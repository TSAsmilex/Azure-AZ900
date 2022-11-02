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
______________________
______________________

# Curso coursera: Introduction to Microsoft Azure Cloud Services

## Semana 1

### 1.2. Introduction to Microsoft Azure fundamentals

1. You have been given the task to determine what solutions or services best suit your business needs. You need to provision end-to-end solutions quickly and reliably, hosted in your own Azure environment. Which Azure solution would best suit your business goal?

    a) Azure Portal

    __b) Azure Marketplace__

    c) Azure Virtual Machines

    __Anotación:__ In the Azure Marketplace you can find, try, buy, and deploy the software and services you need to build new solutions and manage your cloud infrastructure. You can provision end-to-end solutions quickly and reliably, hosted in your own Azure environment.

2. Cloud computing is the delivery of computing services using a pay-as-you-go pricing model. Which of the following statements are true of the pay-as-you-go pricing model? *Select all options that apply.*.   (__0.75 / 1 punto__, falta alguna opcion mas)

    a) You must pay a fixed fee in advance for all Cloud services.

    __b) You rent compute power and storage from someone else's datacenter.__ 

    c) You rent physical hardware such as compute power and storage and maintain them within your own datacenter. (Esta NO)

    __d) You can immediately stop paying for resources that are no longer needed.__

    __Anotación:__ (__d__)You can treat cloud resources like you would resources in your own datacenter. When you are finished using them, you give them back. You are only billed for what you use. (__b__) You don't have to worry about if you have enough resources, you just rent from someone else. 

3. Cloud Computing provides several benefits over a physical environment. Which of the following are benefits of cloud computing? *Select all options that apply.* (__1 / 1 punto__)

    __a) Elasticity__

    __b) High availability__

    __c) Agility__

    d) Full control 

    __Anotación:__ (__a__) Cloud-based applications can be configured to take advantage of autoscaling, so your applications will always have the resources they need.(__b__) Depending on the service-level agreement (SLA) that you choose, your cloud-based applications can provide a continuous user experience with no apparent downtime even when things go wrong. (__c__) Cloud-based resources can be deployed and configured quickly as your application requirements change.

4. Which of the following options is not defined as a type of cloud deployment model? (__1 / 1 punto__)

    a) Hybrid cloud

    b) Private cloud

    c) Public cloud

    __d) Distributed cloud__

    __Anotación:__ A distributed cloud is not a valid type of cloud computing. Distributed computing divides a single task among multiple computers that are connected via a network to achieve the task faster.

5. True or False? The Azure Portal updates continuously and requires no downtime for maintenance activities. (__1 / 1 punto__)

    __a) True__

    b) False

    __Anotación:__ The Azure portal updates continuously and requires no downtime for maintenance activities. This configuration makes the Azure portal resilient to individual datacenter failures and avoids network slowdowns by being close to users.

6. True or False? Serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure. (__1 / 1 punto__)

    __a) True__

    b) False

    __Anotación:__ Serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure. With serverless applications, the cloud service provider automatically provisions, scales, and manages the infrastructure required to run the code.

7. True or False? The Azure Marketplace is a service on Azure specific to Microsoft Products. (__1 / 1 punto__)

    a) True

    __b) False__

    __Anotación:__ The Azure Marketplace is a service on Azure that helps connect end-users with Microsoft partners, independent software vendors (ISVs), and start-ups that are offering their solutions and services, which are optimized to run on Azure.

8. Azure provides four main types of storage services. One of these services Azure Blob storage provides for which of the following. (__1 / 1 punto__)

    __a) Storage service for very large objects such as video files or bitmaps.__

    b) A NoSQL store that hosts unstructured data independent of any schema

    c) A data store for queuing and reliably delivering messages between applications.

    d) File shares that you can access and manage like a file server.

    __Anotación:__ Azure Blob storage provides storage service for very large objects such as video files or bitmaps.

9. Which tool can you use to assist in creating custom Dashboards that will help in graphically organizing your resources in Azure? (__1 / 1 punto__)

    a) Azure Marketplace

    __b) Azure Portal__

    __Anotación:__ With the Azure portal, you can build, manage, and monitor everything from simple web apps to complex cloud deployments. Create custom dashboards for an organized view of resources and configure accessibility options for an optimal experience.

10. True or False? To create and use Azure services, you need an Azure subscription. (__1 / 1 punto__)

    __a) True__

    b) False

    __Anotación:__ To create and use Azure services, you need an Azure subscription. 

11. Cloud computing provides computing services over the internet using a pay-as-you-go pricing model. With this model you typically only pay for the cloud services you use. Which of the following are benefits of the pay-as-you-go pricing model?*Select all that apply.* (__1 / 1 punto__, falta alguna opcion mas)

    __a) Lower operating costs.__

    __b) You can run your infrastructure more efficiently.__ 

    __c) You can scale as your business needs to change.__

    __Anotación:__ (__a__)That’s partially correct. One feature of Cloud services is that you typically pay only for cloud services you use, which helps you lower your operating costs. (__b__)That’s partially correct. One feature of Cloud services is that you can run your infrastructure more efficiently, and scale as your business needs change. (__c__)That’s partially correct. One feature of Cloud services is that you can scale as your business needs change. 

12. In your opinion which of the following statements is true? (__1 / 1 punto__)

    a) You need to create an Azure subscription and an account will be created for you. Once you've created an Azure subscription you are free to create additional Accounts.

    __b) You need to create an Azure account, and a subscription will be created for you. Once you've created an Azure account, you are free to create additional subscriptions.__

    __Anotación:__ Once you create an Azure account, a subscription will be created for you and you are then free to create additional subscriptions.

11. Microsoft offers an Azure Free Account to allow customers to test out various features of their cloud services. To sign up for a free account you are required to provide which of the following? *Select all options that apply.* (__1 / 1 punto__)

    a) A non-refundable deposit

    __b) Phone number__

    __c) A valid credit card__

    __d) GitHub or Microsoft account username__

    __Anotación:__ (__b__)One of the requirements to sign up for a free Azure account is a telephone number. (__c__)One of the requirements to sign up for a free Azure account is a valid Credit Card. (__d__)One of the requirements to sign up for a free Azure account is either a GitHub or Microsoft account username.

11. Cloud computing provides computing services over the internet using a pay-as-you-go pricing model. Typically, you only pay for the cloud services you use. This pricing model can benefit a company in which of the following ways? *Select all options that apply.* (__1 / 1 punto__)

    __a) Lower their operating costs__

    __b) Dynamically scale as your business requirement change__

    c) Provides a guaranteed annual fixed cost

    __d) Operate a more efficient infrastructure__

    __Anotación:__ (__a__)In cloud computing you typically pay only for cloud services you use, which helps you lower your operating costs. (__b__)In cloud computing you typically pay only for cloud services you use, which can help you scale as your business needs change. (__d__)In cloud computing you typically pay only for cloud services you use, which can help you run your infrastructure more efficiently.

______________________
______________________
______________________

# Curso coursera: Preparing for the AZ-900 Microsoft Azure Fundamentals Exam

### 1. Introduction to Azure Core Concepts and Service

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

    __*Anotacion:__ With vertical scaling, computing capacity can be increased by adding additional RAM or CPUs to a virtual machine. 

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

    __*Anotacion:__ With horizontal scaling, computing capacity can be increased by adding instances of a resource. 

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

    __*Anotacion:__ The first thing you create in Azure is a subscription. A subscription is an agreement with Microsoft to use one or more Microsoft cloud platforms or services, for which charges accrue. You get billed per subscription

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

32. Tradewind Traders has recently migrated to Azure cloud services and management wants to start benefiting from DevOps. DevOps is a new approach that helps to align technical teams to work towards their common goal. Which of the following provides a suite of services that address each stage of the software development lifecycle (SDL)?

    __a) Azure DevOps Services__

    b) Azure DevTest Labs

    c) GitHub and GitHub Actions
    
    __*Anotacion:__ Azure DevOps is a suite of services that address every stage of the Software Development Lifecycle (SDL).


### 2. Semana 2
1. Tailwind Traders have recently migrated to Azure cloud services from a Linux-based on-premises environment. The existing administrators want to continue using scripting to configure and create resources. Which of the following tools would you recommend to administrators as the easiest environment for them to use based on their current knowledge?

    a) Azure Portal 

    b) ARM Templates

    __c) Azure CLI__

    d) Azure PowerShell 

    __*Anotacion:__ Azure CLI is more beneficial to those with a Linux administration and scripting background who wish to perform one-off management or administrative actions.

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

    __*Anotacion:__ GitHub is one of the most popular code repositories for open-source software. GitHub provides related services for coordinating work, reporting, and discussing issues, providing documentation, and more.

5. Tailwind Traders has recently migrated to Azure cloud services. Management requires alerts to be generated that will send notifications to the IT department whenever Azure outages occur. Which Azure monitoring tool would you recommend for this?

    a) Azure Service Health

    __b) Azure Monitor__

    c) Azure Advisor

    __*Anotacion:__ Azure Monitor is a platform for collecting, analyzing, visualizing, and potentially acting based on the metric and logging data from your entire Azure and on-premises environment.

6. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. The company requires a solution that will allow for automation of the deployment of similar resources across multiple business units. Which of the following solutions should you recommend?

    __a) Azure Resource Manager templates__

    b) Azure API Management service 

    c) Management groups 

    d) Virtual machine scale sets

    __*Anotacion:__ You can use Azure Resource Manager templates to automate the creation of the Azure resources. Deploying resources through templates is known as Infrastructure as code.

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

    __*Anotacion:__ Azure Cloud Shell is a browser-based shell allowing for the management and development of Azure resources. The Cloud Shell offers a browser-accessible, pre-configured shell experience for managing Azure resources. Being browser-based, Azure Cloud Shell can be run on a browser from a tablet that runs the Android operating system.

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

    __*Anotacion:__ Azure Advisor evaluates your Azure resources and makes recommendations to help you improve reliability, security, and performance, achieve operational excellence, and reduce costs.

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

    c) Azure Multi-Factor Authentication (MFA) 
 
    __d) Azure Key Vault__

    __*Anotacion:__ Azure Key Vault is a cloud service that safeguards encryption keys and secrets like certificates, connection strings, and passwords.

22. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks in place. Management has asked you to research the ability to filter traffic across subscriptions and virtual networks. Based on your research, which of the following will assist with this filtering?

    a) Application Security Group 
 
    b) Azure DDoS Protection 

    __c) Azure Firewall__

    d) Network Security Group (NSG)

    __*Anotacion:__ You can restrict traffic to multiple virtual networks in multiple subscriptions with a single Azure firewall. Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources.

23. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks in place. Management has asked you to research the ability to securely store certificates in Azure. Which of the following services should you configure to enable this feature?

    a) Azure Security Center

    b) Azure Information Protection 

    __c) Azure Key Vault__

    d) Azure Storage account 

    __*Anotacion:__ Azure Key Vault is a secure store for storing various types of sensitive information including passwords and certificates. Azure Key Vault can be used to Securely store and tightly control access to tokens, passwords, certificates, API keys, and other secrets.

24. Tailwind Traders has recently migrated to Azure cloud services. The development departments are currently working on a new IoT application that will be used to capture and transmit personal data back to a cloud service. Management is concerned that this personal data may be exposed in transit. Which of the following services can the company implement to ensure the highest level of security?

    a) IoT Hub

    b) IoT Central 

    __c) Azure Sphere__

    __*Anotacion:__ Azure Sphere creates an end-to-end highly secure IoT solution for customers that encompasses everything from the hardware and operating system on the device to the secure method of sending messages from the device to the message hub.

25. Tradewind Traders is planning to migrate to Azure cloud services and management wants to start developing AI solutions. You have been asked to research what AI features are available in Azure. Based on your research, what service can you use to build a virtual agent that can understand and reply to questions just like a human?

    __a) Azure Bot Service__

    b) Azure Cognitive Services

    c) Azure Machine Learning 

    __*Anotacion:__ The Azure Bot Service and Bot Framework is a platform for creating virtual agents that understand and reply to questions just like a human.

26. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management is planning on implementing an Apache Spark engine for large-scale data processing. Which of the following will provide a compatible analytics platform the Apache Spark engine?
    
    a) Azure DevOps 

    b) Azure Data Factory 

    c) Azure HDInsight

    __d) Azure Databricks.__

    __*Anotacion:__ Azure Databricks is an Apache Spark-based analytics platform. The platform consists of several components including MLlib which is a Machine Learning library consisting of common learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, as well as underlying optimization primitives.

27. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. As part of their future planning, management has requested information on cloud services that will provide a set of version control tools to manage the developer’s code. Which of the following will satisfy this requirement?

    a) Azure Cosmos DB 

    b) Azure DevTest Labs

    __c) Azure DevOps Repos__

    d) Azure Storage 

28. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management plans on deploying several web servers and database servers to Azure but want to limit the types of connections that will be available between the web servers and the databases servers. Which of the following will assist in controlling the connection types?

    __a) network security groups (NSGs)__

    b) Azure Service Bus

    c) Local network gateway 

    d) Route filter

    __*Anotacion:__ A network security group works like a firewall. You can attach a network security group to a virtual network and/or individual subnets within the virtual network. You can filter network traffic to and from Azure resources in an Azure virtual network with a network security group. 

29. Tradewind Traders has recently migrated some of their data and resources to Azure cloud services, Management has asked you to research what service is most appropriate to provide for the collection of events from multiple resources into a centralized repository. Based on your research which of the following solutions should you recommend?

    __a) Azure Event Hubs__

    b) Azure Analysis Services 

    c) Azure Stream Analytics

    d) Azure Monitor 

    __*Anotacion:__ Azure Event Hubs is a big data streaming platform and event ingestion service. It can receive and process millions of events per second. Data sent to an event hub can be transformed and stored by using any real-time analytics provider or batching/storage adapters.

30. Tailwind Traders has recently migrated to Azure cloud services. The development departments are currently working on new IoT applications and require a managed service hosted in the cloud that acts as a central message point for bi-directional communication between their IoT application and the devices it manages. Which of the following will provide this solution?
    
    __a) Azure IoT Hub__

    b) Azure IoT Central

    c) Azure Sphere

    __*Anotacion:__ You can use Azure IoT Hub to build IoT solutions with reliable and secure communications between millions of IoT devices and a cloud-hosted solution backend. 

## Semana 3
1. Tradewind Traders has recently migrated to Azure cloud services. The company has several departments and management has decided that the departmental administrators will be responsible for managing the resources related to their department. Which of the following will allow for the segmentation of the departments? Select all options that apply.

    a) Multiple Regions

    __b) Multiple resource groups__

    __*Anotacion:__ A resource group is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group.

    __c) Multiple subscriptions__

    __*Anotacion:__ An Azure subscription is a container for Azure resources. It is also a boundary for permissions to resources and billing. You are charged monthly for all resources in a subscription. A single Azure tenant (Azure Active Directory) can contain multiple Azure subscriptions.

    d) Multiple Azure Active Directory (Azure AD) directories

2. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. As part of this migration, you have been asked to research the purpose of Azure Advisor. Based on this research, which of the following can be performed by using Azure Advisor?

    __a) Estimate the costs of an Azure solution.__

    b) Integrate Active Directory and Azure Active Directory (Azure AD). 

    c) Evaluate which on-premises resources can be migrated to Azure. 

    d) Confirm that Azure subscription security follows best practices.

    __*Anotacion:__ Azure Advisor analyses your configurations and usage telemetry and offers personalized, actionable recommendations to help you optimize your Azure resources for reliability, security, operational excellence, performance, and cost.

3. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has asked you to research the differences between Authorisation and Authentication in Azure. Based on your research, which of the following is the process of establishing the identity of a person or service that wants to access a resource known as?

    __a) Authentication__

    b) Authorisation

    __*Anotacion:__ Authentication is the process of establishing the identity of a person or service that wants to access a resource. It involves the act of challenging a party for legitimate credentials and provides the basis for creating a security principle for identity and access control. It establishes whether the user is who they say they are.

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

    __b) Azure Portal__

    c) Microsoft Trust Center 

    d) Azure Monitor

    __*Anotacion:__ The Azure portal is a web-based, unified console that provides an alternative to command-line tools. You can build, manage, and monitor everything from simple web apps to complex cloud deployments.

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

    __a) Basic__

    b) Premier 

    c) Developer 

    d) Standard support plan

    __*Anotacion:__ A basic support plan provides 24x7 access to billing and subscription support, online self-help, documentation, whitepapers, and supports forums. Access to the full set of Azure Advisor recommendations and access to personalized Service Health Dashboard & Health APIs.

12. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. You have been asked to identify the lowest-cost support plan that allows 24x7 access to support engineers by phone. Which of the following support options allow this at a low cost?

    a) Azure Basic support plan 

    b) Azure Developer support plan

    __c) Azure Standard support plan__

    d) Azure Professional Direct support plan

    __*Anotation:__ The Basic support plan is free so is, therefore, the cheapest. The Developer support plan is the cheapest paid-for support plan. The order of support plans in terms of cost ranging from the cheapest to most expensive is Basic, Developer, Standard, Professional Direct, Premier. However, 24/7 access to technical support by email and phone is only available for Standard, Professional Direct, Premier plans.

13. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. The company requires their users to be able to open new support requests and you have been asked to determine which support plan will provide this feature. Which of the following statements is correct?

    a) Premier and Professional Direct only 

    b) Premier, Professional Direct, and Standard only

    c) Premier, Professional Direct, Standard, Developer, and Basic 

    __d) Premier, Professional Direct, Standard, and Developer only__

    __*Anotacion:__ You can open support cases in the following plans: Premier, Professional Direct, Standard, and Developer only. You cannot open support cases in the Basic support plan. Try going back and Managing Costs and SLA Service Cycles.

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

    __*Anotacion:__ The Trust Center provides in-depth information about security, privacy, compliance offerings, policies, features, and practices across Microsoft cloud products including links to the security, privacy, and compliance blogs.

18. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has asked you to research Azure AD. What types of resources can Azure AD help secure?
    
    __a) Both External and Internal Resources__

    b) Only external resources 

    c) Only internal resources

    __*Anotacion:__ Azure AD helps users access both external and internal resources. External resources might include Microsoft Office 365, the Azure portal, and thousands of other software as a service (SaaS) applications. Internal resources might include apps on your corporate network and intranet, along with any cloud applications developed within your organization.

19. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company has asked you to research Azure Single Sign On. Based on your research, is the following statement correct in respect of Single Sign-On in Azure? Single sign-on enables a user to sign in one time and use that credential to access multiple resources and applications from different providers.

    __a) Yes__

    b) No

    __*Anotacion:__ Single sign-on enables a user to sign in one time and use that credential to access multiple resources and applications from different providers.

20. Tradewind Traders has recently migrated to Azure cloud services management wants you to implement resource locks to prevent accidental changes or deletions. Which of the following are valid options when configuring Resource Locks? Select all options that apply.

    __a) CanNotDelete__

    __*Anotacion:__ CanNotDelete means authorized people can still read and modify a resource, but they can't delete the resource without first removing the lock.

    b) CanNotModify

    __c) ReadOnly__

    __*Anotacion:__ ReadOnly means authorized people can read a resource, but they can't delete or change the resource. Applying this lock is like restricting all authorized users to the permissions granted by the Reader role in Azure RBAC:

21. Tradewind Traders has recently migrated to Azure cloud services and management wishes to chargeback some of the resource costs to various departments every month. Which is the best solution to meet these requirements with the least amount of administrative effort?

    a) Manually track using a Microsoft Excel spreadsheet

    b) Create Subscriptions for each department (ESTA NO)

    c) Tags

22. Tradewind Traders has recently migrated to Azure cloud services. Users have deployed multiple resources since the migration however today one of the developers has received a message when creating several SQL database instances stating that that the Azure subscription limits must be increased. What must be done to increase this limit?

    a) Upgrade your support plan

    __b) Create a service health alert__

    c) Create a new support request

    d) Modify an Azure policy

23. If you have a free trial subscription to Azure and you reach your credit limit during the trial period, what will happen to your resources?

    __a) Your existing Azure resources are removed from production and your Azure virtual machines are stopped and deallocated.__

    b) The oldest resources will be deleted once the credit limit has been reached allowing you to create new resources.

    c) You can carry on and access existing resources, but you will not be able to create new resources.

    __*Anotacion:__ When you spend all the credit included with your Azure free account, Azure resources that you deployed are removed from production, and your Azure virtual machines are stopped and deallocated. The data in your storage accounts are available as read-only. At this point, you can upgrade your subscription to a pay-as-you-go subscription. Try going back and Managing Costs and SLA Service Cycles

24. Tradewind Traders is planning to migrate to Azure cloud services. However, before this happens management requires some comparisons of the costs involved in using cloud services as opposed to an on-premises solution. What would be the first step you could take to provide this comparison information?

    a) Assume that the cost of running workloads on Azure is similar to running workloads on-premises. 

    b) Setup some resources in Azure as this is a free service. 

    __c) Run the Total Cost of Ownership Calculator.__

25. Tradewind Traders has recently migrated to Azure cloud services. The company has just completed a review of its current configuration and has discovered that there is a selection of unused resources currently in existence including multiple AD accounts, multiple groups, multiple public IP addresses, and multiple network interfaces. The company wants to reduce costs to a minimum. You recommend removing the unused user accounts. Will this reduce the monthly costs?

    a) Yes
    
    __b) No__

    __*Anotacion:__ You are not charged for user accounts. Therefore, deleting unused user accounts will not reduce the Azure costs for the company.

26. Which of the following define performance targets such as uptime?
 
    __a) Service Level Agreements__

    b) Support plans

    c) Usage Meters

    __*Anotacion:__ Service Level Agreements or SLAs define performance targets for an Azure product or service.

27. Tradewind Traders has recently migrated to Azure cloud services. Management wants clarification as to what will occur if Microsoft plans to end support for an Azure service and does NOT have a successor service. What notification period will Microsoft provide in this scenario?

    a) 30 days

    __b) 12 months__ 

    c) 90 days

    d) 6 months

    __*Anotacion:__ The Modern Lifecycle Policy covers products and services that are serviced and supported continuously. For products governed by the Modern Lifecycle Policy, Microsoft will provide a minimum of 12 months' notification before ending support if no successor product or service is offered.

28. Tradewind Traders has recently migrated to Azure cloud services. The company has just completed a review of its current configuration and has discovered that there is a selection of unused resources currently in existence including multiple AD accounts, multiple groups, multiple public IP addresses, and multiple network interfaces. The company wants to reduce costs to a minimum. You recommend removing the network interfaces. Will this reduce the monthly costs?

    a) Yes
        
    __b) No__

    __*Anotacion:__ You are not charged for unused network interfaces. Therefore, deleting unused network interfaces will not reduce the Azure costs for the company.

29. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. Management has asked you to determine what is guaranteed in an Azure Service Level Agreement (SLA) for virtual machines? Select the appropriate option.

    a) Performance 

    b) Feature Availability

    c) Bandwidth

    __d) Uptime__

    __*Anotacion:__ The SLA for virtual machines guarantees "uptime". The amount of uptime guaranteed depends on factors such as whether the VMs are in an availability set or availability zone.

## Semana 4 (Examen completo con preguntas de todos las semanas)
1. Tradewind Traders has recently migrated to Azure cloud services. The company is reviewing its support plans. You have been asked to determine from where support requests can be created. Which of the following statements is correct?
    
    a) The Azure portal

    b) Support.microsoft.com.

    __c) Thec Security & Compliance Admin Center__

    d) The Knowledge Center

2. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has asked you to design a deployment plan that will guarantee services running on virtual machines will continue to operate in the event a single datacenter fails. As part of this design, you will deploy virtual machines to two or more availability zones. Does this design meet the requirements of the Organisation?
 
    __a) Yes__
 
    b) No

3. Tradewind Traders have recently migrated to Azure cloud services. They operate a fairly complex network infrastructure that contains a large number of virtual networks and hundreds of virtual machines. The IT manager has asked you to research the easiest way to control incoming traffic to all the virtual networks. Which of the following is the simplest way to achieve this?

    a) Create a Virtual Network Gateways for each of the virtual networks
 
    b) Create a single Application Security Group (ASG)
 
    __c) Create a single Azure firewall__
    
    d) Create Azure ExpressRoute connections for each virtual network

    __*Anotacion:__ You can restrict traffic to multiple virtual networks with a single Azure firewall. Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources. It's a fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability.

