# Descripción de los servicios de proceso y redes de Azure

## 5.1 Introducción

Este módulo tiene 14 apartados, en los que se aprenderá de máquinas virtuales, Azure escritorio virtual, recursos requeridos para máquinas virtuales, Azure web Apps, re virtual y endpoints.

## 5.2 Máquinas virtuales de Azure

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

## 5.4 Escritorio virtual de Azure

Ofrece un windows accesible desde pc/ios/android en la nube para usarlo con la interfaz de usuario normal. Escalable como cualquier MV.

En el vídeo hacen publicidad sobre cómo los escritorios virtuales de Azure son absolutamente increíbles y nadie se dará cuenta de que son ventanas remotas.

(*Pero es mentira. Mientras lo dicen enseñan que tienen una latencia de la hostia.*)

Una de las ventajas de las que se habla es la **mejora de la seguridad**, obtenida gracias a  Azure Active Directory. Se puede establecer autentificadores "multifactor" (Estilo 2 Factor Authentication) y control de acceso por roles a los usuarios.

Los datos estan en la máquina fisica y las aplicaciones estan en la nube, por lo que mejora el riesgo de perder datos confidenciales. Existen máquinas de Windows 10 y 11 que permiten multi-usuario en una sola máquina virtual.

## 5.5 Contenedores Azure

VM suponen una reducción del coste en hardware para la empresa, pero si quieres aumentar la productividad lanzando multiples instancas de una aplicación en una misma máquina virtual los contenedores son mejores.

**¿Qué son contenedores?**: son entornos virtualizados. A diferencia de las VMs, no virtualizan un hardware específico. Esto hace que sean más ligeros y se desplieguen más rápido.

**VM vs contenedor**: una máquina virtual es una simulación de un ordenador completo, la cual solo puede correr un único sistema operativo. El contenedor solo tiene una aplicación y sus dependencias, el host-container se encarga de controlar el SO de los contenedores. Los contenedores son ligeros y permiten mantener la separación entre ellos.

**Contenedores Azure**: son PaaS y te permite subir tus contenedores y Azure lanzara sus sercicios. Los contenedores son soluciones para la arquitectura de microservicios, donde se separa la solución en pequeñas e independientes piezas.

