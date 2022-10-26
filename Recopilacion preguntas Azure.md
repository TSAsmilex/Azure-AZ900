# Recopilacion preguntas


## 1. Aspectos básicos de Microsoft Azure: Descripción de los conceptos de nube 

### 1.1. Descripción de la informática en la nube

1. ¿Qué es la informática en la nube?

    __a) Entregar servicios informáticos mediante Internet.__

    b) Entregar servicios de almacenamiento mediante Internet.

    c) Entregar sitios web accesibles mediante Internet.

    __*Anotacion:__ La informática en la nube es la prestación de servicios informáticos a través de Internet.

2. ¿Qué modelo de nube usa algunos centros de datos centrados en proporcionar servicios en la nube a cualquier persona que los quiera y algunos centros de datos centrados en un solo cliente?

    a) Nube pública

    __b) Nube híbrida__

    c) Nubes múltiples

    __*Anotacion:__ El modelo de nube híbrida es una combinación de la nube pública y la nube privada, con ambos centros de datos dedicados únicamente a un cliente y a centros de datos que se comparten con el público.

3. Según el modelo de responsabilidad compartida, ¿qué tipo de servicio en la nube sitúa la mayor responsabilidad en el cliente?

    __a) Infraestructura como servicio (IaaS)__

    b) Software como servicio (SaaS)

    c) Plataforma como servicio (PaaS)

    __*Anotacion:__ IaaS sitúa la mayor responsabilidad en el consumidor y el proveedor de servicios en la nube es el responsable de los conceptos básicos de seguridad física, energía y conectividad.

______________________

### 1.2. Descripción de las ventajas de usar servicios en la nube 

1. ¿Qué tipo de escalado implica agregar o quitar recursos (como máquinas virtuales o contenedores) para satisfacer la demanda?

    a) Escalado vertical

    __b) Escalado horizontal__

    c) Escalado directo

    __*Anotacion:__ El escalado horizontal agrega o resta el número de recursos.

2. ¿Qué se describe como la capacidad de un sistema de recuperarse de los errores y seguir funcionando?

    __a) Confiabilidad__

    b) Predicción

    c) Escalabilidad

    __*Anotacion:__ La confiabilidad es la capacidad de un sistema para recuperarse de errores y seguir en funcionamiento y es uno de los pilares del Marco de buena arquitectura de Microsoft Azure.

______________________

### 1.3. Descripción de los tipos de servicio en la nube 

1. ¿Qué tipo de servicio en la nube es más adecuado para una migración mediante lift-and-shift de un centro de datos local a una implementación en la nube?

    __a) Infraestructura como servicio (IaaS)__

    b) Plataforma como servicio (PaaS)

    c) Software como servicio (SaaS)

    __*Anotacion:__ Con un tipo de servicio IaaS, puede aproximarse a su entorno local, lo que hace que realizar una transición a la nube mediante lift-and-shift sea relativamente sencillo.

2. ¿En qué tipo de servicio en la nube se encuentra normalmente una solución de seguimiento de finanzas y gastos?

    a) Infraestructura como servicio (IaaS)

    b) Plataforma como servicio (PaaS)

    __c) Software como servicio (SaaS)__

    __*Anotacion:__ SaaS proporciona acceso a soluciones de software, como el seguimiento de finanzas y gastos, el correo electrónico o los sistemas de vales.

______________________
______________________

## 2. Aspectos básicos de Azure: Descripción de la arquitectura y los servicios de Azure

### 2.1. Describir los componentes arquitectónicos principales de Azure

1. ¿En cuántos grupos de recursos puede estar un recurso al mismo tiempo?

    __a) Uno__

    b) Dos

    c) Tres

    __*Anotacion:__ Un recurso sólo puede estar en un grupo a la vez.

2. ¿Qué ocurre con los recursos de un grupo de recursos cuando se aplica una acción o configuración en el nivel de grupo de recursos?

    a) Los recursos actuales heredan la configuración, pero los recursos futuros, no.

    b) Los recursos futuros heredan la configuración, pero los actuales, no.

    __c) La configuración se aplica a los recursos actuales y futuros.__

    __*Anotacion:__ Los recursos heredan los permisos de su grupo de recursos.