3. Tradewinds Traders is planning to migrate some of its resources to Azure cloud services. Management wants a solution that will require the least amount of administrative effort and responsibility for managing the cloud resources. You have identified three cloud service models. Which model is best suited to satisfy the company's requirements?
    
    a) SaaS

    b) IaaS (ESTA NO)

    c) PaaS

4. Tradewind Traders has recently migrated to Azure cloud services and management wishes to chargeback some of the resource costs to various departments every month. Which in your opinion is the best solution to meet these requirements with the least amount of administrative effort?

    a) Create Subscriptions for each department 

    __b) Tags__

    c) Manually track using a Microsoft Excel spreadsheet

    __*Anotacion:__ Tags provide extra information, or metadata, about your resources. You might create a tag that's named Sales whose value is the name of the billing department. You can use Azure Policy to ensure that the proper tags are assigned when resources are provisioned.
    
5. Tradewind Traders has recently migrated to Azure cloud services. Management has asked you to research Azure feature Releases and their availability. Which of the following will allow all Azure customers an opportunity to test the beta and other pre-release features?
    
    __a) Public Preview__

    b) General availability 

    c) Private Preview

    __*Anotacion:__ During this phase, all customer with the proper Azure AD license are invited to evaluate the new feature

6. Tradewind Traders is planning to migrate to Azure cloud services but before they do, management has asked you to spend some time researching the Database solutions available in Azure specifically the capability to elastically and independently scale throughput and storage across any number of Azure regions worldwide. Based on your research, which of the following cloud database solutions is most appropriate to provide this feature?

    a) Azure Database for MySQL 

    __b) Azure Cosmos DB__

    c) Azure SQL Database

    d) Azure Database for PostgreSQL 

    __*Anotacion:__ Cosmos DB level of flexibility means that as you migrate your company's databases to Azure Cosmos DB. Cosmos DB enables you to elastically and independently scale throughput and storage across any number of Azure regions worldwide and your developers can stick with the API where they're most comfortable.

7. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks in place. As part of their ongoing cloud implementation management wants to have the ability to prevent virtual machines from being created in certain resource groups. Which of the following can be used to prevent VM’s being created in specific resource groups?

    a) Lock 

    b) Tag

    c) Azure role 

    __d) Azure policy__
    
    __*Anotacion:__ An Azure Policy is a service in Azure that you use to create, assign, and manage policies. These policies enforce different rules and effects over your resources, so those resources stay compliant with your corporate standards and service level agreements. In this question, we would create an Azure policy assigned to the resource group that denies the creation of virtual machines in the resource group.

8. Tradewind Traders is planning to migrate to Azure cloud services but before they do, management has asked you to spend some time researching the Database solutions available in Azure specifically the ability to migrate existing on-premises SQL databases to Azure SQL Databases. Based on your research, is it possible to migrate directly?

    __a) Yes__

    b) No

    __*Anotacion:__ That’s correct, you can migrate your existing SQL Server databases with minimal downtime using the Azure Database Migration Service. The Azure Database Migration Service performs all the required steps. You just change the connection string in your apps.

9. Tradewind Traders has migrated its data and resources to Azure cloud services. They currently have multiple subscriptions and virtual networks across multiple regions. As part of their ongoing cloud implementation management is implementing a policy that limits the creation of additional Azure resources by administrators to a region based on their office location and country. Which of the following can be used to implement this policy?

    a) Read-only lock

    b) Reservation

    __c) Azure policy__

    d) Management Group 

    __*Anotacion:__ Azure policies can be used to define requirements for resource properties during deployment and for already existing resources. Azure Policy controls properties such as the types or locations of resources.

10. Tradewind Traders is planning to migrate to Azure cloud services. Management has asked you to spend some time researching the big data and analytic solutions available in Azure. Based on your research, which of the following provides an on-demand analytics job service that simplifies big data by enabling users to write queries to transform their data and extract valuable insights?

    a) Azure Synapse Analytics

    __b) Azure Data Lake Analytics__

    c) Azure Databricks

    d) Azure HDInsight

    __*Anotacion:__ Azure Data Lake Analytics is an on-demand analytics job service that simplifies big data. Instead of deploying, configuring, and tuning hardware, you write queries to transform your data and extract valuable insights.

11. Tradewind Traders has recently migrated to Azure cloud services and management wants to start developing AI solutions. Management requires the development of an app that will predict future outcomes based on private historical data. Which Azure service will you recommend to management?

    a) Azure Cognitive Services

    __b) Azure Machine Learning__

    c) Azure Bot Service

    __*Anotacion:__ Azure Machine Learning is a platform for making predictions. It consists of tools and services that allow you to connect to data to train and test models to accurately predict a future result.

12. Tradewind Traders is planning to migrate to Azure cloud services, however, management has asked you to research some of the main benefits of cloud services. One of these benefits is referred to as agility. Which of the following benefits of cloud services are characteristic of agility?

    a) Your cloud-based applications can provide a continuous user experience with no apparent downtime even when things go wrong.
 
    __b) Cloud-based resources can be deployed and configured quickly as your requirements change.__
 
    c) You can deploy your applications with the confidence that comes from knowing that your data is safe in the event of a disaster.
 
    d) Applications and data can be deployed to regional datacenters around the globe.

    __*Anotacion:__ With agility, cloud-based resources can be deployed and configured quickly as your application requirements change.

13. Tradewind Traders has recently migrated to Azure cloud services and management wants to start developing AI solutions. Management requires the development of an app that can understand the content and meaning of images, video, audio, or translate text into a different language. Which Azure services do you think are the most appropriate to use in this scenario?

    a) Azure Machine Learning

    __b) Azure Cognitive Services__

    c) Azure Bot Service
    
    __*Anotacion:__ Azure Cognitive Services provides pre-built machine learning models that enable applications to see, hear, speak, understand, and even begin to reason.

14. Tradewinds Traders is planning to migrate to Azure cloud services. Management has questions regarding the expenditure once they migrate. You have been asked to research expenditure types and how they differ. Based on your research, you have identified two types of expenditures that are relevant to Cloud migration. Capital Expenditure (CapEx) and Operational Expenditure (OpEx). Which of these expenditure types require the upfront spend on physical infrastructure that can then be deducted as an expense over time?

    __a) Capital Expenditure (CapEx)__
 
    b) Operational Expenditure (OpEx)

    __*Anotacion:__ Capital Expenditure (CapEx) is the upfront spending of money on physical infrastructure and then deducting that upfront expense over time. The upfront cost from CapEx has a value that reduces over time.

15. Tradewind Traders has recently migrated to Azure cloud services and management wants you to research the features of GitHub and Azure DevOps. Based on this research do you agree with the following statement? GitHub is lighter weight than Azure DevOps, with a focus on individual developers contributing to open source while Azure DevOps, is more focused on enterprise development with heavier project management, planning tools, and fine-grained access control.
 
    __a) Yes__
 
    b) No

    __*Anotacion:__ GitHub has a long and trusted history with public repositories and is trusted by tens of thousands of open-source projects. GitHub is “lighter-weight” than Azure DevOps, with a focus on individual developers contributing to open source. Azure DevOps, on the other hand, is more focused on enterprise development with heavier project management and planning tools, and finer-grained access control.

16. Tradewinds Traders is planning to migrate to Azure cloud services however management has questions regarding the expenditure once they migrate. You have been asked to research expenditure types and how they differ. Based on your research you have identified two types of expenditure that are relevant to Cloud migration. Capital Expenditure (CapEx) and Operational Expenditure (OpEx). Which of these expenditure types requires no upfront cost and allows you to pay for services as you use them? 
 
    a) Expenditure (CapEx)
 
    __b) Operational Expenditure (OpEx)__
    
    __*Anotacion:__ Operational Expenditure (OpEx) is spending money on services or products now and being billed for them now. You can deduct this expense in the same year you spend it. There is no up-front cost, as you pay for a service or product as you use it.

17. Tradewind Traders has recently migrated to Azure cloud services. Management wants you to research the features of Azure DevTest Labs which they feel may be a good fit for their developers on an ongoing basis. Based on your research, do you agree with the following definition? DevTest labs provide automated provisioning of pre-created lab environments with required configurations and tools already installed.
 
    __a) True__
 
    b) False

    __*Anotacion:__ Azure DevTest Labs allows for the provisioning of pre-created lab environments with required configurations and tools already installed. It is a huge timesaver for quality assurance professionals and developers

18. Tailwind Traders has recently migrated to Azure cloud services. Management now requires ongoing analysis of how well they are using their services compared to industry best practices. Which monitoring tool would you recommend using for this?
 
    a) Azure Service Health

    __b) Azure Advisor__

    c) Azure Monitor

19. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main features of cloud services. One of these features is Geo-distribution. What does Geo Distribution mean?

    a) Cloud-based resources can be deployed and configured quickly as your requirements change.

    b) You can deploy your applications with the confidence that comes from knowing that your data is safe in the event of a disaster. 

    c) Your cloud-based applications can provide a continuous user experience with no apparent downtime even when things go wrong.

    __d) Applications and data can be deployed to regional datacenters around the globe.__

    __*Anotacion:__ With Geo-distribution, applications and data can be deployed to regional datacenters around the globe ensuring that your customers always have the best performance in their region

20. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research some of the main features of cloud storage. Which of the following is the most suitable for the storage of streaming video and audio?

    __a) Azure Blob Storage__
 
    b) Azure Storage Tiers
 
    c) Azure Files Storage
 
    d) Azure Disk Storage

    __*Anotacion:__ Blob Storage is ideal for serving images or documents directly to a browser, storing files for distributed access, and streaming media. 

21. Tailwind Traders have recently migrated to Azure cloud services. The company has multiple offices around the globe which requires IT staff to travel between them regularly. The IT manager is now hoping to provide a solution that will allow employees to monitor the services remotely. Which service Azure Cloud services do you think is best to use in this scenario?

    __a) Azure Mobile App__
 
    b) Azure PowerShell
 
    c) Azure CLI

    __*Anotacion:__ The Azure mobile app running on a phone or tablet could help key employees keep an eye on the health of the cloud environment. The Azure mobile app is a good compromise in this scenario, it allows employees the freedom to be away from the office while still being able to perform one-off management and administrative tasks.

22. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research connectivity features between your on-premises environment and Cloud resources. In your research, you learn that Azure virtual networks enable you to filter traffic between subnets. Which of the following are valid filtering approaches? Select all options that apply.
 
    a) Border Gateway Protocol

    __b) Network security groups__

    __*Anotacion:__ A network security group is an Azure resource that can contain multiple inbound and outbound security rules. You can define these rules to allow or block traffic, based on factors such as source and destination IP address, port, and protocol.
 
    __c)Network virtual appliances__
    
    __*Anotacion:__ A network virtual appliance is a specialized VM that can be compared to a hardened network appliance. A network virtual appliance carries out a particular network function, such as running a firewall or performing Wide Area Network (WAN) optimization.

23. Tailwind Traders has recently migrated to Azure cloud services. Management has asked you to work on optimizing their cloud services for reliability, security, performance, costs, and operations based on expert best practices. Which Azure monitoring tool would you recommend to best satisfy this requirement?
 
    a) Azure Monitor
 
    __b) Azure Advisor__

    c) Azure Service Health 

    __*Anotacion:__ Azure Advisor evaluates your Azure resources and makes recommendations to help you improve reliability, security, and performance, achieve operational excellence, and reduce costs.

24. Tradewind Traders is planning to migrate to Azure cloud services however management has asked you to research Policy-based VPN gateways. In your research, you learn that Policy-based VPN Gateways evaluate all data packets against sets of IP addresses to determine the tunnel that the packet is going to be sent through. Which of the following are key features of policy-based VPN gateways in Azure? Select all options that apply.

    a) Support for IKEv2.

    __b) Compatibility with legacy on-premises VPN devices__
    
    __*Anotacion:__ Policy-based VPNs must be used in specific scenarios that require them, such as for compatibility with legacy on-premises VPN devices.

    c) Dynamic routing protocols

    __d) Use of static routing__ 
    
    __*Anotacion:__ Combinations of address prefixes from both networks control how traffic is encrypted and decrypted through the VPN tunnel. The source and destination of the tunneled networks are declared in the policy and don't need to be declared in routing tables.

