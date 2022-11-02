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

## 5.4 Describir servicios de almacenamiento de Azure

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