> Si quieres aprender sobre las diferencias entre una máquina virtual y un contenedor, puedes mirar [este blog de Atlassian](https://www.atlassian.com/es/microservices/cloud-computing/containers-vs-vms). El artículo es considerablemente mejor que lo que hemos escrito aquí.

## 5.6 Azure Funtions

Servicio _serverles computing_ que se encarga de mantener las VM y los contenedores activos. Ayudar a la gestion de un servidor, actualizaciones por ejemplo, evitando que solo tengas que centrarte en desarrollo.

El nombre de *serverless* viene de que no tienes que gestionar el servidor; únicamente te encargas de tu programa. Un nombre penoso desde luego.

Azure tiene sus propios servicios *serverless* denominados **Azure Funtions**. Son perfectos para cuando solo necesitas preocuparte de que tu código se ejecute. Azure Funtions escala automáticamente. También se encarga de lanzar los servicios de Azure necesarios, así como de limpiar los recursos no usados, por lo que no te cobrarán extra. Funtions es esencial para el _serverless computing_ ya que permite correr cualquier tipo de código sin necesidad de preparar un entorno.

Functions pueden ser *stateful* o *stateless*. Los *stateless* se comportan como si se levantaran por primera vez, aún habiéndose ejecutado con anterioridad. Cuando son *stateful* (denominados también *Durable Functions*), se les proporciona un contexto de ejecución para que puedan retomar su tarea.

## 5.7 Opciones de hospedaje de aplicaciones

Si quieres hospedar tu aplicacion en Azure debes escoger si quieres contenedor o VM.

Convenientemente para esta sección, existe otra opción conocida como Azure App Service.

(*Para nada esto es publicidad*)

### Azure App Service

**Azure App Service** te permite crear y hostear aplicaciones web apps, tareas en segundo plano, backend móviles o APIs REST sin necesidad de gestionar una infraestructura. Está disponible para Windows y Linux, con despliegue automático desde GitHub, Azure DevOps o cualquier repositorio Git que soporte CD (*Continuous Integration*).

Azure App Service es un servicio HTTP que mantiene lenguajes como  .NET, .NET Core, Java, Ruby, Node.js, PHP, o Python.

Existen los diferentes tipos de servicios en App Service:

- **Aplicaciones Web** en los lenguajes anteriores
- **Aplicacones API** para montar servicios REST, si pinlicas tu API en _Azure Marketplace_ las aplicaciones utilizan HTTP o HTPPS.
- **Trabajos web** donde puedes lanzar programas o scripts que puede ser programados para lanzarse automáticamente.
- **Aplicaciones móviles** que permiten crear para iOS y Android con base de datos SQL en la nube, autentificaciones con Google, Twitter, etc. Notificaciones push y back-end en C# y Node.js

## 5.8 Azure Virtual Networking

> Nota del editor: hasta ahora, no hemos traducido propiamente *on premise*. A partir de ahora, se denominarán "in situ", haciéndose referencia a los servidores que una propia empresa posee.

Son un recurso de Azure, que puede ser como una extensión de tu propia red de tus ordenadores clientes.

### Aislamiento y segmentación

Se pueden crear múltiples redes virtuales, siendo capaces así de definir rangos de IP publicas y privadas o configurar un DNS.

### Comunicaciones de internet

Puedes proporcionar una IP pública a un recurso de Azure para así poder recibir comunicaciones desde internet.

### Comunicación entre recursos Azure

Se puede habilitar la comunicación entre dos recursos de Azure mediante dos mecanismos:
- Las redes virtuales se pueden conectar a otros recursos Azure, así como a otras VMs.
- Los endpoints de los servicios se pueden conectar a otro tipo de recursos. Esto te permite conectar DB de Azure al servicio de almacenamento de cuentas de usuarios.

### Comunicaciones con recursos in-situ

Enlaza los propios servidores de la empresa con los de Azure. Mecanismos:
1. Conexión point-to-site: ordenadores de fuera de tu organización hacia la red corporativa. En este caso, se abre una VPN encriptada a la red de Azure.
2. Las site-to-site conectan tu VPN tus VPN in-situ a las de Azure, o una pasarela a la de Azure.
3. Azure EspressRoute: conectividad privada de Azure que no pasa a través de internet. Seguridad más estricta.

### Direcciones del tráfico de la red

Por defecto, Azure conecta subredes de las virtuales, redes de centros in-situ e internet. Además, puedes establer reglas sobre como este tráfico debe ser redirigido, definiendo específicamente cómo se redirigen los paquetes entre subredes. Las rutas BGP (_Border Gateway Protocol_) definidas en tus centros in-situ pueden extenderse a las redes de Azure.

### Filtrado de tráfico

Existen dos maneras diferentes de filtrar el tráfico en tus subredes:
- Mediante grupos de seguridad donde puedes establecer reglas sobre permitir o no el tráfico, basándose en parámetros como la IP, puerto o protocolo.
- _Network virtual appliances_: máquinas virtuales específicas que se asemejan a redes _appliance_ reforzadas. Estas redes llevan a cabo un propósito específico, como un firewall o un balanceador de carga.

### Conectar redes virtuarles

Se puede hacer _Peering_ entre dos redes virtuales, lo que las conecta  mediante la red de Microsoft, y no internet. Esto hace que el tráfico entre ellas sea privado.

Puedes tambien definir rutas de usuario (UDR, _user defined routes_) para tener mejor control sobre el flujo de tu red.

## 5.9 Ejercicios

> Haz los dos ejercicios de este módulo seguidos, o si no, no funcionará el segundo.

## 5.10 Redes privadas virtuales de Azure

Una *virtual private network* (VPN) utiliza un túnel encriptado en otro túnel. Suelen utilizarse para conectar dos o más redes privadas a través de redes no seguras, como puede ser internet. El tráfico es encriptado.

### Puertas de enlace de una VPN

> Nota: recomiendo mirar lo que es una [_gateway_ (puerta de enlace)](https://www.wikiwand.com/en/Gateway_(telecommunications)) y un [proxy inverso](https://www.wikiwand.com/en/Reverse_proxy).

Las instancias de las VPN gateways se despliegan en una subred específica y conectan...

- Centros de datos in-situ a redes virtuales (conexiones site-to-site).
- Dispositivos individuales a redes virtuales (conexiones point-to-site).
- Redes virtuales a otras redes virtuales (conexiones network-to-network).

Cuando estableces una puerta de enlace VPN debes establecer si estara basada en políticas o rutas.

- Basado en políticas establece IP estáticas de paquetes y el dispositivo evalúa estos paquetes de IP para establecer el tunel por el que enviarlas.
- Basado en rutas con IP dinámica o estática decide qué interfaz de tunel será la correcta para enviar el paquete. Estos métodos son los preferidos para dispositivos físicos. Además, son los más resistentes a cambios en la topología de la red. Recomendadas cuando quieres...
  - Conexines entre redes virtuales.
  - Conexiones punto a sitio.
  - Conexiones multisitio.
  - Coexistencia con una Azure ExpressRoute gateway.

### Escenarios de alta disponibilidad

Si usas tu VPN quieres tener seguridad y alta diponibilidad, hay métodos para ofrecer eso:
1. Activo/espera
2. Activo/activo
3. Fallo _ExpressRoute_
4. Puertas de entrada con redundacia de zona

> Más información sobre esta información VPN en el propio curso:
>
> https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/10-virtual-private-networks

## 5.11 Azure ExpressRoute

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

## 5.12 DNS Azure

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
