# Descripción de los servicios de proceso y redes de Azure

## 5.1 Introducción

Este módulo tiene 14 apartados, en los que se aprenderá de máquinas virtuales, Azure escritorio virtual, recursos requeridos para máquinas virtuales, Azure web Apps, re virtual y endpoints.

## 5.2 Descripción de las máquinas virtuales de Azure

Las máquinas virtuales pertenecen a IaaS, con todo lo que ello conlleva. Son ideales cuando necesitas:

- Control total sobre el sistema operativo.
- La capacidad de correr software específico.
- Configuraciones de red personalizadas.

### Conjuntos de escalado de máquinas virtuales

Permiten configurar y gestionar grupos de VMs identicas sin necesidad de poner a mano los parámetros de cada una. Esto es útil cuando tratamos con ciertos tipos de tareas, como el balanceo de carga. Azure monitoriza el conjunto y de determina cuándo se debe incrementar o decrementar el número de instancias asociadas al sistema.

### Conjuntos de disponibilidad de máquinas virtuales

Son otra herramienta para crear entornos con mayor disponibilidad y seguros. La idea de este sistema consiste en retrasar las atualizaciones y variar la actividad de la red, de forma que se evite una caída total de todas las VMs.

Esto se consigue de dos formas diferentes:

- **Actualizaciones de dominio**: estos grupos se reinician conjuntamente y permite aplicar actualizaciones coordinadamente. Así, se garantiza que dos grupos diferentes no coincidirán a la hora de aplicar parches.
- **Dominio de error**: se agrupan por conexiones físicas a la red eléctrica. De esta manera, se sabrá cuándo ocurre un corte del suministro.

### Cuándo usar VMs

Ejemplos comunes de cuándo es efectivo utilizar máquinas virtuales:

- Durante testeo y desarrrollo.
- Ejecución de aplicaciones en la nube.
- Al expandir tu centro de datos a la nube.
- Durante una recuperación de una catástrofe.

## 5.3 Ejercicio

## 5.4 Describir el escritorio virtual de Azure

Ofrece un windows accesible desde pc/ios/android en la nube para usarlo con la interfaz de usuario normal. Escalable como cualquier MV.

**Mejora de seguridad** usando Azure Actuva Directory. Se puede estableces autentificadores "multifactor" y control de acceso por roles a los usuarios. Los datos estan en la máquina fisica y las aplicaciones estan en la nube, por lo que mejora el riesgo de perder datos confidenciales. Existen máquinas de Windows 10 y 11 que permiten multi-usuario en una sola máquina virtual.

## 5.5 Describir contenedores Azure

MV suponen una reducción del coste en hardware para la empresa, pero si quieres aumentar la productividad lanzando multiples instancas de una aplicación en una misma máquina virtual los contenedores son mejores.

**¿Que son contenedores?** , son entornos virtualizados. En diferencia a las MV no gestionas el sistema operativo de un contenedor, ya que son ligeros se despliegan más rápido.

**MV vs Contenedores** MV es lo que es, una simulación de un ordenador completo, pero cada máquina virtual solo puede correr un único sistema operativo. El contenedor solo tiene una aplicación y sus dependencias, el host-container se encarga de controlar el SO de los contenedores. Los contenedores son ligeros y permiten mantener la separación entre ellos.

**Contenedores Azure**, son PaaS y te permite subir tus contenedores y Azure lanzara sus sercicios. Los contenedores son soluciones para la arquitectura de microservicios, donde se separa la solución en pequeñas e independientes piezas.

## 5.6 Describir Azure Funtions

Servicio _serverles computing_ que se encarga de mantener las MV y los contenedores activos. Ayudar a la gestion de un servidor, actualizaciones por ejemplo, evitando que solo tengas que centrarte en desarrollo.

**Beneficios de  Azure Funtions** son perfectos para cuando solo necesitas preocuparte de que tu código se encuentre ejecutandose. Azure Funtions escala automáticamente, tambien se encarga de lanzar los servicios Azure necesarios y de limpiar los recursos no usados, por lo que no te cobrarán extra. Funtions es esencial para el _serverless computing_ ya que peromite correr cualquier tipo de código sin necesidad de preparar un entorno.

## 5.7 Describir las opciones de hospedaje de aplicaciones

Si quieres hospedar tu aplicacion en Azure debes escoger si quieres contenedor o MV, aunque existe otra opción como Azure App Service.

**Azure App Service** te permite creat y hostear aplicaciones webs, back-end, trabajos en segundo plano o APIs REST, disponibles para windows y linux, con despliegue automático desde GitHub, Azure DevOps o cualquier repositorio Git. Azure App Service es un servicio HTTP que mantiene lenguajes como  .NET, .NET Core, Java, Ruby, Node.js, PHP, o Python.

**Aplicaciones Web** en los lenguajes anteriores

**Aplicacones API** para montar servicios REST, si pinlicas tu API en _Azure Marketplace_ las aplicaciones utilizan HTTP o HTPPS

**Trabajos web** donde puedes lanzar programas o scripts que puede ser programados para lanzarse automáticamente.

**Aplicaciones móviles** que permiten crear para iOS y Android con base de datos SQL en la nube, Autentificaciones como google, twiter, etc. Notificaciones push y back-end en C# y Node.js

## 5.8 Describir Azure Virtual Networking

Son un recurso de Azure, que puede ser como una extensión de tu propia red de tus ordenadores clientes. Te permite:

**Aislamiento y segmentación** ya que puedes crear multiples redes virtuales aisladas, puedes definir rangos de IP publicas y privadas o configurar un DNS.

**Comunicaciones de internet** Puedes habilitar el recibir comunicaciones desde intener usando una IP pública a un recurso Azure.

**Comunicación entre recursos Azure** permite comunicar de manera segura dos servicios Azure, ya que puedes conectar con _App Service_ dos recursos diferentes. O utiizando Azure SQL o cuentas de almacenamiento.

**Comunicación con recursos del dispositivio físico** usando:
1. Point-to-site usando una VPN encriptada si es un ordenadore fuera de la organización.
2. Site-to-site conecta tu VPN a la VPN de Azure, lo que permite que se reconozcan como si estuviesen en una red local.
3. Azure EspressRoute conectividad privada de Azure que no pasa a través de internet.

**Dirigir el tráfico de la red** puedes establer reglas sobre como este tráfico debe ser redirigido. Tamben puedes establez Border Gateway Protocol que funiona con todas las redes Azure.

**Filtrado de tráfico** puedes filtrar el tráfico pro tus subredes usando grupos de seguridad donde puedes establecer reglas sobre permitir o no el trábico, segun IP, puerto o protocolo. Redes virtuales de MV similar a una red física.

**Conectar redes virtuarles** se puede hacer _Peering_ entre dos redes virtuales lo que permite conectarlas entre ellas, usando el red de Microsoft. Puedes tambien definir rutas de usuario  para tener mejor control de tu red virtual.