25. Tailwind Traders has recently migrated its data and resources to Azure cloud services. Management has asked you to provide a personalized view of the health of the Azure services, regions, and resources. Which of the following tools would best satisfy these requirements?

    a) Azure Monitor

    b) Azure Advisor

    __c) Azure Service Health__

    __*Anotacion:__ Azure Service Health provides a personalized view of the health of the Azure services, regions, and resources.

26. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. They are now planning on building and deploying an Artificial Intelligence (AI) solution in Azure. Which feature should the company avail of to build, test, and deploy predictive analytics solutions?

    a) Azure Logic Apps

    __b) Azure Machine Learning Designer__

    c) Azure Cosmos DB

    d) Azure Batch

    __*Anotacion:__ Azure Machine Learning designer lets you visually connect datasets and modules on an interactive canvas to create machine learning models.

27. Tradewind Traders has recently migrated some of their data and resources to Azure cloud services, Management has asked you to research the various features of serverless computing in Azure. Which of the following services provides serverless computing in Azure?

    __a) Azure Functions__

    b) Azure virtual machines

    c) Azure Container Instances

    d) Azure storage account

    __*Anotacion:__ Azure Functions is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure

28. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has decided to only make use of the Platform as a Service (PaaS) offerings in Azure. You have been asked to design a migration plan. As part of this design, you have included the creation of Azure virtual machines, Azure SQL databases, and Azure Storage accounts. Does this design meet the requirements of the organization?
 
    a) Yes
 
    __b) No__

    __*Anotacion:__ Platform as a service (PaaS) is a complete development and deployment environment in the cloud. PaaS includes infrastructure servers, storage, and networking as well as middleware, development tools, business intelligence (BI) services, database management systems, and more. PaaS is designed to support the complete web application lifecycle: building, testing, deploying, managing, and updating. However, virtual machines are examples of Infrastructure as a service (IaaS). IaaS is an instant computing infrastructure, provisioned and managed over the internet.

29. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. Management is concerned that costs of resources may exceed budget in any month. Management wants to be notified by email alerts when the cost of the current billing period for an Azure subscription exceeds a specified limit. Which of the following Azure features can be implemented to satisfy this requirement?
 
    __a) Budget Alerts__

    b) Access control (IAM)

    c) Compliance

    d) Azure advisor 
    
    __*Anotacion:__ Budget alerts notify you when spending, based on usage or cost reaches or exceeds the amount defined in the alert condition of the budget. Cost Management budgets are created using the Azure portal or the Azure Consumption API.

30. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management requires that users can create virtual machines by using their Android tablets. You recommend that they use the Azure portal. Will this recommendation work?
 
    __a) Yes__
 
    b) No

    __*Anotacion:__ The Azure portal is a web-based, unified console that provides an alternative to command-line tools. With the Azure portal, you can manage your Azure subscription using a graphical user interface. Being web-based, the Azure portal can be run on a browser from a tablet that runs the Android operating system.

31. Tradewind Traders is planning to migrate its data and resources to Azure cloud services. The company wants to ensure that certain content is only accessible from specific locations. Which of the following solutions is the most suitable to meet this requirement?
 
    a) Multifactor Authentication
 
    b) Single Sign On (SSO)
 
    __c) Conditional Access__

    __*Anotacion:__ Conditional Access is a tool that's used by Azure Active Directory to allow (or deny) access to resources based on identity signals. These signals include who the user is, the user's location, and what device the user is requesting access from.

32. Tradewind Traders has recently migrated to Azure cloud services. Azure has various reporting and monitoring tools built-in. What is the simplest tool to use to create a single report that will show all security information to be collected from all the monitoring tools?
 
    __a) Azure Sentinel__
 
    b) Secure Score
 
    c) Azure Key Vault

    __*Anotacion:__ Azure Sentinel is Microsoft's cloud-based SIEM solution and can combine and report on security data from different sources.

33. Tailwind Traders has recently moved to Azure cloud services from an on-premises Windows environment and the Chief Financial Officer (CFO) now wants to gain insights into how Azure resources are being used and costed. He wants to see the data displayed visually and be able to run reports on an ongoing basis in real-time. Which tool would you recommend using in this scenario?

    __a) Azure Portal__

    b) Azure PowerShell

    c) ARM Templates

    d) Azure CLI

    __*Anotacion:__ That’s correct, given the requirement to view data visually and create custom reports the Azure portal is the best choice. You can quickly find answers to questions using a range of reporting options.

34. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management wants to implement security that will limit the applications that can run on certain virtual machines. Which of the following approaches provide such a solution?

    a) Connect the virtual machines to Azure Sentinel.

    b) Administrators periodically review which applications are running on each VMs by creating and running PowerShell scripts. (ESTA NO)

    c) Implement an application control rule in Azure Security Center. 

35. Tradewind Traders is planning to migrate some of their data and resources to Azure cloud services, Management has asked you to design a deployment plan that will guarantee services running on virtual machines will continue to operate in the event a single datacenter fails. As part of this design, you will deploy virtual machines to a single scale set. Does this design meet the requirements of the organization?

    a) Yes

    __b) No__

    __*Anotacion:__ Azure virtual machine scale sets let you create and manage a group of load-balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. Scale sets provide high availability to your applications and allow you to centrally manage, configure, and update many VMs. However, this question does not specify that the scale set will be configured across multiple datacenters, so this solution does not meet the goal.

36. Tradewind Traders is planning to migrate to Azure cloud services, Management has asked you to research some of the features of high availability within Azure cloud services. Based on your research, Azure Availability Zones can protect which of the following types of failure?

    a) Azure datacenter failure

    b) Physical Server failure

    c) Azure Storage failure

    d) Azure Region failure (ESTA NO)

37. Tradewinds Traders is planning to migrate to Azure cloud services however management has questions about management and responsibilities once resources are migrated. You have identified three cloud service models. In which model does the cloud provider keep the hardware up to date but the operating system maintenance and network configuration are left to the cloud tenant? 

    a) PaaS

    __b) IaaS__

    c) SaaS

    __*Anotacion:__ IaaS is the cloud service model that is closest to managing physical servers. In this model, the cloud provider keeps the hardware up to date, but operating system maintenance and network configuration are left to the cloud tenant. 

38. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. Management wants to allow HTTP access from the internet to a specific virtual machine. You modify a DDoS protection plan. Does this meet the requirements of management?

    a) Yes

    __b) No__

    __*Anotacion:__ DDoS is a form of attack on a network resource. A DDoS protection plan is used to protect against DDoS attacks; it does not provide connectivity to a virtual machine. To ensure that a virtual machine named VM1 is accessible from the Internet over HTTP, you need to modify a network security group or Azure Firewall

39. Tradewind Traders has recently migrated to Azure cloud services, The IT manager has asked you to create a solution that will provide several windows 10 users mapped network drive access to content that will be stored in Azure Storage. What type of storage solution should you create in Azure?

    a) An Azure SQL database (ESTA NO)

    b) A virtual machine data disk

    c) A Blobs service in a storage account

    d) A Files service in a storage account

40. Tradewind Traders operate a successful ecommerce site. Recent customer feedback has shown that response times at certain times during the month can be very slow. Which feature of Azure cloud services could improve response times while also providing cost management?

    a) High Availability

    b) Load Balancing (ESTA NO)

    c) Elasticity

    d) High Latency

41. Tradewind Traders has recently migrated some of their data and resources to Azure cloud services, Management has asked you to research specific tools to assist with securing their environment. Which of the following would be the simplest way to monitor your resources and perform automatic security assessments to identify potential vulnerabilities?

    a) Azure Key Vault

    __b) Azure Security Center__

    c) Azure Sentinel

    __*Anotacion:__ Azure Security Center is a monitoring service that provides visibility of your security posture across all your services on Azure and on-premises.

42. Tradewind Traders is planning to migrate some of its data and resources to Azure cloud services. Management has asked you to design a deployment plan that will guarantee services running on virtual machines will continue to operate in the event a single datacenter fails. As part of this design, you will deploy virtual machines to two or more resource groups. Does this design meet the requirements of the organization?

    a) Yes

    __b) No__

43. Tradewind Traders has recently migrated some of its data and resources to Azure cloud services. As part of their ongoing migration, management has requested information on the storage of encryption keys and secrets like certificates, connection strings, and passwords. You have spent some time researching this topic. Based on your research, which of the following can be used to store encryption keys and secrets in Azure?

    a) Azure Key Vault

    b) Personally Identifiable Information (PII) (ESTA NO)

    c) Azure Active Directory (Azure AD) administrative accounts


## AZ-900 Exam simulation

1. The Nutex Corporation plans to provide app management and monitoring services to some companies. The management wants you to discover ways to obtain customer-level usage and billing details. Which of the following statements about options available with Azure Subscriptions are TRUE? (Choose three.)

    __A)Existing key vaults are inaccessible when a subscription is added to an Active Directory tenant.__

    B)Credit entitlements from one subscription can be moved to another.

    C)Azure subscriptions must always be purchased in $ (USD).

    __D)The registered Azure Stack must be re-registered after adding a subscription to an Active Directory tenant.__

    __E)Multiple Azure subscriptions can exist within a tenant.__

    __*Anotacion:__

    The following statements are true:

        - Multiple Azure subscriptions can exist within a tenant.
        - Existing key vaults are inaccessible when a subscription is added to an Azure Active Directory tenant.
        - The registered Azure Stack must be re-registered after adding a subscription to an Active Directory tenant.

    Each subscription can independently fuel a different set of resources within the same customer tenant. Subscriptions can come from different purchase channels and can co-exist independent of each other.

    The following occurs when you add a subscription to an Azure Active Directory tenant:

        - Users with RBAC roles lose their access.
        - Service Administrators and Co-Administrators lose their access.
        - Existing key vaults are inaccessible until the key vault tenant ID is changed.
        - Managed identities for resources such as Virtual Machines or Logic Apps must be re-enabled or recreated.
        - A registered Azure Stack must be re-registered.

    Credit entitlements in one subscription cannot be moved to another subscription. Resources can be migrated from one subscription to another, but not the credit entitlements.

    Azure subscriptions can be bought by the designated currency based on the channel through which one procures, and all major currencies can be used.

2. The Nutex Corporation plans to comply with all the privacy, compliance, and data protection standards. You are asked to investigate the security, compliance, and privacy offerings and commitments from Microsoft. Which of the following statements about the Azure Service Trust Portal are TRUE? (Choose three.)

    __A)The Azure Service Trust Portal provides Security and Compliance Blueprints to assist customers with building applications that comply with compliance regulations and standards.__
    
    __B)Microsoft’s privacy principle states that Microsoft will not use your email, chat, files, or other personal content to target ads to you.__
    
    __C)If an Azure tenant is deactivated, Microsoft permanently deletes all data for that tenant in the Service Trust Portal within 24 hours of tenant deactivation.__
    
    D)All transactions to Azure Storage through the Azure portal occur via HTTPS.
    
    E)If a customer’s cloud subscription expires, Microsoft will delete the data in the subscription in 90 days without any notice.

    __*Anotacion:__ 

    Microsoft’s privacy principle states that Microsoft will not use your email, chat, files, or other personal content to target ads to you. Microsoft’s privacy principle also states that:

        - You are in control of your privacy with easy-to-use tools and clear choices.
        - Microsoft will be transparent about data collection and use so that you can make informed decisions.
        - Microsoft protects your data with strong security and encryption.
        - Microsoft will respect your local privacy laws and fight for legal protection of your privacy as a right.
        - When Microsoft collects data, Microsoft will use it to benefit you and to make your experiences better.

    If an Azure tenant is deactivated, Microsoft permanently deletes all data for that tenant in the Service Trust Portal (e.g., user information and data uploaded to Compliance Manager) within 24 hours of tenant deactivation.

    The Azure Service Trust Portal provides Security and Compliance Blueprints to assist customers with building applications that comply with compliance regulations and standards.

    Azure Security and Compliance Blueprints include industry-specific overviews and guidance, customer responsibilities matrix, reference architectures with threat models, control implementation matrices, and automation to deploy reference architectures.

    If a customer’s cloud subscription expires, Microsoft will not delete the data in the subscription in 90 days without notice. If you terminate a cloud subscription or it expires (except for free trials), Microsoft will store your customer data in a limited-function account for 90 days (the “retention period”) to give you time to extract the data or renew your subscription. During this period, Microsoft provides multiple notices so you will be amply forewarned of the upcoming deletion of data.

