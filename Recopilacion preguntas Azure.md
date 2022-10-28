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

______________________
______________________

## 3. Azure Fundamentals: Describe Azure management and governance

### 3.1. Descripción de la administración de costos en Azure

1. ¿Qué característica de Azure puede ayudar a mantener la organización y a realizar el seguimiento del uso en función de los metadatos asociados a los recursos?

    __a) Etiquetas__
    
    b) Seguimientos
    
    c) Valores
    
    __*Anotacion:__ Las etiquetas permiten asociar metadatos a un recurso para ayudar a realizar el seguimiento de la administración de recursos, los costos y la optimización, la seguridad, etc.


2. ¿Cuál es el mejor método para calcular el costo de la migración a la nube mientras se incurre en costos mínimos?

    a) Migrar una pequeña muestra a la nube y realizar el seguimiento de los costos en el tiempo.
    
    __b) Usar la calculadora de costo total de propiedad para calcular los costos esperados.__
    
    c) Migrar a la nube, pero realizar el seguimiento del uso estrechamente mediante etiquetas para comprender rápidamente los costos.
    
    __*Anotacion:__ La calculadora de costo total de propiedad permite introducir la infraestructura y los requisitos actuales, y proporciona una estimación para la ejecución en la nube.

______________________

### 3.2. Descripción de las características y herramientas de Azure para la gobernanza y el cumplimiento

1. ¿Cuántos parámetros necesita un artefacto de Azure Blueprints para ser válido?

    __a) 0__
    
    b) 1
    
    c) 2
    
    __*Anotacion:__ Es posible que los artefactos no tengan parámetros adicionales. Un ejemplo es la directiva Implementar la detección de amenazas en servidores SQL Server, que no requiere ninguna configuración adicional.

2.  ¿Cómo puede impedir que se creen recursos no compatibles, sin tener que evaluar manualmente cada recurso a medida que se crea?

    __a) Azure Policy__
    
    b) Azure Blueprint
    
    c) Azure Resource Monitor
    
    __*Anotacion:__  Azure Policy le permite crear directivas e iniciativas (grupos de directivas) que impiden la creación de recursos no compatibles.
    
______________________

### 3.3. Descripción de las características y herramientas para administrar e implementar recursos de Azure

1. ¿Qué servicio le ayuda a administrar los entornos de Azure, locales y de varias nubes?

    __a) Azure Arc__
    
    b) Azure Policy
    
    c) Azure Cloud Manager
    
    __*Anotacion:__ Azure Arc, junto con Azure Resource Manager, le permite ampliar el cumplimiento y la supervisión de Azure a las configuraciones híbridas y de varias nubes

2.  ¿Qué dos componentes podría usar para implementar una implementación de "infraestructura como código"?

    __a) Azure Blueprints y plantillas de ARM__
    
    b) Azure Policy y Azure Arc
    
    c) Azure Monitor y Azure Arc
    
    __*Anotacion:__ Azure Blueprints aplica directivas de forma automatizada y las plantillas de ARM le permiten implementar el recurso como código. El uso conjunto de los dos ayuda a garantizar que se implementen recursos coherentes y compatibles.
    
______________________

### 3.4. Descripción de las herramientas de supervisión de Azure

1. ¿Cuál no es una de las categorías de recomendación de Azure Advisor?

    a) Confiabilidad
    
    __b) Capacity__
    
    c) Coste
    
    __*Anotacion:__  Las cinco categorías de recomendación de Azure Advisor son: Confiabilidad, Seguridad, Rendimiento, Excelencia operativa y Costo.

2. Recibirá una notificación por correo electrónico de que las máquinas virtuales (VM) de una región de Azure donde tiene máquinas virtuales implementadas están experimentando una interrupción. ¿Qué componente de Azure Service Health le indicará si la aplicación se ha visto afectada?

    a) Estado de Azure
    
    b) Estado del servicio
    
    __c) Estado de los recursos__
    
    __*Anotacion:__ Resource Health es una vista personalizada de los recursos reales de Azure. Proporciona información sobre el estado de los recursos en la nube individuales.


______________________

### 3.5 Coursera:  Introduction to Azure Core Concepts and Service

1. Tradewind Traders current on-premises datacenter has several hundred servers and available resources in the datacenter are currently very low. Management has asked you to research a solution that will allow for increased resources but will keep expenditure such as capital expenditure and operational expenditure at a minimum. What solution should you recommend?

    a) Create an additional Datacente

    b) A complete migration to the public cloud

    __c) Create a Hybrid cloud__

    d) Create a new Private cloud

    __*Anotacion:__ That’s correct. A hybrid cloud is a combination of a private cloud and a public cloud. With a hybrid cloud, you can continue to use the on-premises servers while adding new servers in the public cloud. Adding new servers in Azure minimizes the capital expenditure costs

2. Tradewind Traders is planning to migrate to Azure cloud services. The company currently operates multiple MySQL database solutions on-premises. Management has asked you to spend some time researching the MySQL features available in Azure specifically the ability to perform automatic backups and point in time restores. You have determined that these features are available for MySQL in Azure. For how many days are point-in-time restores supported for MySQL in Azure?

    a) 15

    b) 25

    __c) 35__

    d) 45

    __*Anotacion:__ Azure database for MySQL supports Automatic backups and point-in-time-restore for up to 35 days. Try going back and reviewing Introduction to Microsoft Azure Fundamentals.