3. ¿Qué característica de Azure replica los recursos entre regiones que están al menos a 300 millas de distancia entre sí?

    a) __Pares de región__

    b) Availability Zones

    c) Regiones soberanas

    __*Anotacion:__ La mayoría de las regiones de Azure se emparejan con otra región de la misma zona geográfica (por ejemplo, EE. UU., Europa o Asia) que esté como mínimo a 300 millas de distancia.

______________________

### 2.2. Descripción de los servicios de proceso y redes de Azure

1. ¿Qué característica de máquina virtual de Azure escalona las actualizaciones en todas las máquinas virtuales en función de sus dominios de actualización y error?

    __a) Conjuntos de disponibilidad__

    b) Conjuntos de escalado

    c) Conjuntos de actualizaciones

    __*Anotacion:__ Los conjuntos de disponibilidad escalonan las actualizaciones de máquina virtual en función de sus dominios de actualización y error.

2. ¿Qué servicio de Azure permite a los usuarios utilizar una versión hospedada en la nube de Windows desde cualquier ubicación y conectarse desde los exploradores más modernos?

    __a) Azure Virtual Desktop__

    b) Azure Virtual Machines

    c) Azure Container Instances

    __*Anotacion:__ Azure Virtual Desktop proporciona acceso a una versión hospedada en la nube de Windows y funciona con la mayoría de los exploradores modernos.

______________________

### 2.3. Descripción de los servicios de almacenamiento de Azure 
1. ¿Qué herramienta mantiene automáticamente los archivos entre un servidor Windows local y un entorno de nube de Azure actualizado?

    __a) Azure File Sync__

    b) Explorador de Azure Storage

    c) AzCopy

    __*Anotacion:__ Azure File Sync garantiza la sincronización bidireccional de los archivos entre los servidores de Windows para el entorno local y en la nube.

2. ¿Qué opción de redundancia de almacenamiento proporciona el mayor grado de durabilidad, con 16 nueves de durabilidad?

    a) Almacenamiento con redundancia local

    b) Almacenamiento con redundancia de zona

    __c) Almacenamiento con redundancia de zona geográfica__

    __*Anotacion:__ El almacenamiento con redundancia geográfica (GRS) y el almacenamiento con redundancia de zona geográfica (GZRS) proporcionan 16 nueves de durabilidad.

3. ¿Qué servicio de Azure Storage admite el análisis de macrodatos, así como el control de tipos de datos binarios y de texto?

    __a) Azure Blobs__

    b) Azure Files

    c) Azure Disks

    __*Anotacion:__ Azure Blobs es un almacén de objetos que se puede escalar de forma masiva para datos de texto y binarios. Azure Blobs también incluye compatibilidad con el análisis de macrodatos mediante Data Lake Storage Gen2.
    
______________________

### 2.4. Descripción de la identidad, el acceso y la seguridad de Azure

1. ¿Qué herramienta de Azure Active Directory puede cambiar las credenciales necesarias para iniciar sesión en función de las señales, como dónde se encuentra el usuario?

    __a) Acceso condicional__

    b) Acceso de invitado

    c) Inicio de sesión sin contraseña

    __*Anotacion:__ El acceso condicional es una herramienta que usa Azure Active Directory para permitir (o denegar) el acceso a los recursos en función de señales de identidad. Acceso condicional puede cuestionar un segundo factor de autenticación si las señales de inicio de sesión son inusuales o proceden desde una ubicación inesperada.

2.  ¿Qué modelo de seguridad supone el peor escenario de seguridad y protege los recursos en consecuencia?

    __a) Confianza cero__

    b) Defensa en profundidad

    c) Control de acceso basado en roles.

    __*Anotacion:__ Confianza cero es un modelo de seguridad que supone el peor de los escenarios posibles y protege los recursos con esa expectativa.

3. A un usuario se le asignan simultáneamente varios roles que usan el control de acceso basado en rol. ¿Cuáles son sus permisos reales? Los permisos de rol son: Rol 1: leer || Rol 2: escritura || Rol 3: lectura y escritura.

    a) Solo lectura

    b) Solo escritura

    __c) Lectura y escritura__

    __*Anotacion:__ El control de acceso basado en rol, mediante un modelo de permiso, concede todos los permisos asignados en todos los roles asignados.