3. The Nutex Corporation wants to build and use chunks of code to integrate the apps they have deployed on Azure. They expect the integrations to be made within a short turnaround time. Match the attribute or setting of the Azure Functions feature with its purpose.

    Durable Functions -> Write stateful functions in a serverless compute environment
    
    dynamicThrottlesEnabled -> Check system performance counters like connections, threads, processes, memory, and CPU
    
    matchCondition -> Define a single API surface for multiple function apps
    
    Schedule -> Triggers the function to using a CRON expression with six fields
    
    Binding -> Fetch data from external services

    __*Anotacion:__
    A Durable Function is an extension of Azure Functions that can be used to write stateful functions in a serverless compute environment. Customers can define custom stateful workflows by writing orchestrator functions and define stateful entities by creating entity functions using the Azure Functions programming model. Behind the scenes, these functions manage state, checkpoints, and restarts.

    The hosts file in the function app can be modified for HTTP concurrency and, as a result, scale the function app.

    dynamicThrottlesEnabled is an option available in the hosts file. When the dynamicThrottlesEnabled option is enabled to scale the functions, the request processing pipeline periodically checks system performance counters such as connections, threads, processes, memory, and CPU. If any of those counters are over a high threshold (80%), requests are rejected with a 429 "Too Busy" response until the counter(s) return to normal levels.

    Azure Functions Proxies can be used to break a large API into multiple function apps (as in a microservice architecture), while still presenting a single API surface for clients. The proxies are stored in a proxies.json file, located in the root of a function app directory. This file can be edited. matchCondition is one of the options that can be edited and is an object that defines the requests that trigger the execution of this proxy.

    Schedule is a setting that runs the functions at specified time intervals. The input to schedule is a six field CRON expression that denotes a schedule using an NCronTab library.

    Azure Functions use input and output bindings to make data from external services available to the code.

4. You plan to store historical tax information from 2015 to 2021 in Azure. Users in the tax department must mount a network drive to access the tax information from their Windows 11 and Linux devices. Your solution is to implement Azure Information Protection (AIP). Does your solution meet the needs of the tax department?

    A)Yes

    B)No

    __*Anotacion:__

    Azure Information Protection (AIP) will not meet the needs of the tax department. Azure Information Protection (AIP) will not allow tax department users from Linux or Windows devices to map a drive to access the historical tax information. You will need to use an Azure file share. You can use a storage account key to access the file share. You can have the file share accessed with either Server Message Blocks (SMB) or Network File System (NFS) protocol. With the Azure Files service, you can mount file shares can be mounted by cloud or on-premises deployments. Windows clients can access SMB Azure file shares. Linux or macOS clients can access SMB Azure file shares and NFS Azure Files shares.

    Azure Information Protection (AIP) is a cloud-based solution that is part of the Microsoft Information Protection (MIP) solution. It uses labels to classify assets and apply tags.

5. You are planning to host a business application on the Azure cloud. After some research, you plan to use Azure Container Instances because it enables you to run multiple instances of an application on a single host machine. Which of the following statements are correct? Select “Yes” else “No” for the given statements.
The following table shows the correct answers for the given statements.

    Azure Container Services is a Platform as a Service (PaaS) in which you can upload containers that run on the platform. -> Yes
    
    Azure Container Services is a Software as a Service (SaaS) platform in which you can upload containers that run on the platform. -> No
    
    Azure Container Services is an Infrastructure as a Service (IaaS) in which you can upload containers that run on the platform. -> No
    
    You can manage both Docker and Microsoft-based containers using Azure Container Instances and Azure Kubernetes Service (AKS). -> Yes
    
    You can manage both Docker and Microsoft-based containers using only Azure Container Instances. -> No
    
    Azure Container Instances is a quick and easy way to run a container without using any virtual machines and without having to use a higher-level service. -> Yes

    __*Anotacion:__ 

    Containers are becoming the popular and preferred way to deploy and manage cloud applications. Azure Container Instances is the best choice to run multiple instances of an application on a single host machine.

    Azure Container Services is a Platform as a Service (PaaS) offering that allows you to upload containers that run on the platform. It offers the quickest and easiest way to run a container without using any virtual machines and without using a higher-level service.

    You can manage both Docker and Microsoft-based containers using Azure Container Instances and Azure Kubernetes Service (AKS). Containers are a virtual environment that allow you to host multiple virtual machines on a single physical host. In the same manner, you can run multiple containers on a single physical or virtual host. Containers enable you to respond to changes on demand. You can quickly restart the containers in case of a crash or hardware interruption. Docker is the most popular container engine, which is supported by Azure.

    You can use the same API to schedule both Windows and Linux containers. Azure Container Instances provide optimum utilization by allowing exact specifications of CPU cores and memory. With Azure Container Instances, you can execute a command in a running container by providing the interactive shell to help with application development and troubleshooting.

6. Your company needs to protect their application and data from datacenter failures. The company plans to move to Azure. You want to ensure that applications and data are stored in availability zones. Which of the following statements best describes availability zones?

    A)A way for you to ensure your application remains online if a high-impact maintenance event is required or a hardware failure occurs
    
    B)A geographical area containing at least one, but potentially multiple, datacenters that are in close proximity and networked together with a low-latency network
    
    C)Physically separate locations within an Azure region
    
    D)A discrete market typically containing two or more regions that preserves data residency and compliance boundaries
    
    __*Anotacion:__

    Availability zones are physically separate locations within an Azure region. Each availability zone has one or more datacenters. Each datacenter is equipped with independent power, cooling, and networking. Availability zones protect your applications and data from datacenter failures.

    An availability zone is not a discrete market typically containing two or more regions that preserves data residency and compliance boundaries. That describes a geography. A geography is a unique market that contains two or more regions that stores data in the regions according to the compliance boundaries of the regions.

    An availability zone is not a geographical area containing at least one, but potentially multiple, datacenters that are in close proximity and networked together with a low-latency network. That describes a region. A region is a geographical area containing one or more datacenters networked together with a low-latency network and are in close proximity.

    An availability zone is not a way for you to ensure that your application remains online if a high-impact maintenance event is required, or a hardware failure occurs. That can be done with an availability set. Availability sets logically group resources so that Azure can ensure that VM resources are isolated from each other when they are in an Azure datacenter. Availability sets allow your application to remain online if a hardware failure occurs or a maintenance event is required.

7. You need to monitor the VMs running in your department’s resource group. These VMs run several applications that query a backend database. Department members create spreadsheets from the data that is queried from the database. You need to respond quickly to alerts and take action on those alerts by using Azure CLI or PowerShell commands. You will be attending a two-day music festival over the weekend. You plan to take only your Android phone. However, there are no team members that can take over your monitoring activities. What can you do to ensure that monitoring activities continue?

    A)Download the Microsoft 365 Admin app
    
    B)Download the Azure mobile app
    
    C)Download the Microsoft tunnel app
    
    D)Download the Remote Desktop app
    
    __*Anotacion:__

    You should download the Azure mobile app. This app will allow you to monitor VMs, respond to alerts and take corrective actions for those alerts. You can also use this app to run Azure PowerShell commands, or Azure CLI commands.

    You should not use the Remote Desktop app. This app will allow you to connect via RDP to a VM. While you can connect to a VM, you are not alerted if there are issues with the VM.

    You should not use the Microsoft 365 Admin app. This app will allow you to manage all the apps in Microsoft 365. While the developers use the spreadsheets, the monitoring should be on the VMs, not on the spreadsheets.

    You should not download the Microsoft tunnel app. This app is used to ensure that you can securely connect to Azure resources. This app by itself will not notify of issues with Azure resources.

8. You have been tasked to create a solution to monitor network security groups within the Dream Suites Azure subscription. Diagnostic logging for network security groups has been enabled. You need to review the logs and show details for network security group blocked flows in the last hour.(Image) What solution below will meet the requirements?

    A)Azure Security Center

    B)Azure Application Insights

    C)Azure Log Analytics

    D)Azure Service Health

    __*Anotacion:__ 

    Azure Log Analytics is a service that is used to collect log data from Azure and on-premises. Insights can be derived from this log repository and stored in a single workspace. A powerful expressive query language is available to transform log data into actionable insight. When turning on diagnostic logging for a network security group you have the option to send to log analytics to obtain further insight. This option will provide the ability to show details for network security group blocked flows in the last hour.

    The Azure Security Center feature is a robust management platform that allows monitoring of threats within on-premises and Azure workloads and to fix discovered vulnerabilities quickly. This security platform provides the visibility to visually manage the security posture of your on-premises and Azure assets. This option will not provide the ability to show details for network security group blocked flows in the last hour.

    The Azure Service Health dashboard is the centralized place to track planned maintenance schedules, health advisories, and health alert notifications. This option will not provide the ability to show details for network security group blocked flows in the last hour.

    The Azure Application Insights solution provides the information required to understand how an app is performing and how it is being used. This solution can be used to monitor web applications to quickly detect performance bottlenecks, diagnose issues and to help improve usability. A common use case of the Azure Application Insights solution is integrating into Visual Studio to help automate the DevOps process to provide continuous improvement. This option will not provide the ability to show details for network security group blocked flows in the last hour.

9. Your company needs to select the appropriate cloud model and category to deploy. Match the cloud model or category with its appropriate description.

    __*Anotacion:__ 

    The cloud models and categories should be matched with the descriptions in the following manner:

        Public cloud – Each organization shares the cloud service provider’s infrastructure with the other companies that have subscribed to the cloud.

        Private cloud – The organization deploys its own cloud infrastructure, usually behind a firewall.

        Hybrid cloud – The organization’s deployment is split between resources deployed on the cloud service provider’s infrastructure and resources deployed in its own cloud infrastructure.

        Community cloud – A group of related organizations share infrastructure provided by the cloud service provider for software and development tools that are designed to meet community needs.

        SaaS (software as a service) – The cloud service provider hosts the applications on the cloud servers.

        IaaS (infrastructure as a service) – The cloud service provider maintains all the hardware required for the cloud.

        PaaS (platform as a service) – The organization hosts the deployment platform, including the operating system and application services.

        NaaS (network as a service) – The cloud service provider provides network services over the Internet.

        DSaaS (data science as a service) – The cloud service provider hosts analytics resources for data-driven applications

10. The Nutex Corporation has an on-premises datacenter and plans to move some of their applications, servers, and databases to the Azure cloud. Before migrating, management wants to understand how much money would be saved over the next five years by moving to the cloud versus remaining on-premises. You need to consider all of the hidden costs involved with operating on-premises and in the Azure Cloud. What is the BEST way to achieve the objective?

    A)Use the Total Cost of Ownership (TCO) calculator as a starting point.

    B)Use historical financial records to ascertain the TCO.

    C)Use manual calculations to ascertain the hidden costs involved.

    D)Use the Azure Pricing Calculator as a starting point.

    E)Ask similar organizations to provide their TCO and do a cost comparison using the TCO calculator.

    __*Anotacion:__

    You should use the Total Cost of Ownership (TCO) calculator as a starting point in the given scenario. You do not need an Azure subscription to use it.

    Working with the TCO calculator involves three steps:

    - Define your workloads – You should provide the specifications of your on-premises infrastructure to the TCO calculator based on the below four categories:
        - Servers – this includes operating systems, virtualization methods, CPUs, and memory.
        - Databases – this includes database types, server hardware, and the Azure services you want to use.
        - Storage – this includes storage type and capacity.
        - Networking – this includes the amount of network bandwidth you are currently consuming in the on-premises environment.
    - Adjust assumptions – In this step, you specify the license information you use in your on-premises environment. You can save money by reusing those licenses in Azure. You can also determine if you need storage in another Azure region for redundancy. You can then specify the electricity price per kilowatt (KWh), hourly rate for IT administration, and network maintenance cost as a percentage of network hardware and software costs.
    - View the report – Choose the timeframe, for example five years as in the given scenario. The TCO calculator will generate the report based on the information you have provided.
    
    You should not use manual calculations to ascertain the hidden costs involved with operating on-premises and in the Azure cloud because there is a high chance of forgetting some factors and miscalculating the results. It is best to use the TCO calculator.

    You should not use the Azure pricing calculator because it will not account for the hidden costs involved in running an on-premises data center. Hidden costs are included in the Assumptions step of the TCO calculator. The Azure pricing calculator will provide up-front and monthly costs associated with the specific Azure resources you choose to purchase, including the costs of technical support and licensing.

    You should not use historical financial records to ascertain the TCO. This is not the BEST option to choose and would be part of the manual calculations to ascertain the hidden costs. While using manual calculations, you can use historical financial records to ascertain the TCO.

    You should not ask similar organizations to provide their TCO and perform a cost comparison using the Microsoft TCO calculator. You can ask other organizations to learn how much they have saved over the period of switching from on-premises to Azure cloud. This option can help you make a decision to some extent.