3. Tradewind Traders is planning to migrate to Azure cloud services. Management has asked you to research some of the main features of cloud services. Based on your research, which of the following statements is correct?

    a) An Azure region can be found in every country in Europe and the Americas only.

    b) An Azure region contains one or more datacenters that are connected by using a high-latency network.

    c) An Azure region is found in each country where Microsoft has a subsidiary office.

    __d) An Azure region contains one or more datacenters that are connected by using a low-latency network.__

    __*Anotacion:__ An Azure region is a set of data centers deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. Try going back and reviewing Introduction to Microsoft Azure Fundamentals.

4. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services and will make use of Azure’s pay-as-you-go subscription. What type of expenditure is the pay-as-you-go subscription?

    a) Capital Expenditure (CapEx)

    __b) Operational Expenditure (OpEx)__

    __*Anotacion:__ One of the major changes that you will face when you move from an on-premises cloud to the public cloud is the switch from capital expenditure (buying hardware) to operating expenditure (paying for service as you use it). 

5. Tradewinds Traders is planning to migrate to Azure cloud services however management has questions concerning management and responsibilities once resources are migrated. You have identified three cloud service models. In which cloud service model is the cloud provider responsible for managing the virtual machines, the operating system, and networking resources that the cloud tenant deploys their applications into?
    
    a) SaaS (ESTA NO)

    b) IaaS

    c) Paas

6. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has decided to only make use of the Platform as a Service (PaaS) offerings in Azure. You have been asked to design a migration plan. As part of this design, you have included the creation of Azure App Services and Azure virtual machines that will run MySQL Databases. Does this design meet the requirements of the Organisation?

    a) Yes

    __b) No__

    __*Anotacion:__ Azure App Service is a PaaS (Platform as a Service) service. However, Azure virtual machines are an IaaS (Infrastructure as a Service) service. Therefore, this design does not meet the requirements.

7. Tradewind Traders is planning to migrate some of their custom in-house applications to Azure cloud services. These custom applications provide various services to the organization's customers and have specific prerequisites and services. Which cloud solution should you recommend that will satisfy the organization's requirements?

    __a) Infrastructure as a Service (laaS)__

    b) Software as a Service (SaaS)

    c) Platform as a Service (PaaS)

    __*Anotacion:__ Infrastructure as a service (IaaS) is an instant computing infrastructure, provisioned and managed over the internet. The IaaS service provider manages the infrastructure, while you purchase, install, configure, and manage your software.


8. Tradewind Traders is planning to migrate to Azure cloud services but before they do management has asked you to spend some time researching the Database solutions available in Azure with specific regard to schema-less data and always-on applications. Based on your research, which of the following cloud database solutions is most suitable to provide this feature?

    a) Azure Database for PostgreSQL 

    b) Azure Database for MySQL 

    c) Azure SQL Database

    __d) Cosmos DB__

    __*Anotacion:__ Azure Cosmos DB supports schema-less data, which lets you build highly responsive and Always-On applications to support constantly changing data. You can use this feature to store data that is updated and maintained by users around the world.


9. Tradewinds Traders is planning to migrate to Azure cloud services but before they do you have been asked to do some research on cloud deployment models. Based on your research which of the following deployment models will provide the ability to share data, applications, and resources on-premises and in the Cloud

    a) Private Cloud

    b) Public Cloud 

    __c) Hybrid Cloud__

    __*Anotacion:__ A hybrid cloud is a computing environment that combines a public cloud and a private cloud by allowing data and applications to be shared between them.

10. Tradewind Traders are in the process of migrating their resources to Azure cloud services. Currently, they have several VMs deployed to their Azure subscription. Management has asked you to research how their on-premises users will be able to securely access the resources that have been migrated to Azure. Based on that research, which of the following will you need to create to implement this solution? Select all options that apply.

    __A Virtual Network Gateway__

    __*Anotacion:__ To implement a solution that enables the client computers on your on-premises network to communicate to the Azure virtual machines, you need to configure a VPN (Virtual Private Network) to connect the on-premises network to the Azure virtual network. The Azure VPN device is known as a Virtual Network Gateway. 

    __A Gateway Subnet__

    __*Anotacion:__ The virtual network gateway needs to be located in a dedicated subnet in the Azure virtual network. This dedicated subnet is known as a gateway subnet. Try going back and reviewing Microsoft Azure Database, Analytics, and Compute Services.

    A Virtual network

    An Application Gateway (ESTA NO)

    A Load Balancer

11. Tradewinds Traders is planning to migrate to Azure cloud services. Management has asked you to research the main benefits of cloud services. Based on your research you have identified scalability as one of the main benefits. Scalability includes horizontal and vertical scaling. Which of the following is characteristic of vertical scaling?

    __a) Computing capacity can be increased by adding additional RAM or CPUs to a virtual machine.__

    b) Computing capacity can be increased by adding instances of a resource


12. Tradewind Traders is planning to migrate to Azure cloud services but before they do, management has asked you to spend some time researching the Database solutions available in Azure with specific regard to the use of multiple APIs. Based on your research, which of the following cloud database solutions is most appropriate to provide this feature?

    __a) Azure Cosmos DB__

    b) Azure Database for PostgreSQL 

    c) Azure SQL Database 

    d) Azure Database for MySQL 

13. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has decided to only make use of the Platform as a Service (PaaS) offerings in Azure. You have been asked to design a migration plan. As part of this design, you have included the creation of Azure App Services and Azure Storage accounts.Does this design meet the requirements of the Organization?

    a) Yes

    __b) No__

    __*Anotacion:__ Azure App Service is a PaaS (Platform as a Service) service. However, Azure Storage accounts are an IaaS (Infrastructure as a Service) service. Therefore, this design does not meet the requirements.

14. Tradewind Traders have recently migrated to Azure cloud services however the development team has expressed frustration at the amount of time it takes to create new virtual machines for test purposes as these machines are created and destroyed on a regular basis. Which of the following would you recommend to minimize the effort required to deploy and remove the virtual machines?

    a) Azure Availability Zones

    __b) Azure DevTest Labs__

    c) Azure Reserved Virtual Machine (VM) Instances 

    d) Azure virtual machine scale sets 

    __*Anotacion:__ DevTest Labs allows for the creation of labs consisting of pre-configured bases or Azure Resource Manager templates.

15. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research connectivity features between your on-premises environment and Cloud resources. In your research, you learn that Azure virtual networks enable you to link resources in your on-premises environment with your Azure subscription. In effect, you can create a network that spans both your local and cloud environments. There are three mechanisms for you to achieve this connectivity. Which of the following is not a valid mechanism?

    __a) Service endpoints__ 

    b) Site-to-site Virtual Private Networks 

    c) Azure ExpressRoute 

    d) Point-to-site Virtual Private Networks 

    __*Anotacion:__ You use service endpoints to connect to other Azure resource types, such as Azure SQL databases and storage accounts. This approach enables you to link multiple Azure resources to virtual networks, thereby improving security and providing optimal routing between resources.

16. Tradewind Traders is planning to migrate to Azure cloud services. The majority of their IT department is more familiar with Linux environments than Windows. Will these users be able to continue using Bash commands to create resources such as Virtual Machines once the organization has migrated? 

    __a) Yes__

    b) No

    __*Anotacion:__ With Azure Cloud Shell, you can create virtual machines using Bash or PowerShell.

17. Tradewinds Traders is planning to migrate to Azure cloud services. Management has asked you to research the main benefits of cloud services. Based on your research you have identified scalability as one of the main benefits. Scalability includes horizontal and vertical scaling. Which of the following is characteristic of horizontal scaling?

    a) Computing capacity can be increased by adding additional RAM or CPUs to a virtual machine.

    __b) Computing capacity can be increased by adding instances of a resource__

18. Tradewinds Traders is planning to migrate to Azure cloud services. Management has asked you to research the main benefits of cloud services. Your research has shown that cloud service providers operate on a consumption-based model. Which of the following are characteristics of a consumption-based model? Select all options that apply.

    Resources will be charged for, even when they are not in use.

    __You only pay for additional resources when they are needed.__

    __*Anotacion:__ In a consumption-based model, you only pay for additional resources when they are needed.

    __There is no need for companies to purchase and manage a costly infrastructure that they may or may not use to its full capacity.__

    __*Anotacion:__ In a consumption-based model, you don’t need to purchase and manage a costly infrastructure that they may or may not use to its full capacity.

    Consumers must pay the costs upfront.

19. Tradewind Traders is planning to migrate to Azure cloud services. The company currently operates multiple database solutions on-premises including PostgreSQL databases. Management has asked you to spend some time researching the high availability features and support levels available for Azure Database for PostgreSQL. Based on your research, what level of SLA is available for single-server deployments of PostgreSQL in Azure?

    a) 90.00%

    b) 99.00%

    c) 99.90%

    __d) 99.99%__

    __*Anotacion:__ Azure Database for PostgreSQL - Single Server deployment option delivers built-in high availability with no additional cost of 99.99% SLA.

20. Tradewind Traders is planning to migrate to Azure cloud services. The majority of their IT department is more familiar with Linux environments than Windows. Will these users be able to continue using Bash commands to create resources such as Virtual Machines once the organization has migrated? 

    __a) Yes__

    b) No

    __*Anotación:__ With Azure Cloud Shell, you can create virtual machines using Bash or PowerShell.

21. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main benefits of cloud services. Which of the following do you think are some of the benefits of cloud services? Select 2 options.

    Limited storage

    Dedicated hardware

    Unsecured connections

    __Self-service management__

    __*Anotacion:__ With the public cloud, you have self-service management. You are responsible for the deployment and configuration of the cloud resources such as virtual machines or websites. The underlying hardware that hosts the cloud resources is managed by the cloud provider.

    __Metered pricing__

    __*Anotacion:__ With the public cloud, you get pay-as-you-go pricing, you pay only for what you use, there are no CapEx costs.

22. Tradewind Traders is planning to migrate to Azure cloud services but before they do management has asked you to spend some time exploring Azure features and solutions. Which of the following should be your first step?

    __a) Create a subscription__

    b) Create a management group 
    
    c) Create a virtual network

    d) Create a resource group 

23. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main features of cloud storage. Which of the following offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block (SMB) protocol? 

    __a) Azure Files Storage__

    b) Azure Blob Storage

    c) Azure Storage Tiers

    d)Azure Disk Storage

    __*Anotacion:__ Azure Files offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block (SMB) protocol. Azure file shares can be mounted concurrently by cloud or on-premises deployments of Windows, Linux, and macOS. Diagnostic logs, metrics, and crash dumps are just three examples of data that can be written to a file share and processed or analyzed later. Try going back and reviewing Microsoft Azure Fundamental Concepts & Architectural Components.

24. Tradewind Traders is planning to migrate to Azure cloud services, and you have been asked to do some research on Infrastructure as a Service. Which of the following is an example of IaaS?

    a) Azure web app

    b) Azure logic app 
    
    c) Azure SQL database 

    __d) Azure virtual machine__

    __*Anotacion:__ An Azure virtual machine is an example of Infrastructure as a Service (IaaS).


25. Tradewind Traders is planning to migrate to Azure cloud services. Management has asked you to spend some time researching the big data and analytic solutions available in Azure. Based on your research, which of the following provides a fully managed, open-source analytics service for enterprises that makes it easier and more cost-effective to process massive amounts of data while running popular open-source frameworks?

    __a) Azure HDInsight__

    b) Azure Data Lake Analytics

    c) Azure Databricks 
 
    d) Azure Synapse Analytics 

    __*Anotacion:__ Azure HDInsight is a fully managed, open-source analytics service for enterprises. It is a cloud service that makes it easier, faster, and more cost-effective to process massive amounts of data. HDInsight allows you to run popular open-source frameworks and create cluster types.

26. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has decided to only make use of the Platform as a Service (PaaS) offerings in Azure. You have been asked to design a migration plan. As part of this design, you have included the creation of Azure App Services and Azure Storage accounts. Does this design meet the requirements of the Organization?

    a) Yes
    
    __b) No__

    __*Anotacion:__ Azure App Service is a PaaS (Platform as a Service) service. However, Azure Storage accounts are an IaaS (Infrastructure as a Service) service. Therefore, this design does not meet the requirements.

27. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has asked you to design a deployment plan that will guarantee services running on virtual machines will continue to operate in the event a single datacenter fails. As part of this design, you will deploy virtual machines to two or more scale sets. Does this design meet the requirements of the organization?

    a) Yes

    __b) No__

    __*Anotacion:__ Azure virtual machine scale sets let you create and manage a group of load-balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. Scale sets provide high availability to your applications and allow you to centrally manage, configure, and update many VMs. However, this question does not specify that the scale set will be configured across multiple datacenters so this solution does not meet the goal.

28. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main benefits of cloud services. Which of the following do you think are some of the benefits of cloud services? Select 2 options.

    Dedicated hardware

    Unsecured connections

    __Self-service management__

    __*Anotacion:__ With the public cloud, you have self-service management. You are responsible for the deployment and configuration of the cloud resources such as virtual machines or websites. The underlying hardware that hosts the cloud resources is managed by the cloud provider.

    __Metered pricing__

    __*Anotacion:__ With the public cloud, you get pay-as-you-go pricing, you pay only for what you use, there are no CapEx costs.

    Limited storage

29. Tradewind Traders is investigating a possible migration of their data and resources to Azure cloud services. Which of the following is true in respect of the Public Cloud?

    a) All public cloud resources can be freely accessed by every member of the public

    b) The public cloud is owned by the public, NOT a private corporation

    c) The public cloud is a crowd-sourcing solution that provides corporations with the ability to enhance the cloud

    __d) The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud__

    __*Anotacion:__ The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud. The hardware resources (servers, infrastructure, etc.) are managed by the cloud provider.

30. Tradewinds Traders is planning to migrate to Azure cloud services however management has questions concerning management and responsibilities once resources are migrated. You have identified three cloud service models. In which model does the cloud provider keep the hardware up to date but the operating system maintenance and network configuration are left to the cloud tenant? 

    a) PaaS

    b) IaaS

    c) SaaS (ESTA NO)

31. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main features of cloud storage. In your research, you discover that Azure storage offers different access tiers for blob and file storage. This allows you to store object data most cost-effectively. Based on your research, which is the most cost-effective tier to optimize storage for data that is infrequently accessed and stored for at least 30 days?

    __a) Cool storage tier__

    b) Archive storage tier

    c) Hot storage tier 

    __*Anotacion:__ Cool storage tier is optimized for data that is infrequently accessed and stored for at least 30 days.


## Semana 2
1. Tailwind Traders have recently migrated to Azure cloud services from a Linux-based on-premises environment. The existing administrators want to continue using scripting to configure and create resources. Which of the following tools would you recommend to administrators as the easiest environment for them to use based on their current knowledge?

    a) Azure Portal (ESTA NO)

    b) ARM Templates

    c) Azure CLI

    d) Azure PowerShell (ESA NO)

2. Tradewind Traders has recently migrated to Azure cloud services and management wants to start benefiting from DevOps. DevOps is a new approach that helps to align technical teams to work towards their common goal. Which of the following provides a suite of services that address each stage of the software development lifecycle (SDL)?

    __a) Azure DevOps Services__

    b) GitHub and GitHub Actions

    c)Azure DevTest Labs

    __*Anotacion:__ Azure DevOps is a suite of services that address every stage of the Software Development Lifecycle (SDL).

