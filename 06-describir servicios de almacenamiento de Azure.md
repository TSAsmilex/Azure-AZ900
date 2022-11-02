# Describir servicios de almacenamiento de Azure

## 6.1 Introducción

Serivicios de almacenamiento de Azure, sus tiers, sus opciones de redundancia y almacenamiento, opciones de movimiento de archivos y migraciones.

## 6.2 Describir cuentas de almacenamiento Azure

Almacenamiento en la nube, envio de mensajes, compartir archivos, guardado en disco, etc. Blob Store sirve para almacenar datos en binario para envio de datos o recuperación.

Accesible HTTP y HTTPS, tambien al crear una cuenta puedes escoger el nivel de redundancia:

1. Locally redundant storage (LRS)
2. Geo-redundant storage (GRS)
3. Read-access geo-redundant storage (RA-GRS)
4. Zone-redundant storage (ZRS)
5. Geo-zone-redundant storage (GZRS)
6. Read-access geo-zone-redundant storage (RA-GZRS)

[Tipos de cuenta y sus niveles](https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/2-accounts)


### Cuentas de almacenamiento puntos finales

El beneficio de Azure Storage es tener unicamente un nombre para todos tus datos de Azure. El nombre sigue las reglas de 3 a 24 carácteres con mayusculas, minusculas y números, además de ser única. Los posibles puntos finales de Azure son, blob, data lake storage gen 2, azure files, queue Storage y table storage. Todos ellos segun la url, https://nombre.tipodebasededatos.core.windows.net

## 6.3 Describir la redundancia de almacenamiento Azure

Azure Storage guarda multiples copas de tus datos para estar protegido en caso de fallos. A la hora de escoger el nivel de redundancia debe ser un intermedio entre bajo coste y alta disponibilidad, además de factures como:
1. Como tus datos se replican en tu región primaria
2. Si tus datos se van a replicar a una segunda region geográficamente distinta.
3. Si tu aplicación requiere acceso de lectura a la segunda región si la primera falla.

### Redundacia en tu zona primaria
Los datos se replican 3 veces en tu zona primaria, puede ser _locally redundant storage(LRS)_ ó _zone-redundant storage(ZRS)_

**_Locally redundant storage_**, replica tres veces tus datos en un mismo centro de datos de tu region primaria, con una durabilidad de once nueves decimales(99,99999999%) de durabilidad de objetos sobre un mismo año. Esta es la versión más barata, pero si ocurre una catastrofe natura tus datos se perderan.

**_Zone-redundant storage_**, similar al anterior pero utiliza 3 zonas de disponibilidada lo que proporciona doce nueves decimales de durabilidad sobre un mismo año.

### Redundancia en una región secundaria

Para aplicaciones de gran durabilidad se puede escoger tener una segunda region con copias a gran distancia de la region principal, protegiendolo incluso ante una catastrofe. 

**_Geo-Redundant Storage_** (GRS) se copia de manera sincrona las tres copias de LRS, ofreciendo dieciseis nueves de decimales de durabilidad sobre un mismo año.

**_Geo-zone-redundant Strorage_** (GZRS) realiza las copias de ZRS dando tambien dieciseis nueves de decimales de durabilidad sobre un mismo año.

### Leer datos de la segunda región

Debes de tener redundancia GRS o GZRS y Azure te permite leer de aquellos datos si el primario no esta disponible.

## 6.4 Describir servicios de almacenamiento de Azure

Los servicios son:
1. _Blobs_- objetos de almacenamiento amximos para texto y datos binarios.
2. _Files_- compartir archivos
3. _Queues_- Almacenamiento de mensajes 
4. _Disk_- volumenes de almacenamiento al nivel de bloque

### Benefícios del almacenamiento Azure
1. **Alta  isponibilidad y durabilidad** gracias a la redundancia anteriormente vista, tener datos en diferentes regiones permite protegerlos, además estos datos replicados seguiran estando altamente disponibles.

2. **Seguros** los datos estan encryptados y sobre un control de acceso muy fino.

3. **Escalable** 

4. **Gestionable** Azure lleva mantenimiento hardawre y actualizaciones por ti.

5. **Accesible** utilizando HTTP y HTTPS. Ofrece clientes en multiples lenguajes además de REST API además de scripts en sus terminales Azure(Azure PowerShell y Azure CLI).

### Almacenamiento de Blob
Es la solución de Azure para el almacenamiento de objetos, sean texto o datos binarios (*Se considera dato binario archivos de video, imagen, ejecutables, etc*) por lo que no estan limitados a un formato de archivo. Este sistema Azure no esta estructurado por lo que permite un almacenamiento muy amplio.

Los Blops son ideales para:
- Ofrecer imágenes o documentos a un navegador
- Almacenar archivos de acceso distribuido
- _Streaming_ de video y audio
- Almacenar y recuperar copias de seguridad
- Almacenar datos de análisis realizados in situ o de servicios Azure.

### _Tiers_ de almacenamiento Blob

Debido a las diferentes frecuencias de acceso a los archivos, se generan estos _Tiers_
- _Hot access tier_ para datos de acceso muy frecuente.
- _Cool access tier_ para datos de poco acceso que son almacenados durante 30 días.
- _Archive access tier_ para datos rara vez accedidos y almacenados durante 180 días con requisitos de latencia flexibles.

Además, para la consideración de _tier_ se tiene también en cuenta lo siguiente.
- Solo el _tier hot y cool_ pueden ser asignados a nivel de cuenta.
- Los _tier_ puede sern puestos en un blob durante o después de ser subido a Azure.
- Los datos _cool_ puede tener una menor disponibilidad que _hot_ pero el resto de características son similares. Una menor disponibilidada SLA(_Service-level agreement_) y un coste de acceso mayor permiten un coste de almacenaje bajo.
- _Archive storage_ almacena datos _offline_ pero tiene un mayor coste de acceso a los datos.