11. Which of the following is the proper use of an Azure ARM template?

    A)To organize resources and subscriptions
    
    B)To deploy predictive analytics
    
    C)The automatic creation of Azure resources

    D)To act as a broker with message queues and publish-subscribe topics (in a namespace).
    
    __*Anotacion:__ 

    Azure Resource Manager templates are JavaScript Object Notation (JSON) files that specify the infrastructure and configuration for your project. They can be used to automate the creation of resources. An ARM template can create identical resources in multiple locations.

    Organizing resources and subscriptions is better done through the use of management groups. Azure Management Groups can be used to create an effective and efficient hierarchy to manage Azure subscriptions and resources.

    The Azure Service bus, not an ARM template, is a broker with message queues and publish-subscribe topics (in a namespace).

    Deploying predictive analytics is better done with the Azure Machine Learning Studio. This is a drag and drop tool that allows you to build, test, and deploy predictive analytics using AI.

12. Your organization has offices in multiple locations in France. Teams are distributed across the country. Your organization uses a private cloud storage solution to synchronize work-related data and make it available to employees across locations. Employees must manually synchronize the data on the cloud with that on their computers. You are asked to plan for a solution that automatically synchronizes data, reduces costs and eliminates the dependency on Internet speeds to synchronize data. You plan to use Azure File Storage. Which of the following are mandatory requirements to implement Azure File Storage and accomplish the goal of the plan? (Select all that apply.)

    A)Prep on-premises servers that meet the requirements to deploy Azure File Sync.

    B)Deploy Azure File Sync on the on-premises servers.

    C)Install Windows Deployment Services on-premises

    D)Create an Azure File Share on the Azure portal.

    E)Register the on-premises servers with the Storage Sync Service.

    F)Create ExpressRoute circuit(s) for the Azure File Sync solution.

    G)Create a Sync Group and add the on-premises servers as Server Endpoints on the Azure portal.

    __*Anotacion:__

    The following are mandatory requirements:

    - Deploy Azure File Sync on the on-premises servers.
    - Create an Azure File Share on the Azure portal.
    - Prep on-premises servers that meet the requirements to deploy Azure File Sync.
    - Register the on-premises servers with the Storage Sync Service.
    - Create a Sync Group and add the on-premises servers as Server Endpoints on the Azure portal.
    
    One of the purposes of Azure File Storage is for file shares in the cloud. You can use Azure File Storage to create file shares without worrying about overhead of a physical server, device, or appliance. The following are the steps you must perform to set up Azure File Storage and the planned solution:

    - Create a File Share by using the Azure portal, PowerShell, or CLI and specify the maximum limit of the File Share.
    - Identify servers or on-premises virtual machines that will synchronize and download the files to the on-premises locations by using Azure File Sync.
    
    Although Azure File Sync is not a mandatory requirement to use Azure File Storage effectively, in the desired solution for this question, automatic synchronization, caching and reducing bandwidth costs, and eliminate dependency on Internet speeds. So, Azure File Sync must be used.

    First, deploy Azure File Sync agent on the on-premises resources you’ve prepped. Next, register the on-premises servers with the Storage Sync service to establish a trust relationship. Lastly, create a Sync Group to define the sync topology for a set of files. Endpoints within a sync group are kept in sync with each other.

    A sync group must contain one cloud endpoint, which represents an Azure file share and one or more server endpoints. Also, add the on-premises servers as the Server Endpoints.

    Azure ExpressRoute is not a mandatory requirement. Azure ExpressRoute is a feature that allows you to extend your on-premises networks into the Microsoft cloud over a private connection facilitated by a connectivity provider. So, this is NOT a mandatory requirement to make Azure File Storage and Azure File Sync.

    Windows Deployment Services (WDS) is not a mandatory requirement. WDS is a server role that allows you to deploy Windows operating systems remotely.

13. The Nutex Corporation wants to build apps on Azure. You are part of a Software Development operations team that must manage the operational aspects of developing apps. Which of the following statements about Azure App Service are TRUE? (Choose two)

    A)Only apps hosted in the Dedicated Computer Premium pricing tier or higher can be restored from snapshots.

    B)The Dedicated Compute Premium pricing tier of App Service runs dedicated Azure VMs on dedicated Azure Virtual Networks.

    C)If an app’s Memory quota is exceeded, the app is stopped.

    D)The auto swap feature is supported in web apps running in a Linux or Windows environment.

    E)The per-app scaling setting is available only for Shared, Premium, Premium V2, and Isolated pricing tiers.

    F)The Dedicated Compute Premium pricing tier of App Service can host up to 100 Hybrid connections.

    __*Anotacion:__

    The following statements are true:

    - The Dedicated Compute Premium pricing tier of App Service can host up to 100 hybrid connections.
    - Only apps hosted in the Dedicated Computer Premium pricing tier or higher can be restored from snapshots.
    
    Hybrid connections provide access from the app to an application endpoint in another network. They do not enable an alternate capability to access the application. Each hybrid connection corresponds to a single TCP host and port combination, which means that the hybrid connection endpoint can be on any application and any operating system when a single TCP listening port is accessed.

    The maximum allowed hybrid connections are as follows: Basic (5), Standard (10), Premium (100), and Isolated (200).

    Apps can be restored to the previous state based on one of the apps’ snapshots. Azure saves a snapshot of all apps automatically. Snapshots are incremental shadow copies and are more beneficial than regular backups. Snapshots eliminate issues such as storage size limitations, file copy errors due to file locks, and backup configuration issues.

    The following statements are not true:

    - If an app’s Memory quota is exceeded, the app is stopped.
    - The Dedicated Compute Premium pricing tier of App Service runs dedicated Azure VMs on dedicated Azure Virtual Networks.
    - The auto swap feature is supported in web apps running on a Linux or Windows environment.
    - The per-app scaling setting is available only in Shared, Premium, Premium V2, and Isolated pricing tiers.
    
    All Dedicated Compute pricing tiers run apps on dedicated Azure VMs. Apps in the same App Service plan share compute resources for that plan. The higher tiers can scale-out more VM instances than lower tiers.

    The Isolated pricing tier provides network isolation by running dedicated Azure VMs on dedicated Azure Virtual Networks. It provides compute isolation to the apps and the maximum scale-out capabilities.

    The auto swap feature is supported in web apps running in a Windows environment only. Auto swap should be used where the app is to be deployed continuously with zero cold starts and zero downtime for app users. Auto swap is enabled from a slot into production every time the code changes are pushed to that slot. App Service automatically swaps the app into production after it has warmed up in the source slot.

    The per-app scaling setting is available for Standard, Premium, Premium V2, and Isolated pricing tiers, not Shared or Free tier. Per-app scaling can be enabled at the level of an App Service plan to allow for scaling an app independently from the App Service plan that hosts it. This way, an App Service plan can be scaled to six instances, for example, but an app can be set to use only three.

    If an app’s Memory quota is exceeded, the app is only restarted. The quotas for apps are CPU (short), CPU (Day), Memory, Bandwidth, and Filesystem. If an app exceeds the CPU (short), CPU (Day), or Bandwidth quota, the app is stopped until the quota resets and all incoming requests result in an HTTP 403 error. If the Filesystem quota is exceeded, any write operation fails. Write operation failures include writes to logs.

14. You are part of the IT team at the Nutex Corporation. Your management has triggered an initiative to reduce the costs with Azure resources. You need to reduce storage costs for blob data. You propose using Azure Hybrid Benefit. Which of the following are true regarding Azure Hybrid Benefit? Choose two.

    A)Eligible licenses are SQL Server, Exchange Server, and Windows Server with active Software Assurance

    B)Allows you to use Azure cloud licenses with on-premises servers.

    C)Allows you to use on-premises licenses with servers in Azure.

    D)Eligible licenses are SQL Server, and Windows Server with active Software Assurance

    E)End-of-support software versions are not eligible
    
    __*Anotacion:__

    The following are correct:

    - Eligible licenses are SQL Server, Exchange Server, and Windows Server with active Software Assurance
    - Allows you to use on-premises licenses with servers in Azure.
    
    Azure Hybrid Benefit saves you money by using existing on-premises licenses with active Software Assurance on a virtual machine in Azure. Azure Hybrid Benefit does allow you to use a cloud-based license with an on-premises server.

    Windows Server and SQL Server licenses with active Software Assurance are eligible for Azure Hybrid Benefit. Exchange Server is not eligible. However, RedHat and SuSe Linux subscriptions are eligible.

    End-of-support software versions are eligible for Azure Hybrid Benefit.

15. The Nutex Corporation plans to add a large amount of data from a company that it purchased. It plans on using Azure Blob storage. Match the Attribute or Setting for Azure Blob storage with its appropriate description.

    Blobfuse -> A virtual file systems driver that accesses the block blob data in the Storage account through the Linux file system

    Azure Data Box -> A service used to transfer on-premises dara ro Blob storage when large datasets or network constrains do not allow to upload data over the wire

    Page -> A type of Blob that stores VHD files and serve as disks for Azure virtual machines

    Cool -> An Access tier that stores Blobs of dara that is NOT accessed frequently and stored for at least 30 days.

    AzCopy -> A command-line tool for Windows and Linux to copy data to and from Blob storage, across containers, or accross storage accounts

    __*Anotacion:__ 
    Blobfuse is a virtual file system driver for Azure Blob storage. You can use Blobfuse to access your existing block blob data in your Storage account through the Linux file system. Blobfuse can be installed on Ubuntu 14.04, 16.04, and 18.04 editions.

    Azure Data Box transfers on-premises data to Blob storage when large datasets or network constraints make uploading data over the wire unrealistic. One of Azure Data Box Disk, Azure Data Box, or Azure Data Box Heavy devices from Microsoft can be used, depending on the size of data to be transferred. You can then copy your data to those devices and ship them back to Microsoft to be uploaded into Blob storage.

    The three types of Blobs in Azure Blob Storage are Block, Append, and Page. Block blobs store text and binary data, up to about 4.7 TB. Block blobs are made up of blocks of data that can be managed individually. Append blobs are made up of blocks like block blobs but are optimized for append operations. Page blobs store random access files up to 8 TB in size. Page blobs store virtual hard drive (VHD) files and serve as disks for virtual machines.

    The three Access tiers available with Azure Blob storage are Hot, Cool, and Archive. Hot is optimized for storing data that is accessed frequently. Cool is optimized for storing data that is infrequently accessed and stored for at least 30 days. Archive is optimized for storing data that is rarely accessed and stored for at least 180 days with flexible latency requirements.

    AzCopy is a command-line tool that copies data to and from Blob storage, across containers, or across storage accounts. AzCopy executable files are available for Windows, Linus, and macOS computers.