3. Tailwind Traders has recently moved to Azure cloud services. Management is concerned that they may be spending too much and are also concerned about how well their new environment meets security best practices. They would like to analyze their use of the cloud against industry best practices. Which monitoring tool would you recommend using for this?

    __a) Azure Advisor__

    b) Azure Monitor

    c) Azure Service Health

    __*Anotacion:__ Azure Advisor evaluates your Azure resources and makes recommendations to help you improve reliability, security, and performance, achieve operational excellence, and reduce costs.

4. Tradewind Traders has recently migrated to Azure cloud services and management wants their developers to start utilizing solutions such as using shared source code repositories and tools that enable developers to perform code reviews by adding comments and questions in a web-view of the source code before it is merged into the main codebase. Which of the following solutions would be most suitable?

    a) Azure DevTest Labs 

    b) Azure DevOps Services

    __c) GitHub and GitHub Actions__

5. Tailwind Traders has recently migrated to Azure cloud services. Management requires alerts to be generated that will send notifications to the IT department whenever Azure outages occur. Which Azure monitoring tool would you recommend for this?

    a) Azure Service Health

    __b) Azure Monitor__

    c) Azure Advisor

    __*Anotacion:__ Azure Monitor is a platform for collecting, analyzing, visualizing, and potentially acting based on the metric and logging data from your entire Azure and on-premises environment.

6. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. The company requires a solution that will allow for automation of the deployment of similar resources across multiple business units. Which of the following solutions should you recommend?

    a) Azure Resource Manager templates

    b) Azure API Management service (ESTA NO)

    c) Management groups

    d) Virtual machine scale sets

7. Tradewind Traders has recently migrated to Azure cloud services and management wants to start developing AI solutions. Management requires the development of an app that will include both a virtual agent that interfaces with humans through natural language and understands the content and meaning of images, video, audio. What two Azure Services do you think are most suitable for developing this app? Select all options that apply.

    __a) Azure Cognitive Services__

    __*Anotacion:__ Azure Cognitive Services provides pre-built machine learning models that enable applications to see, hear, speak, understand, and even begin to reason.

    b) Azure Machine Learning

    __c) Azure Bot Service__

    __*Anotacion:__ The Azure Bot Service and Bot Framework is a platform for creating virtual agents that understand and reply to questions just like a human.

8. Tradewind Traders has recently migrated to Azure cloud services. Their software development teams work on many different projects. The company wants to publish an open-source API that allows third-parties to integrate their inventories of new and used items. They also want to use the API to offer a wider variety of products directly from their e-commerce site. They will need a platform to share example code, collect feedback on the API, allow contributors to report issues, and build communities around feature requests. Which of the following would you recommend they implement?

    __a) GitHub and GitHub Actions__

    b) Azure DevOps Services

    c) Azure DevTest Labs

    __*Anotacion:__ With GitHub, your company can publish its code, accept community contributions to improve the code examples, accept feedback, and bug reports. Because this scenario involves open-source code, GitHub is a leading candidate.

9. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. The company is very proactive in IoT (Internet of Things) and they require a solution that will allow millions of IoT sensors to upload and store data in Azure. This solution must support very large quantities of data. Which of the following Azure resources should be deployed to support the planned solution? Select 2 options.

    a) Azure Queue storage

    __b) Azure Data Lake__

    __*Anotacion:__ There are two storage services IoT Hub can route messages to Azure Blob Storage and Azure Data Lake Storage Gen2. Azure Data Lake Storage accounts are hierarchical namespace-enabled storage accounts built on top of blob storage. Both use blobs for their storage.

    c) Azure Notification Hubs

    d) Azure File Storage

    __e) Azure IoT Hub__

    __*Anotacion:__ IoT Hub is a managed service, hosted in the cloud, that acts as a central message hub for bi-directional communication between your IoT application and the devices it manages. You can use Azure IoT Hub to build IoT solutions with reliable and secure communications between

10. Tradewind Traders is planning to migrate to Azure cloud services. Management has asked you to spend some time researching the big data and analytic solutions available in Azure. Based on your research, which of the following provides a fully managed, open-source analytics service for enterprises that makes it easier and more cost-effective to process massive amounts of data while running popular open-source frameworks?

    a) Azure Synapse Analytics

    __b) Azure HDInsight__

    c) Azure Data Lake Analytics

    d) Azure Databricks

    __*Anotacion:__ Azure HDInsight is a fully managed, open-source analytics service for enterprises. It is a cloud service that makes it easier, faster, and more cost-effective to process massive amounts of data. HDInsight allows you to run popular open-source frameworks and create cluster types.

11. Tradewind Traders has recently migrated some of their data and resources to Azure cloud services, Management is concerned about external attacks against their websites, they also want you to generate reports that will provide information on attempted attacks. Which of the following should you include when implementing this solution?

    a) Azure Firewall
    
    __b) DDoS protection__

    c) Network security groups (NSG) 

    d) Azure Information Protection

    __*Anotacion:__ DDoS is a type of attack that tries to exhaust application resources. Azure has two DDoS service offerings that protect from network attacks: DDoS Protection Basic and DDoS Protection Standard. DDoS Basic protection is integrated into the Azure platform by default and at no extra cost. You have the option of paying for DDoS Standard. It has several advantages over the basic service, including logging, alerting, and telemetry. 