### Archivos Azure

Utiliza protocolos estándar en la industria como _Server Message Block_ (SMB) ó _Network File System_ (NFS). Los recursos compartidos pueden ser montados in situ o en la nube. SBM esta diponible en Windows, Linux y macOS mientras que NFS no lo esta para windows.

**Beneficios clave de archivos Azure**
- **Acceso compartido**, usando los protocoles SMB Y NFS puedes modifiar tus recursos compartidos de in situ a la nube Azure sin problemas.
- **Totalmente gestionado**,  los recursos compartidos de Azure no dependen del hardware o el sistema operativo.
- **_Scripting and tooling_** los terminales azures pueden ser usados para administrar los recursos compartidos de Azure.
- **Resiliencia** _Azure files_ ha sido diseñado para estar siempre disponible (*Propaganda*)
[¿Que es resiliencia?](https://es.wikipedia.org/wiki/Resiliencia_(psicolog%C3%ADa))
- **Programabilidad familiar**, los desarrolladores puede reutilizar su código exiistente gracias a las APIs _System IO_, las librerías Azure y el servicio REST.

### _Queue storage_

Es un servicio para almacenar grandes cantidades de mensajes, usando autentificacion HTTP y HTTPS. Una _queue_ puede almacenar tantos mensajes como tu almacenamiento ed cuenta, cada mensaje pesa 64KB y suelen usarse para crear backlog.

Es posible combinarlas con las funciones de Azure para que realicen una accióin cuando se recibe un mensaje.

### Almacenamiento en disco

Similar al almacenamiento en disco físico, pero de manera virtualizazda por Azure. Son volúmenes al nivel de bloque que ofrecen una gran resiliencia y disponibilidad (mayor que un disco físico).

## 6.5 Ejercicio
> Funciona la guía

## 6.6 Opciones de migración Azure

Azure permite migraciones en tiempo real o asíncronas usando Azure Data Box.

### _Azure Migrate_

Es un servicio de ayuda de migración in situ a la nube. Proporciona:
- **Plataforma de migración unificada** (Azure Migrate)
- **Variedad de herramientas** como _Discovery and assessment_ ó _Server Migration_. Además tiene integración con otros servicios Azure y con ISV (_Independent software vendor_).
- **Evaluación y migracion** en el portal Azure Migrate puedes evaluar y migrar tu infraestructura in situ a Azure.

### Herramientas integradas
- **_Discovery and assessment_**, evalua y descrube servidores in situ o en máquinas virtuales.
- **_Server Migration_** 
- **_Data Migration Assistant_** es una herramienta independiente para verificar servidores SQL. Permite  detectar poblemas bloqueantes durante la migración, funcionalidades no soportadas o nuevas funcionalidades que puedan servir para después de la migración.
- **_Azure Database Migration Service_** migración de base de datos in situ hacia Azure.
- **_Webb app migration assistant_** herramienta independiente que evalua páginas webs in situ.
- **_Azure Data Box_** permite mover grandes cantidades de datos offline hacia Azure.

### _Azure Data Bax_

Es un servicio de migración física que permite transferir grandes cantidades de datos de manera rápida, segura y barata. Te llevan un dispositivo de almacenamiento de 80 TB y lo recogen posteriormente para llevarlo a un centro de datos, se suben en cuanto Micrisoft obtenga la _Data Box_. Este dispositivo esta protegido por una carcasa resistente.

**Casos de uso**

Para transferencia de datos de más de 40 TB y/o con conexión limitada a la red. 

Casos para enviar datos a Azure
- **_Onetime migration_** mover gran cantidad de datos in situ hacia Azure.
- **Mover bibiliotecas multimedia sin conexión.**
- **Migrar MV, Serviores SQL y Aplicaciones.**
- **Mover tu histórico de datos** hacia Azure para un análisis en profundidad y uso de HDInsight.
- **_Initial bulk transfer_**, se usa una _Data Box_ inicial y después incrementos a través de la red.
- **Actualziaciones periódicas**, si se generan gran cantidad de datos periodicamente que se necesitan enviar a Azure.

Casos para traer datos desde Azure
- **Recuperación de desastres**, recuperar una copia desde Azure para restablecer los dispositivos in situ.
- **Requisitos de seguridad**, cuando debes exportar datos fuera de Azure debido a requisitos de seguridad del gobierno.
- **Migración de vuelta a in situ**

Todos los _Data Box_ son limpiados según el estándar NIST 800-88r1.

## 6.7 Opciones de movimiento de archivos Azure

Para cuando no es necesario _Data Box_

### AzCopy

Es una linea de comandos que permite copiar Blobs o archivos de tu cuenta. Puedes subir ficheros, descargar, copiar o sincronizar.

- _Azure Storage Explorer_ Aplicación independiente que ofrece usar AzCopy con interfaz.

### _Azure file Sync_

Herramienta centrada en compartir archivos (*archivos Azure*) con flexibilidad, rendimiento y compatabilidada con el sistema de ficheros de windows.

Con _Azure File Sync_ puedes:
- Usar cualqueir protocolo en servidores Windows además de SMB, NFS y FTPS.(*Aparecen en el apartado 6.4, sub-apartado archivos de azure*)
- Tener tantas cachés como necesites.
- Remplazar servidores locados fallidos usando *Azure File Sync* en un nuevo servidor.
- Configuración de _tier_ de archivos.

## 6.8 Preguntas
[Respuestas](./Recopilacion%20preguntas%20Azure.md)

## 6.9 Recapitulación