16. The Nutex Corporation plans to provide app management and monitoring services to some companies. The management wants you to discover ways to obtain customer-level usage and billing details. Which of the following statements about Azure Subscriptions are TRUE? (Choose three.)

    A)Azure subscriptions help customers monitor the billing and usage of data granularly.
    B)Each subscription can trust up to three Azure AD directories.
    C)Multiple subscriptions can trust the same Azure AD directory, but each subscription can only trust a single directory.
    D)The accidental deletion of an Azure subscription by an admin user cannot be reversed.
    E)An Azure subscription can be transferred to an Azure account in another country.
    F)An Azure subscription cannot contain multiple resource groups.
    Explanation

    The following statements are true:

    Azure subscriptions help customers monitor the usage and billing data granularly.
    Multiple subscriptions can trust the same Azure AD directory. However, each subscription can only trust one Azure AD directory.
    An Azure subscription can be transferred to an Azure account in another country.
    To monitor the usage and billing data granularly, customers can obtain usage and billing data by resource groups as well as others. The following shows you the different properties that can be used to segment costs.

    (Property -> When to use)
    
    - Availability zones	Break down AWS costs by availability zone.

    - Billing period	Break down PAYG costs by the month they were (or will be) invoiced.

    - Charge type -> Break down usage, purchase, refund, and unused reservation costs.

    - Department -> Break down costs by EA department.

    - Enrollment account -> Break down costs by EA account owner.

    - Frequency -> Break down usage-based, one-time, and recurring costs.

    - Invoice ID -> Break down costs by billed invoice.

    - Meter -> Break down costs by usage meter.

    - Operation -> Break down AWS costs by operation.

    - Pricing model -> Break costs down by on-demand, reservation, or spot usage.

    - Provider -> Break down costs by AWS and Azure.

    - Publisher type -> Break down AWS, Azure, and Marketplace costs.

    - Reservation -> Break down costs by reservation.

    - Resource -> Break down costs by resource.

    - Resource group -> Break down costs by resource group.

    - Resource type -> Break down costs by resource type.

    - Resource location -> Break down costs by location or region.

    - Service name or Meter category -> Break down cost by Azure service.

    - Service tier or Meter subcategory -> Break down cost by Azure usage meter subclassification.

    - Subscription -> Break down costs by Azure subscription and AWS linked account.

    - Tag -> Break down costs by tag values for a specific tag key.
    
    An Azure subscription has a trust relationship with Azure Active Directory (Azure AD). Azure AD authenticates users, services, and devices of the Azure subscriptions that are added to the AD directory.

    Cross-country transfers cannot be performed in the Azure portal. To transfer a subscription across countries, customers must contact the Microsoft Support team.

    Azure subscriptions allow multiple resource groups to be added. Azure provides four levels of scope: management groups, subscriptions, resource groups, and resources. Management settings can be applied at any of these levels of scope. The level you select determines how widely the setting is used. Lower levels inherit settings from higher levels. For example, when you apply a policy to the subscription, the policy is applied to all resource groups and resources in your subscription. When you apply a policy on the resource group, that policy is applied to the resource group and all its resources.

    Azure subscriptions can be reactivated if they are deleted by another admin user. If you are the Account Administrator and accidentally delete an individual subscription with pay-as-you-go rates, you can reactivate it in the Account Center.

17. The Nutex Corporation wants to migrate its on-premises applications and services to Azure. You are the analyst tasked to investigate the benefits of this migration to Azure. Which of the following statements about the Azure TCO Calculator is TRUE?

    A)Azure TCO Calculator calculates on-premises infrastructure costs based on three criteria: hardware, software, and networking costs.

    B)The Azure TCO Calculator application can be downloaded from the Azure website.

    C)Customers interested in migrating from on-premises deployments to Azure must focus their calculations on the Compute, Storage, and Network requirements on Azure in order to evaluate the costs accurately.

    D)The Azure Pipelines service is not available with the Azure Government offering.

    E)Azure TCO Calculator primarily evaluates the total cost incurred to migrate on-premises application workloads to Microsoft Azure.
    
    __*Anotacion:__

    Customers interested in migrating from on-premises deployments to Azure must focus their calculations on the Compute, Storage, and Network requirements on Azure in order to evaluate the costs accurately.

    Unfortunately, not all cloud TCO calculations are accurate enough to let you make an informed decision. Many are ballpark estimates because they have failed to account for all performance metrics essential for rightsizing, and they may rely on metrics that have been averaged instead of considering peaks and valleys. These imprecise assessment methods may cause you to estimate a configuration scenario that is not suited to your performance requirements.

    Metrics such as peak CPU utilization, allocated and peak RAM usage, observed storage on-premises (capacity and current occupancy), disk IOPS and bandwidth, throughput, and usage patterns must be analyzed. This approach focuses on three areas: Compute, Storage, and Network.

    The following statements are not true:

    - Azure TCO Calculator primarily evaluates the total cost incurred to migrate on-premises application workloads to Microsoft Azure.
    - Azure TCO Calculator calculates on-premises infrastructure costs based on three criteria: hardware, software, and networking costs.
    - The Azure TCO Calculator application can be downloaded from the Azure website.
    
    Microsoft’s Azure Total Cost of Ownership (TCO) Calculator allows you to evaluate potential cost savings if you migrate on-premises application workloads to Microsoft Azure. You must specify the details of your existing infrastructure and various cost assumptions that you want the tool to work with. You receive a report that shows your on-premises costs compared to Microsoft Azure costs. While you may get a report of cost savings, TCO will NOT give you the total costs incurred to migrate on-premises application workloads to Microsoft Azure. TCO may allow you to compare costs on databases, storage, and networking, but does NOT calculate the labor rate that may be involved with the migration.

    The Azure TCO Calculator calculates the on-premises infrastructure costs based on more than three criteria. It takes the following costs into consideration:

    - Hardware
    - Software (for Windows as an OS)
    - Electricity
    - Data center
    - Networking
    - Disk storage
    - IT labor
    - Virtualization
    - Azure TCO Calculator is an online calculator that can be accessed on the Azure website. Customers can use it to check their TCO but only the results can be downloaded.

    At the time of this writing, Azure Pipelines service is not available with the Azure Government offering.

18. Which of the following are examples of SaaS? (Choose two.)

    A)Google Compute Engine

    B)Microsoft Azure

    C)Google Apps

    D)Salesforce

    E)Amazon Web Services Elastic Beanstalk

    __*Anotacion:__ 

    Google Apps and Salesforce are examples of Software as a Service (SaaS). With SaaS, the customer uses software for a fee from a cloud provider. Google Apps and Salesforce run in the cloud and do not require software installed on the client. Other examples of SaaS are web-based mail services, such as Hotmail or Yahoo Mail.

    Microsoft Azure and Amazon Web Service Elastic Beanstalk are example of Platform as a Service (PaaS). PaaS is a cloud category that a customer uses to create their own applications and manage those applications.

    Google Compute Engine is an example of Infrastructure as a Service (IaaS). IaaS is a cloud category that provides customers with network infrastructure, physical computing resources, data partitioning, scaling, security, and backup.

19. Your organization has an on-premises infrastructure. You have recently deployed Windows virtual file servers in an Azure virtual network. You want to import 50 TB of data from an on-premises file server and plan to use Azure Data Box. In which of the following scenarios can you use Azure Data Box to import data to Azure? (Choose three.)

    A)Periodic Uploads

    B)Security requirements

    C)Onetime Migration

    D)Initial Bulk Transfer

    E)Disaster Recovery

    F)Migrate back to on-premises or to another cloud service provider

    __*Anotacion:__

    Azure Data Box is a cloud solution that allows you to send terabytes of data into and out of Azure in a quick and reliable way. Azure Data Box is a Microsoft proprietary solution that imports and exports data from Azure. You can set up the device using the local web user interface.

    Data Box is best suited to transfer data larger than 40 TB in scenarios with no to limited network connectivity. Below are some of the scenarios where Data Box can be used to import data to Azure.

    - Onetime Migration – when you want to move a large amount of on-premises data to Azure. For example, migrating offline tape media to create an online media library, migrating your SQL Servers, VMs, and applications, and moving historical data for in-depth analysis and reporting using HDInsight.
    - Initial Bulk Transfer – when you want to move an initial large historical backup to Azure. Once the process is complete, the incremental data is transferred via network to Microsoft Azure Storage.
    - Periodic Uploads – when you want to move a large amount of data periodically to Azure.
    
    Disaster Recovery, security requirements, and migrating back to on-premises or to another cloud service provider are not the scenarios that use Data Box to import data to Azure. These are useful when using Data Box to export data from Azure.

    - Disaster Recovery – when you need to move data from Azure to an on-premises network. In a typical scenario, a large amount of Azure data is exported to a data box, which is shipped to an on-premises datacenter where the data is restored.
    - Security requirements – when you have to move data out of Azure due to government or security requirements. For example, Azure Storage is available in Secret and Top Secret clouds, and you want to export data out of Azure.
    - Migrate back to on-premises or to another cloud service provider – when you no longer need data in Azure or change cloud service providers.

20. Your company hosts a website. Due to web traffic spikes that were caused by ads which typically ran for three days, the company has over-purchased capacity in advance of running ads for the next month. Which benefit of Azure Cloud Services supports cost management for this type of usage pattern?

    A)high availability

    B)elasticity

    C)load balancing

    D)high latency

    __*Anotacion:__

    Elasticity in Azure could allow the website to scale rapidly, commensurate with demand, due to traffic spikes caused by ads. Microsoft Azure could allocate resources when the spike occurs and deallocate the resources when the traffic spike passes. The elasticity feature makes the capabilities of the cloud appear unlimited and can be allocated in any quantity for any time length.

    High latency would not be a feature that would be used in this scenario. Network latency is the time it takes for a packet to traverse the network from the sender to the receiver. The issue in the scenario is a spike in traffic, not a delay in traffic traversing the network.

    Load balancing would not be a feature that would be used in this scenario. Load balancing distributes incoming network traffic across a group of servers known as a server pool. Load balancing can increase performance by decreasing the burden that is placed on a server. Load balancing is designed to increase reliability over time, but it would not be as effective in this scenario as elasticity, which allocates resources on demand.

    High availability would not be a feature that would be used in this scenario. The high-availability feature allows groups of computers to support applications with little or no downtime. High availability may not protect against spikes, but elasticity can.

21. During your research to move from an on-premises setup to the Azure cloud, you learn that Microsoft's physical infrastructure spans 60 regions across 140 countries and consists of hardware and systems located across multiple datacenters. Which approach does Microsoft use in its datacenters to be carbon negative, create a resilient supply chain, and anticipate growth?

    A)Azure Security and Resiliency Architecture (ASRA)

    B)Digital twins

    C)Blockchain

    D)Circular Centers

    __*Anotacion:__

    In the Microsoft Circular Centers program, when the hardware’s life cycle is complete, it is decommissioned and repurposed. This action allows the servers and server components to be reused elsewhere in the Microsoft organization or donated to other organizations. Circular Centers allows Microsoft to reuse 90% of the servers and their components, ensuring that Microsoft can achieve its goal of being carbon negative. It also allows parts to be available, which improves the supply chain.

    You should not choose blockchain. The blockchain is an accounting of transactions in an electronic ledger. The ledger is duplicated and distributed by the computer systems on the blockchain to ensure that it makes it impossible to corrupt or modify. While blockchain can ensure that resources are used and accounted for, it has a substantial carbon footprint as currently practiced and is not a carbon-negative technology.

    You should not choose digital twins. A digital twin is a virtual representation of a physical object or process that serves as the real-time digital counterpart. You could create a virtual machine of a server in the cloud that represents a physical server located on-premises. While digital twins help a datacenter with the supply chain and anticipate growth, they do not help a datacenter to become carbon negative.

    You should not choose Azure Security and Resiliency Architecture (ASRA). This is the approach that Microsoft uses to ensure resiliency consistently and to provide high security across the Microsoft cloud infrastructure supply chain. This approach will improve the supply chain, but it does not help a datacenter become carbon negative.

22. You plan to deploy an Azure cloud with the following divisions:
    - Two divisions in North America, one located in Atlanta, GA, and the other in Montreal, Québec.
    - Two divisions in Europe, one located in London and the other in Paris.
    Each division will have its own administrator. Each division administrator can manage the Azure resources used by their respective division. How many Azure Active Directory (Azure AD) directories will this solution require?

    A)2
    
    B)4

    C)3

    D)1
    
    __*Anotacion:__ 

    While it is possible to create separate Azure Active Directory (Azure AD) directories for each division, there is no need for all that extra administrative effort. A single Azure AD can support the creation of multiple Azure administrative domains. A domain can be created for each division. The central administrator could:

    1. Create an administrative unit for each division.
    2. Populate the administrative unit with only students and staff within the division.
    3. Create a role with administrative permissions over only Azure AD users in each administrative unit.
    4. Add the division IT team to the role, along with its scope.