12. Tradewind Traders is planning to migrate to Azure cloud services and management wants to start developing AI solutions. You have been asked to research what AI features are available with Azure with specific emphasis on using existing data to train and test a model and then apply that model to new data to forecast future behaviors, outcomes, and trends. Which of the following terms best describe this?

    a) Deep Learning
    
    __b) Machine Learning__

    __*Anotacion:__ Machine learning is a data science technique that uses existing data to train and test a model, then apply that model to new data to forecast future behaviors, outcomes, and trends.

13. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management now plans on deploying additional virtual machines, however, they are concerned about locking down the ports on these machines to prevent access from devices on the internet. Which of the following can be used to help protect access to the ports on these machines?

    a) Azure Active Directory (Azure AD) roles

    b) Azure Active Directory groups 

    __c) Network security groups (NSG)__

    d) Azure key vault 

    __*Anotacion:__ A network security group works like a firewall. You can attach a network security group to a virtual network and/or individual subnets within the virtual network. A network security group contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources. Try going back and reviewing General Security and Network Security in Microsoft Azure.

14. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management requires that users can create virtual machines by using their Android tablets. You recommend that they use the PowerShell feature in Azure Cloud Shell. Will this recommendation work?

    __a) Yes__

    b) No

15. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management wants to allow HTTP access from the internet to a specific virtual machine. You configure a Network Security Group. Does this meet the goal?

    __a) Yes__

    b) No

    __*Anotacion:__ A network security group works like a firewall. You can attach a network security group to a virtual network and/or individual subnets within the virtual network. In this question, we need to add a rule to the network security group to allow the connection to the virtual machine on port 80 (HTTP).

16. Tradewind Traders has recently migrated to Azure cloud services. Their software development teams work on many different projects and they are required to provide project sponsors and managers with reports, progress tracking, bug reports, etc. Management now wants to ensure that individuals will only have access to information they need to do their work. Which of the following in your opinion would be the most suitable solution to meet this requirement?

    a) Azure DevTest Labs

    __b) Azure DevOps Services__

    c) GitHub and GitHub Actions

    __*Anotacion:__ Azure DevOps has a much more granular set of permissions that allow organizations to refine who can perform most operations across the entire toolset. Also, Azure DevOps is highly customizable, allowing an administrator to add custom fields to capture metadata and other information alongside each work item. By contrast, GitHub Issues uses tags as its primary means of helping a team categorize issues.

17. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. The company has developed an Azure web app. They require that the settings for the app be configurable if needed from an iPhone. What are two Azure management tools that you can use from the iPhone? Select all options that apply.

    __a) Azure portal__

    __*Anotacion:__ The Azure portal is a web-based portal for managing Azure. Being web-based, you can use the Azure portal on an iPhone.

    b) Azure CLI (Command Line Interface)

    __c) Azure Mobile App__

    __*Anotacion:__ With Azure Mobile App you can monitor the health and status of your Azure resources. Quickly diagnose and fix issues. Run commands to manage your Azure resources. Data is secure and encrypted. Try going back and reviewing Microsoft AI Services and Solutions.

    d) Windows PowerShell

18. Tradewind Traders has recently migrated to Azure cloud services. Management requires you to research the available monitoring solutions available to them within Azure. A specific requirement is the ability to be able to evaluate the Azure resources and make recommendations that could improve reliability, security, and performance. Which of the following would you recommend to do this?

    a) Azure Monitor
 
    b) Azure Service Health

    __c) Azure Advisor__

19. Tradewind Traders has recently migrated some of their data and resources to Azure cloud services, you are familiarising yourself with the various mechanisms to create resources in Azure. You have been asked to create some resources in Azure using PowerShell. You currently have a Windows 10 computer that has the Azure PowerShell module installed. Does this configuration support the creation of resources in Azure?

    __a) Yes__

    b) No

    __*Anotacion:__ A PowerShell script is a file that contains PowerShell cmdlets and code and needs to be run in PowerShell. The computer is running a compatible OS and the information states that it has the Azure PowerShell module installed. Therefore, this configuration will support the creation of resources in Azure.

20. Tradewind Traders is planning to migrate to Azure cloud services and management wants to start developing AI solutions. You have been asked to research what AI features are available with Azure with specific emphasis on Azure Cognitive Services. Which of the following features are offered by Cognitive Services? Select all options that apply.

    __a) The ability to add recognition and identification capabilities when analyzing pictures, videos, and other visual content.__

    __*Anotacion:__ Azure Cognitive Services includes vision services that allow recognition and identification capabilities when analyzing pictures, videos, and other visual content. Try going back and reviewing Microsoft Azure Serverless Technology and IoT.

    __b) The ability to convert speech into text and text into natural-sounding speech. Translate from one language to another and enable speaker verification and recognition.__

    __*Anotacion:__ Azure Cognitive Services includes speech services that can convert speech into text and text into natural-sounding speech. It can translate one language into another and enable speaker verification and recognition.

    c) The ability to create virtual agents that understand and reply to questions just like a human.

    d) The ability to train and evaluate predictive models using tools and programming languages familiar to data scientists.

21. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management plans to automate the deployment of new servers to Azure but is concerned that this process may expose administrative credentials during the deployment. Which of the following can be used to encrypt the credentials that will be used in the automated process?

    a) Azure Information Protection

    b) Azure Security Center

    c) Azure Multi-Factor Authentication (MFA) (ESTA NO)
 
    d) Azure Key Vault

22. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks in place. Management has asked you to research the ability to filter traffic across subscriptions and virtual networks. Based on your research, which of the following will assist with this filtering?

    a) Application Security Group 
 
    b) Azure DDoS Protection 

    __c) Azure Firewall__

    d) Network Security Group (NSG)

    __*Anotacion:__ You can restrict traffic to multiple virtual networks in multiple subscriptions with a single Azure firewall. Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources.

23. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks in place. Management has asked you to research the ability to securely store certificates in Azure. Which of the following services should you configure to enable this feature?

    a) Azure Security Center

    b) Azure Information Protection (ESTA NO)

    c) Azure Key Vault

    d) Azure Storage account (ESTA NO)

24. Tailwind Traders has recently migrated to Azure cloud services. The development departments are currently working on a new IoT application that will be used to capture and transmit personal data back to a cloud service. Management is concerned that this personal data may be exposed in transit. Which of the following services can the company implement to ensure the highest level of security?

    a) IoT Hub

    b) IoT Central (ESTA NO)

    c) Azure Sphere

25. Tradewind Traders is planning to migrate to Azure cloud services and management wants to start developing AI solutions. You have been asked to research what AI features are available in Azure. Based on your research, what service can you use to build a virtual agent that can understand and reply to questions just like a human?

    a) Azure Bot Service

    b) Azure Cognitive Services

    c) Azure Machine Learning (ESTA NO)

26. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management is planning on implementing an Apache Spark engine for large-scale data processing. Which of the following will provide a compatible analytics platform the Apache Spark engine?
    
    a) Azure DevOps

    b) Azure Data Factory (ESTA NO)

    c) Azure HDInsight

    d) Azure Databricks.

27. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. As part of their future planning, management has requested information on cloud services that will provide a set of version control tools to manage the developer’s code. Which of the following will satisfy this requirement?

    a) Azure Cosmos DB (ESTA NO)

    b) Azure DevTest Labs

    c) Azure DevOps Repos

    d) Azure Storage

## Semana 3
1. Tradewind Traders has recently migrated to Azure cloud services. The company has several departments and management has decided that the departmental administrators will be responsible for managing the resources related to their department. Which of the following will allow for the segmentation of the departments? Select all options that apply.

    a) Multiple Regions

    __b) Multiple resource groups__

    __*Anotacion:__ A resource group is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group.

    __c) Multiple subscriptions__

    __*Anotacion:__ An Azure subscription is a container for Azure resources. It is also a boundary for permissions to resources and billing. You are charged monthly for all resources in a subscription. A single Azure tenant (Azure Active Directory) can contain multiple Azure subscriptions.

    d) Multiple Azure Active Directory (Azure AD) directories

2. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. As part of this migration, you have been asked to research the purpose of Azure Advisor. Based on this research, which of the following can be performed by using Azure Advisor?

    a) Estimate the costs of an Azure solution.

    b) Integrate Active Directory and Azure Active Directory (Azure AD). (ESTA NO)

    c) Evaluate which on-premises resources can be migrated to Azure. (ESTA NO)

    d) Confirm that Azure subscription security follows best practices.

3. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has asked you to research the differences between Authorisation and Authentication in Azure. Based on your research, which of the following is the process of establishing the identity of a person or service that wants to access a resource known as?

    __a) Authentication__

    b) Authorisation

4. Tradewind Traders has recently migrated to Azure cloud services. Management has asked you to research Azure Blueprints which are composed of artifacts. Which of the following resources as artifacts are currently supported by Azure Blueprints? Select all options that apply.

    a) Management Groups

    __b) ARM Templates__

    __*Anotacion:__ Azure Blueprints currently supports Resource Groups, ARM template, Policy Assignment, and Role Assignment as artifacts.

    __c) Policy Assignment__

    __*Anotacion:__ Azure Blueprints currently supports Resource Groups, ARM template, Policy Assignment, and Role Assignment as artifacts.

    __d) Role Assignment__

    __*Anotacion:__ Azure Blueprints currently supports Resource Groups, ARM template, Policy Assignment, and Role Assignment as artifacts.

5. Tradewind Traders has recently migrated to Azure cloud services. Management wants clarification on their legal agreement between themselves and Microsoft that details the obligations by both parties concerning the processing and security of customer data and personal data. Which of the following should you refer management to? 

    a) Microsoft Privacy Statement

    __b) Online Services Terms__

    __*Anotacion:__ The Online Services Terms (OST) is a legal agreement between Microsoft and the customer that details the obligations by both parties concerning the processing and security of customer data and personal data. The OST applies specifically to Microsoft's online services that you license through a subscription including Azure, Dynamics 365, Office 365, and Bing Maps.

6. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has multiple offices around the world. Management wants to be able to generate multiple billing reports from the Azure Portal that will contain the resource utilization from each office. Which feature should you use before you generate the reports?

    a) Templates

    __b) Tags__

    c) Locks

    d) Policies

    __*Anotacion:__ You can use resource tags to label Azure resources. Tags are metadata elements attached to resources made up of key/value pairs. strings. When all Azure resources are tagged, you can generate reports to list all resources based on the value of the tag.

