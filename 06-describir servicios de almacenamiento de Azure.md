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

**Cuentas de almacenamiento puntos finales** el beneficio de Azure Storage es tener unicamente un nombre para todos tus datos de Azure. El nombre sigue las reglas de 3 a 24 carácteres con mayusculas, minusculas y números, además de ser única. Los posibles puntos finales de Azure son, blob, data lake storage gen 2, azure files, queue Storage y table storage. Todos elos segun la url, https://nombre.tipodebasededatos.core.windows.net

## 6.3 Describir la redundancia de almacenamiento Azure

Azure Storage guarda multiples copas de tus datos para estar protegido en caso de fallos. A la hora de escoger el nivel de redundancia debe ser un intermedio entre bajo coste y alta disponibilidad, además de factures como:
1. Como tus datos se replican en tu región primaria
2. Si tus datos se van a replicar a una segunda region geográficamente distinta.
3. Si tu aplicación requiere acceso de lectura a la segunda región si la primera falla.

**Redundacia en tu zona primaria** los datos se replican 3 veces en tu zona primaria, puede ser _locally redundant storage(LRS)_ ó _zone-redundant storage(ZRS)_

Locally redundant storage, replica tres veces tus datos en un mismo centro de datos de tu region primaria, con una durabilidad de once nueves decimales(99,99999999%) de durabilidad de objetos sobre un mismo año. Esta es la versión más barata, pero si ocurre una catastrofe natura tus datos se perderan.

Zone-redundant storage, similar al anterior pero utiliza 3 zonas de disponibilidada lo que proporciona doce nueves decimales de durabilidad sobre un mismo año.

**Redundancia en una región secundaria** para aplicaciones de gran durabilidad se puede escoger tener una segunda region con copias a gran distancia de la region principal, protegiendolo incluso ante una catastrofe. 

Geo-Redundant Storage (GRS) se copia de manera sincrona las tres copias de LRS, ofreciendo dieciseis nueves de decimales de durabilidad sobre un mismo año.

Geo-zone-redundant Strorage (GZRS) realiza las copias de ZRS dando tambien dieciseis nueves de decimales de durabilidad sobre un mismo año.

**Leer datos de la segunda región** debes de tener redundancia GRS o GZRS y Azure te permite leer de aquellos datos si el primario no esta disponible.

## 5.4 Describir servicios de almacenamiento de Azure

Los servicios son:
1. Blobs- objetos de almacenamiento amximos para texto y datos binarios.
2. Files- compartir archivos
3. Queues- Almacenamiento de mensajes 
4. Disk- volumenes de almacenamiento al nivel de bloque

****