23. You are a system administrator for Nutex Corporation. Your business-critical web application is experiencing intermittent errors. You are unable to find the cause of the issue. You plan to use Azure Monitor to determine the root cause of the issue. Which of the following should you use for this?

    A)Azure Log Analytics

    B)Azure Databricks

    C)Azure Functions

    D)Azure Advisor

    __*Anotacion:__

    Azure Log Analytics will help you drill into the monitoring data for troubleshooting and deep diagnostics. It is a tool located in the Azure portal used for editing log queries and interactively analyzing their results. You can get a set of given records by running a simple query and then sort, filter, and analyze them. You can also use advanced queries to perform statistical analyses and visualize the results in a chart to identify a particular trend.

    Azure Databricks will not help you drill into the monitoring data for troubleshooting and deep diagnostics. Azure Databricks is a data analytics platform provided by Microsoft for the Azure cloud services platform. It has three environments for developing data-intensive applications:

    - Databricks Machine Learning
    - Databricks SQL
    - Databricks Data Science and Engineering
    
    Azure Functions will not help you drill into the monitoring data for troubleshooting and deep diagnostics. An Azure function is a serverless solution where you have to write less code, maintain less infrastructure, and save on costs. Azure Functions provides "compute on-demand" in two ways. First, it helps you to implement your system's logic into readily available blocks of code. Second, as there is an increase in requests, it meets the necessary demand with the needed resources and function instances.

    Azure Advisor will not help you drill into the monitoring data for troubleshooting and deep diagnostics. Azure Advisor is a Microsoft-provided cloud consultant that enables you to follow best practices to optimize your Azure deployments. It analyzes your resource configurations and provides recommendations for solutions that can help you improve the cost-effectiveness, performance, reliability, and security of Azure resources.

______________________
______________________
______________________

# Video. Preparación Examen AZ 900 Teoria y Preguntas

## Video 1

1. Your company plans to migrate all its network resources to Azure. What should you create first of all?

    __a) a subscription__

    b) a resourde group

    c) a virtual network

    d) a management group

2. A platform as services (PaaS) solution that hosts web apps in Azure provides full control of the operating systems that host applications.

    a) Yes

    __b) No__

3. A platform as services (PaaS) solution that hosts web apps in Azure provides the ability to scale the platform automatically.

    __a) Yes__

    b) No

4. A platform as services (PaaS) solution that hosts web apps in Azure provides professional development services to continuously add features to custom applications.

    __a) Yes__

    b) No 

5. You plan to migrate a web application for Azure. The web application is accessed by external users. You need to recomend a cloud deployment solution to minimize the amount of administrative effort used to manage the web application. What should you include in the recommendation?

    a) Software as a Service (Saas)

    __b) Platform as a Service (Paas)__

    c) Infrastructure as a Service (Iaas)

    d) Database as a Service (Daas)

6. An Azure web app that queries an on-premises Microsoft SQL server is an example of a _________ cloud.

    __a) hybrid__

    b) multi-vendor

    c) private

    d) public

7. Match

    __Public Cloud__ - No required capital expenditure

    __Private Cloud__ - Provides complete control over security

    __Hybrid Cloud__ - Provides a choice to use on-premises or cloud-based resources.

8. You have 50 virtual machines hosted on-premises and 50 virtual machines hosted in Azure. The on-premises virtual machines and the Azure virtual machines connect to each other. Which type of cloud model is this?

    __a) hybrid__

    b) private 

    c) public

9. To which cloud models can you deploy physical servers?

    __a) private cloud and hybrid cloud only__

    b) private cloud only

    c) private cloud, and hybrid cloud and public cloud

    d) hybrid cloud only
 
10. An Azure resource can have multiple Delete locks.

    __a) Yes__

    b) No

11. An Azure resource inherits locks from its resource group.

    __a) Yes__

    b) No

12. If an Azure resource has a Read-only lock, yo can add a Delete lock to the resource.

    __a) Yes__

    b) No

    __*Anotacion:__ Delete es el mas restrictivo, no se podria hacer al revés, pero sí así.

13. An organization that hosts its infrastructure _________ no longer requires a data center.

    a) in a private cloud

    b) in a hybrid cloud

    __c) in a public cloud__

    d) on a Hyper-V host
    
14. You need to prevent the accidentar deletion of the resources in RG1. Which setting should you use? To answer, select the appropiate setting in the answer area.

    a) Quickstart

    b) Resource costs

    c) Deployments

    d) Policies

    e) Properties

    __f) Locks__

    g) Automation script

15. An Azure Policy initiative definition is a _______________ .

    __a) collection of policy definitions.__

    b) Collection of Azure Policy definition assignments.

    c) group of Azure Blueprints definitions.

    d) group of role-based access control (RBAC) role assignments.

16. Your company has 10 departments. The company plans to implement an Azure environment. You need to ensure that each department can use a different payment option for the Azure services it consumes. What should you create for each department?

    a) a reservation

    __b) a subscription__

    c) a resource group

    d) a container instance

    __*Anotacion:__ una subscripcion por departamento. 

17. __________ provide organizations with the ability to manage the compliance of Azure resources across multiple subscriptions.

    a) Resource groups

    b) Management groups

    __c) Azure policies__

    d) Azure app Service plans

18. You can create a resource group inside of an other resource group.

    a) Yes

    __b) No__

    __*Anotacion:__ No existe herencia de grupos de recursos

19. An Azure virtual machine can be in multiple resource groups.

    a) Yes

    __b) No__

20. A resource group can contain resources from multiple Azure regions.21. You have a resource group named RG1. You need to prevent the creation of virtual machines only in RG1. The solution must ensure that other objects can be created in RG1. What should you use?

    a) a lock

    b) an Azure role

    c) a tag

    __d) an Azure policy__

    __*Anotacion:__ lock es para bloquear que un elemento se pueda eliminar o modificar, no para impedir la creacion de recursos. Con la politica podemos controlar qué queremos permitir o denegar en nuestro entorno.

22. With software as a service (SaaS), you must apply software updates.

    a) Yes

    __b) No__

24. With infrastructure as a service (IaaS), you must install the software you want to use.

    __a) Yes__

    b) No

25. Azure Backup is an example of platform as a service (PaaS).

    __a) Yes__

    b) No

26. Your company has an Azure subscription that contains resources in several regions. You need to ensure that administrators can only create resources in those reions. What should you use?

    a) a read-only lock

    __b) an Azure policy__

    c) a management group

    d) a reservation

27. You plan to provision Infrastructure as a Service (Iaas) resources in Azure. Which resource is an example of Iaas?

    a) an Azure web app

    __b) an Azure virtual machine__

    c) an Azure logic app

    d) an Azure SQL database

28. Your company has an Azure subscription that contains resources in several regions. A company policy states that administratos must only be allowed to create additionar Azure in a region in the country where their office is located. You need to create the Azure resource that must be used to meet the policy requirement. What should you create?

    a) a read-only lock

    __b) an Azure policy__

    c) a management group

    d) a reservation
    
29. In which type of cloud model are all the hardware resources owned by a third-party and shared between multiple tenants?

    a) private

    b) hybrid

    __c) public__
    
30. Your company plans to migrate to Azure. The company has several departments. All the Azure resources used by each department will be managed by a department administrator. What are *two* possible techniques to segment Azure for the departments? Each correct answer presents a complete solution. NOTE: Each correct selection is worth one point.

    __a) multiple subscriptions__

    b) multiple Azure Active Directory (Azure AD) directories

    c) multiple regions

    __d) multiple resource groups__

______________________

## Video 2

1. Azure provides flexibility between capital expenditure (CapEx) and operational expenditure (OpEx).
    
    __a) Yes__

    b) No

2. If you create two Azure virtual machines that use the B2S size, each virtual machine will always generate the same monthly costs.
    
    a) Yes

    __b) No__

    __*Anotacion:__ Pueden ser dos máquinas virtuales que utilicen discos de distintos tamaños y por tanto el coste será distinto.

3. When an Azure virtual machine is stopped, you continue to pay storage costs associated to the virtual machine.
    
    __a) Yes__

    b) No

    __*Anotacion:__ Cuando se detiene una máquina virtual, no paga por la máquina, pero sí por los costos de almacenamiento asociados a la máquina virtual. Los costos de almacenamiento más comunes corresponden a discos conectados a las máquinas vituales. También hay otros costos de almacenamiento asociados a una máquina virtual, como el almacenamiento de datos de diagnóstico y copias de seguridad de máquinas virtuales.

4. You have 1000 virtual machines hosted on the Hyper-V hostos in a data center. You plan to migrate all the virtual machines to an Azure pay-as-you-go subscription. You need to identify which expenditure model to use for the planned Azure solution. Which expenditure model should you identify?

    __a) operational__

    b) elastic

    c) capital

    d) scalable

5. Azure Pay-As-You-Go pricing is an example of CapEx.

    a) Yes

    __b) No__

6. Paying electricity for your data center is an example of OpEx.

    a) Yes

    __b) No__

7. Deploying your own datacenter is an example of CapEx.

    __a) Yes__

    b) No

8. Build a data center infrastructure is an example of operational expenditure (OpEx) costs.

    a) Yes

    __b) No__

9. Monthly salaries for technical personnal are an example of operational expenditure (OpEx) costos

    __a) Yes__

    b) No

10. Leasing software is an example of operational expenditure (OpEx) costs.

    __a) Yes__

    b) No

11. You plan to deploy 20 virtual machines to an Azure environment. To ensure that a virtual machine named VM1 cannot connect to the ohter virtual machines, VM1 must _______________________________ .

    __a) be deployed to a separate virtual network.__

    b) run a different operating system than the other virtual machines.

    c) be deployed to a separate resource group.

    d) have two network interfaces

12. You need to ensure that the services running on the virtual machines ares available if a single data center fails. 

    1) Solution: You deploy the virtual machines to two or more resource groups. Does this meet the goal?

        a) Yes

        __b) No__

    2) Solution: You deploy the virtual machines to two or more regions. Does this meet the goal?

        a) Yes

        __b) No__

    3) Solution: You deploy the virtual machins to two or more availability zones.  Does this meet the goal?

        a) Yes

        __b) No__

13. Availability zones can be implemented in all Azure regions.

    a) Yes

    __b) No__

14. Only virtual machines that run Windows Server can be created in availability zones.

    a) Yes

    __b) No__

15. Availability zones are used to replicate data and applications to multiple regions.

    a) Yes

    __b) No__

16. North America is represented by a single Azure region.

    a) Yes

    __b) No__

17. Every Azure region has multiple datacenters.

    __a) Yes__

    b) No

18. Data transfers between Azure services located in different Azure regions are always free.

    a) Yes

    __b) No__

    __*Anotacion:__ La transferencia de datos entrantes es gratuita, pero la transferencia de datos salientes tiene una tarifa.

19. You can use Availability Zones in Azure to protect Azure virtual machines from a datacenter failure.

    __a) Yes__

    b) No

20. You can use Availability Zones in Azure to protect Azure virtual machines from a region failure.

    a) Yes

    __b) No__

21. You can use Availability Zones in Azure to protect Azure managed disks from a datacenter failure.

    __a) Yes__

    b) No

22. An Availability Zone in Azure has physically separate locations _________________.

    a) across two continents

    __b) within a single Azure region__

    c) within multiple Azure regions

    d) within a single Azure datacenter
    
23. You need to identify the type of failure for which an Azure Availability Zone can be used to protect access to Azure services. What should you identify?

    a) a physical server failure

    b) an Azure region failure

    c) a storage failure

    __d) an Azure datacenter failure__
    
24. Data that is stored in an Azure Storage Account automatically has at least three copies.

    __a) Yes__

    b) No
    
25. All data that is copied to an Azure Storage account is backed up automatically to another Azure dataceneter.

    a) Yes

    __b) No__

    __*Anotacion:__ deberiamos seleccionar redundancia por zonas para que esto ocurra.
    
26. An Azure Storage account can contain up to 2TB of data and up to one million files.

    a) Yes

    __b) No__

    __*Anotacion:__ El limite de almacenamiento actual es de 2PB para EE.UU. y Europa, y de 500TB para el resto del mundo (incluido Reino Unido) sin límite de cantidad de archivos.
    
27. A company wants to try out some services which Azure is offering in Public Preview. Do the services in Public PReview in Azure come with an SLA?

    a) True

    __b) False__
    
28. A company wants to set up resources in Azure. They want a way to manage identities in Azure. Which of the following is used as an Identity Management solution in Azure?

    __a) Azure AD__

    b) Azure Advisor

    c) Azure Security Center

    d) Azure  Monitor
    