7. True or False? Azure China is operated by 21Vianet and is a physically separated instance of cloud services located in China.

    __a) True__

    b) False

    __*Anotacion:__ Azure China is operated by 21Vianet is a physically separated instance of cloud services located in China. It is independently operated and transacted by Shanghai Blue Cloud Technology Co., Ltd. (“21Vianet”), a wholly-owned subsidiary of Beijing 21Vianet Broadband Data Center Co., Ltd.

8. Tradewind Traders has recently migrated to Azure cloud services. Management wants their users to have access to a unified console that provides an alternative to command-line tools where you can build, manage, and monitor everything from simple web apps to complex cloud deployments. Which tool would you recommend they use?

    a) Azure Advisor

    b) Azure Portal

    c) Microsoft Trust Center (ESTA NO)

    d) Azure Monitor

9. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. As part of this migration, the company wants to create a support plan that will provide its users with access to Azure support engineers by phone and email. You have been asked to research the available support plans and recommend one that will provide this service. You recommend the Professional Direct support plan. Does this meet the company’s requirements?

    __a) Yes__

    b) No

    __*Anotacion:__ The Basic support plan does not have any technical support for engineers. The Developer support plan has only technical support for engineers via email. The Standard, Professional Direct, and Premier support plans have technical support for engineers via email and phone. The Standard support plan would be the cheapest plan to implement however this was not stated as a requirement in the question

10. Tradewind Traders has recently migrated to Azure cloud services. The company’s development team creates virtual machines for testing regularly. These test machines are only used during certain times. In your opinion what is the most efficient way to save costs on virtual machines when they are not in use?

    a) Use virtual machines that are only chargeable when accessed remotely. Try going back and Managing Costs and SLA Service Cycles.

    __b) Deallocate the virtual machines when they are not in use.__

    c) Delete the virtual machines when they are not in use because once they are deleted, they will not incur any charges.

    __*Anotation:__ When you deallocate virtual machines, the associated hard disks and data are kept in Azure. But you don't pay for CPU or network consumption, which can help save costs.

11. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. You have been asked to determine which support plan will provide best practice information, health status and notifications, and 24/7 access to billing information at the lowest possible cost. Which support plan should you choose?

    a) Basic

    b) Premier (ESTA NO)

    c) Developer (ESTA NO)

    d) Standard support plan

12. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. You have been asked to identify the lowest-cost support plan that allows 24x7 access to support engineers by phone. Which of the following support options allow this at a low cost?

    a) Azure Basic support plan 

    b) Azure Developer support plan

    __c) Azure Standard support plan__

    d) Azure Professional Direct support plan

    __*Anotation:__ The Basic support plan is free so is, therefore, the cheapest. The Developer support plan is the cheapest paid-for support plan. The order of support plans in terms of cost ranging from the cheapest to most expensive is Basic, Developer, Standard, Professional Direct, Premier. However, 24/7 access to technical support by email and phone is only available for Standard, Professional Direct, Premier plans.

13. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. The company requires their users to be able to open new support requests and you have been asked to determine which support plan will provide this feature. Which of the following statements is correct?

    a) Premier and Professional Direct only (ESTA NO)

    b) Premier, Professional Direct, and Standard only

    c) Premier, Professional Direct, Standard, Developer, and Basic (ESTA NO)

    d) Premier, Professional Direct, Standard, and Developer only

14. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. As part of this migration, you have been asked to research the Modern Lifecycle Policy for Azure services. Based on your research Which of the following statements do you think most accurately defines Modern Lifecycle Policy for Azure services?

    a) After a service is made generally available, Microsoft provides support for the service for a minimum of four years.

    __b) Microsoft provides a minimum of 12 months’ notice before ending support for a service.__

    c) Microsoft provides mainstream support for a service for five years.

    d) When a service is retired, you can purchase extended support for the service for up to five years.

    __*Anotacion:__ For products governed by the Modern Lifecycle Policy, Microsoft will provide a minimum of 12 months' notification before ending support if no successor product or service is offered, excluding free services or preview releases. 

15. Tradewind Traders has recently migrated to Azure cloud services and management is in the process of setting up an SLA with Microsoft. They want clarification on the time duration that the service is unavailable based on the percentages listed. How much cumulative downtime per year will an SLA percentage of 99.95 give?

    a) 3.65 days

    __b) 4.38 hours__

    c) 52.56 minutes 

    d) 8.76 hours

    __*Anotacion:__ An SLA percentage of 99.95 will give an annual cumulative downtime of 4.38 hours.

16. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has asked you to research multi-factor authentication. A code that's sent to a mobile phone is an example of which type of multi-factor authentication?

    a) something you are

    b) Something you know

    __c) Something you have__

    __*Anotacion:__ Something you have might be a code that's sent to your mobile phone.

17. Tradewind Traders has recently migrated to Azure cloud services. Management wants access to in-depth information about security, privacy, compliance offerings, policies, features, and practices across Microsoft cloud products. Which tool should you recommend for them to use?

    a) Azure Advisor

    __b) Microsoft Trust Center__

    c) Azure Monitor

    d) Azure Portal

    __*Anotacion:__The Trust Center provides in-depth information about security, privacy, compliance offerings, policies, features, and practices across Microsoft cloud products including links to the security, privacy, and compliance blogs.
