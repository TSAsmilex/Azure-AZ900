# Describir las características y herramientas para administrar e implementar recursos de Azure

## 10.1 Introducción

- Describir Azure Portal
- Describir Azure Cloud Shell, incluida la CLI de Azure y Azure PowerShell
- Describir el propósito de Azure Arc
- Describir Azure Resource Manager (ARM) y plantillas de Azure ARM

## 10.2 Describir herramientas para interactuar con Azure

### Azure Portal

Es una web que unifica las entradas de consola en una interfraz gráfica que permite:

- Construir, gestionar y monitorizar todo
- Crear _dashboards_
- Configurar la accesibilidad

Se actualiza y es resiliente, además de estar disponble siempre.

### Azure Cloud Shell

Es una herramienta basada en navegador que te permite crea, gestionar y configurar recursos azure. Puede ser usado con Azure Powershel o CLI.

Tiene varias funcionalidades como:

- No requiere instalación al ser una herramienta de navegador.
- Utiliza autentificación con las credenciales de Azure
- Puedes escoger entornos familiares como Azure Powershel o CLI.

### ¿Que es Azure PowerShel?

Es un shell para desarrolladores, DevOps y profesionales IT para que ejecuten comandos, llamados _mommand-lets_ (cmdlets). Estos comandos llaman a la API REST de Azure y pueden ejecutarse independientemente o combinados para operaciones complejas como:

- _Setup_, division y mantenimiento de recursos individuales o conectados multiples recursos.
- Despliege de infraestructuras grandes.

### ¿Que es Azure CLI?

Es un equivalente a Azure PowerShell pero con diferencia de sintaxis, ya que utiliza comandos bash en vez de los propios de Azure.

## 10.3 Describir el propósito de Azure Arc

Gestionar entornos de multiples nubes o nubes híbridas puede ser complicado. Azure Arc te permite extenden tus monitoreos y conformidades Azure hacia tu nube híbrida o multinube. Azure Arc proporcina una manera centralizada y unificada de:

- Gestionar tus entornos conjuntamente proyectoando tus recursos no Azure en Azure Resource Manager (ARM).
- Gestionar multinubes e híbridas maquinas vituales, Kubernetes y bases de datos como si estuviesen siendo ejecutadas en Azure.
- Usar serivicios familiares de Azure.
- Usar ITOps tradicionales mientras introduces prácticas DevOps.
- Configurar localizaciones como una capa de abstracción encima de la extensión Azure Arc Kubernetes y cluster.

**¿Que hace Azure Arc fuera de Azure?**
Permite Gestionar Servidores, _Kubernetes cluster_, servicios de datos Azure, Servidores SQL y máquinas virtuales.

## 10.4 Describir Azure Resource Manager y Azure ARM templates

