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

Trata sobre cómo utilizar los scripts de Azure para instalar Nginx en una VM de Ubuntu. No es especialmente interesante.

## 5.4 Describir el escritorio virtual de Azure

Ofrece un windows accesible desde pc/ios/android en la nube para usarlo con la interfaz de usuario normal. Escalable como cualquier MV.

En el vídeo hacen publicidad sobre cómo los escritorios virtuales de Azure son absolutamente increíbles y nadie se dará cuenta de que son ventanas remotas.

(*Pero es mentira. Mientras lo dicen enseñan que tienen una latencia de la hostia.*)

Una de las ventajas de las que se habla es la **mejora de la seguridad**, obtenida gracias a  Azure Active Directory. Se puede establecer autentificadores "multifactor" (Estilo 2 Factor Authentication) y control de acceso por roles a los usuarios.

Los datos estan en la máquina fisica y las aplicaciones estan en la nube, por lo que mejora el riesgo de perder datos confidenciales. Existen máquinas de Windows 10 y 11 que permiten multi-usuario en una sola máquina virtual.

## 5.5 Describir contenedores Azure

VM suponen una reducción del coste en hardware para la empresa, pero si quieres aumentar la productividad lanzando multiples instancas de una aplicación en una misma máquina virtual los contenedores son mejores.

**¿Qué son contenedores?**: son entornos virtualizados. A diferencia de las VMs, no virtualizan un hardware específico. Esto hace que sean más ligeros y se desplieguen más rápido.

**VM vs contenedor**: VM es lo que es, una simulación de un ordenador completo, pero cada máquina virtual solo puede correr un único sistema operativo. El contenedor solo tiene una aplicación y sus dependencias, el host-container se encarga de controlar el SO de los contenedores. Los contenedores son ligeros y permiten mantener la separación entre ellos.

**Contenedores Azure**: son PaaS y te permite subir tus contenedores y Azure lanzara sus sercicios. Los contenedores son soluciones para la arquitectura de microservicios, donde se separa la solución en pequeñas e independientes piezas.

Si quieres aprender sobre las diferencias entre una máquina virtual y un contenedor, puedes mirar [este blog de Atlassian](https://www.atlassian.com/es/microservices/cloud-computing/containers-vs-vms).

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

## 5.9 Ejercicios

## 5.10 Describir redes Azure privadas

Virtual private network(VPN) que son usadas para conectar redes privadas a redes no privadas, el trafico esta encriptado para evitar ataques.

**Puertas de enlace VPN** conéctar centro de datos fisicos con site-to-site, conectar dispositivos individuales con point-to-site o conectar redes con network-to-network. Toda la información esta encriptada por un tunel privado.

Cuando estableces una puerta de enlace VPN debes establecer si estara basada en politicas o rutas. Basado en políticas establece IP estáticas de paquetes y el dispositivo evalía estos paquetes de IP para establecer el tunel por el que enviarlas. Basado en touter con IP dinámica o estática decide que interfaz de tunel sera la correcta para enviar el paquete, estos métodos son preferidos para dispositívios físicos.

**Escenarios de alta disponibilidad** si usas tu VPN quieres tener seguridad y alta diponibilidad, hay métodos para ofrecer eso:
1. Activo/espera
2. Activo/activo
3. Fallo _ExpressRoute_
4. Puertas de entrada con redundacia de zona

``` Más información sobre esta información VPN en el propio curso ```

[VPN](https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/10-virtual-private-networks)

## 5.11 Describir Azure ExpressRoute

Es una conexión de tus dispositivos físicos con Microsoft Cloud y sus servicios, puede ser una conexión any-to-any, point-to-point o conexión cruzada virtual. Al no ir por redes públicas ofrece mayor velocidad y seguridad.

**Beneficios de ExpressRoute** 
1. Conexión de los servicios de Microsoft cloud en todas las regiones
2. Conectividad global entre todas las regiones y sericios gracias a ExpressRoute Global
3. Enlazado dinámico 
4. Redundacia integrada

**Modelos de conexión ExpressRoute**
1. Localización contigua a un centro de datos de nube (co-location)
2. Point-to-point
3. Any-to-any
4. Directamente desde lugares ExpressRoute

Además se garantiza la seguridad desde todoas esta comunicaciones.

## 5.12 Describir DNS Azure

La descripción es tan increible como DNS de Azure y ya, puedes hacer cosas que hace una DNS.

**Beneficios de Azure DNS**
1. Fidelidad y rendimiento
2. Seguridad con logs, restricción de recursos y control de acceso por roles
3. Facilidad de uso 
4. Customización de redes virtuales con dominios privados
5. Registro de _Alias_ 

Azure DNS no ofrece un nombre de dominio, debes de comprarlo desde la aplicación correspondiente y poder usarlo en Azure

## 5.13 Preguntas

[Respuestas](./Recopilacion%20preguntas%20Azure.md)

## 5.14 Sumario
