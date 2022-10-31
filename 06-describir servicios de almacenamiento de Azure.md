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

**Cuentas de almacenamiento puntos finales** el beneficio de Azure Storage es tener unicamente un nombre para todos tus datos de Azure. El nombre sigue las reglas de 3 a 24 carácteres con mayusculas, minusculas y números, además de ser única. Los posibles puntos finales de Azure son, blob, data lake storage gen 2, azure files, queue Storage y table storage. Todos elos segun la url, htttps://nombre.tipodebasededatos.core.windows.net

## 6.3 Describir la redundancia de almacenamiento Azure

