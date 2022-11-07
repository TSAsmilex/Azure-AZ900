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

ARM es un servicio de gestión y despliegue de Azure, proporciona gestion de capas que te permite crear, actualizar y borrar recursos, todo lo que haga con Azure pasa por ARM. Si es la API un SDK sigue pasando por ARM ya que se encarga de gestionar la petición y autentificaciones.

### Beneficios de Azure Resource Manager

- Gestionar tus infraestructuras a través de _templates_ en lugar de _scripts_, usando JSON.
- Desplegar, gestionar y monitorear tus recursos en grupos.
- Re-desplegar soluciones a través del ciclo de desarrollo.
- Definir dependencias entre recursos para ser desplegadas en el orden correcto.
- Aplicar control de acceso RBAC.
- Aplicar etiquetas a los recursos.
- Clarificar los gastos de tu organización y sus facturas.

El video explica que ARM tiene organización de recursos automatica para que sea más sencillo.

### ARM templates

Es una descripción declarativa en formato JSON donde se establece que recursos quieres usar y esta lista se revisa antes de cada despliegue para comprobar que todos los recursos estan disponibles y serán creados correctamente. Los desarrolladores, profesionales DevOps y profesiones IT necesitan definir la configuracion de recurosos solo en el ARM _template_ y esta se encargará de todo.(Los _templates_ puede ejecutar código PowerShell y Bash).

**Beneficiones de usar ARM templates**

- **Sintaxis declarativa**  te permiten desplegar infraestructuras Azure declarativamente, es decir, declaras que quieres desplegarla pero no necesitas escribir toda la programación de comandos.
- **Resultados repetibles** , puedes usar el mismo ARM _template_ si sabes que tienen el mismo entorno.
- **Orquestación** para no tener que preocuparse de la complejidad de ordenacion de operaciones, ya que ARM lo hará por nosotros.
- **Archivos modulares** puedes dividir ARM _templates_ en piezas más pequeñas y reutilizarlas o incluso enlazarlar entre ellas.
- **Extensibilidad** puede incluir código PowerShell o Bash a tu _template_ para dotarlo de más poder.

## 10.5 Preguntas

[Respuestas](./Recopilacion%20preguntas%20Azure.md)

## 10.6 Sumario