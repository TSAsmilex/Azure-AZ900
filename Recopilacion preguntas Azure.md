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

    b) You rent compute power and storage from someone else's datacenter. 

    c) You rent physical hardware such as compute power and storage and maintain them within your own datacenter. (Esta NO)

    __d) You can immediately stop paying for resources that are no longer needed.__

    __Anotación:__ (__d__)You can treat cloud resources like you would resources in your own datacenter. When you are finished using them, you give them back. You are only billed for what you use. (__c__) The cloud provider takes care of maintaining the underlying infrastructure for you. 

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

### Primer intento

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

    __B)No__

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
    
    __C)Physically separate locations within an Azure region__
    
    D)A discrete market typically containing two or more regions that preserves data residency and compliance boundaries
    
    __*Anotacion:__

    Availability zones are physically separate locations within an Azure region. Each availability zone has one or more datacenters. Each datacenter is equipped with independent power, cooling, and networking. Availability zones protect your applications and data from datacenter failures.

    An availability zone is not a discrete market typically containing two or more regions that preserves data residency and compliance boundaries. That describes a geography. A geography is a unique market that contains two or more regions that stores data in the regions according to the compliance boundaries of the regions.

    An availability zone is not a geographical area containing at least one, but potentially multiple, datacenters that are in close proximity and networked together with a low-latency network. That describes a region. A region is a geographical area containing one or more datacenters networked together with a low-latency network and are in close proximity.

    An availability zone is not a way for you to ensure that your application remains online if a high-impact maintenance event is required, or a hardware failure occurs. That can be done with an availability set. Availability sets logically group resources so that Azure can ensure that VM resources are isolated from each other when they are in an Azure datacenter. Availability sets allow your application to remain online if a hardware failure occurs or a maintenance event is required.

7. You need to monitor the VMs running in your department’s resource group. These VMs run several applications that query a backend database. Department members create spreadsheets from the data that is queried from the database. You need to respond quickly to alerts and take action on those alerts by using Azure CLI or PowerShell commands. You will be attending a two-day music festival over the weekend. You plan to take only your Android phone. However, there are no team members that can take over your monitoring activities. What can you do to ensure that monitoring activities continue?

    A)Download the Microsoft 365 Admin app
    
    __B)Download the Azure mobile app__
    
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

    __C)Azure Log Analytics__

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

    __A)Use the Total Cost of Ownership (TCO) calculator as a starting point.__

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
    
    __C)The automatic creation of Azure resources__

    D)To act as a broker with message queues and publish-subscribe topics (in a namespace).
    
    __*Anotacion:__ 

    Azure Resource Manager templates are JavaScript Object Notation (JSON) files that specify the infrastructure and configuration for your project. They can be used to automate the creation of resources. An ARM template can create identical resources in multiple locations.

    Organizing resources and subscriptions is better done through the use of management groups. Azure Management Groups can be used to create an effective and efficient hierarchy to manage Azure subscriptions and resources.

    The Azure Service bus, not an ARM template, is a broker with message queues and publish-subscribe topics (in a namespace).

    Deploying predictive analytics is better done with the Azure Machine Learning Studio. This is a drag and drop tool that allows you to build, test, and deploy predictive analytics using AI.

12. Your organization has offices in multiple locations in France. Teams are distributed across the country. Your organization uses a private cloud storage solution to synchronize work-related data and make it available to employees across locations. Employees must manually synchronize the data on the cloud with that on their computers. You are asked to plan for a solution that automatically synchronizes data, reduces costs and eliminates the dependency on Internet speeds to synchronize data. You plan to use Azure File Storage. Which of the following are mandatory requirements to implement Azure File Storage and accomplish the goal of the plan? (Select all that apply.)

    __A)Prep on-premises servers that meet the requirements to deploy Azure File Sync.__

    __B)Deploy Azure File Sync on the on-premises servers.__

    C)Install Windows Deployment Services on-premises

    __D)Create an Azure File Share on the Azure portal.__

    __E)Register the on-premises servers with the Storage Sync Service.__

    F)Create ExpressRoute circuit(s) for the Azure File Sync solution.

    __G)Create a Sync Group and add the on-premises servers as Server Endpoints on the Azure portal.__

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

    __A)Only apps hosted in the Dedicated Computer Premium pricing tier or higher can be restored from snapshots.__

    B)The Dedicated Compute Premium pricing tier of App Service runs dedicated Azure VMs on dedicated Azure Virtual Networks.

    C)If an app’s Memory quota is exceeded, the app is stopped.

    D)The auto swap feature is supported in web apps running in a Linux or Windows environment.

    E)The per-app scaling setting is available only for Shared, Premium, Premium V2, and Isolated pricing tiers.

    __F)The Dedicated Compute Premium pricing tier of App Service can host up to 100 Hybrid connections.__

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

    __A)Eligible licenses are SQL Server, Exchange Server, and Windows Server with active Software Assurance__

    B)Allows you to use Azure cloud licenses with on-premises servers.

    __C)Allows you to use on-premises licenses with servers in Azure.__

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

    __A)Azure subscriptions help customers monitor the billing and usage of data granularly.__

    B)Each subscription can trust up to three Azure AD directories.

    __C)Multiple subscriptions can trust the same Azure AD directory, but each subscription can only trust a single directory.__

    D)The accidental deletion of an Azure subscription by an admin user cannot be reversed.

    __E)An Azure subscription can be transferred to an Azure account in another country.__

    F)An Azure subscription cannot contain multiple resource groups.

    __*Anotacion:__

    The following statements are true:

    - Azure subscriptions help customers monitor the usage and billing data granularly.
    - Multiple subscriptions can trust the same Azure AD directory. However, each subscription can only trust one Azure AD directory.
    - An Azure subscription can be transferred to an Azure account in another country.
    
    To monitor the usage and billing data granularly, customers can obtain usage and billing data by resource groups as well as others. The following shows you the different properties that can be used to segment costs.

    (Property -> When to use)
    
    - Availability zones -> Break down AWS costs by availability zone.

    - Billing period -> Break down PAYG costs by the month they were (or will be) invoiced.

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

    __C)Customers interested in migrating from on-premises deployments to Azure must focus their calculations on the Compute, Storage, and Network requirements on Azure in order to evaluate the costs accurately.__

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

    __C)Google Apps__

    __D)Salesforce__

    E)Amazon Web Services Elastic Beanstalk

    __*Anotacion:__ 

    Google Apps and Salesforce are examples of Software as a Service (SaaS). With SaaS, the customer uses software for a fee from a cloud provider. Google Apps and Salesforce run in the cloud and do not require software installed on the client. Other examples of SaaS are web-based mail services, such as Hotmail or Yahoo Mail.

    Microsoft Azure and Amazon Web Service Elastic Beanstalk are example of Platform as a Service (PaaS). PaaS is a cloud category that a customer uses to create their own applications and manage those applications.

    Google Compute Engine is an example of Infrastructure as a Service (IaaS). IaaS is a cloud category that provides customers with network infrastructure, physical computing resources, data partitioning, scaling, security, and backup.

19. Your organization has an on-premises infrastructure. You have recently deployed Windows virtual file servers in an Azure virtual network. You want to import 50 TB of data from an on-premises file server and plan to use Azure Data Box. In which of the following scenarios can you use Azure Data Box to import data to Azure? (Choose three.)

    __A)Periodic Uploads__

    B)Security requirements

    __C)Onetime Migration__

    __D)Initial Bulk Transfer__

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

    __B)elasticity__

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

    __D)Circular Centers__

    __*Anotacion:__

    In the Microsoft Circular Centers program, when the hardware’s life cycle is complete, it is decommissioned and repurposed. This action allows the servers and server components to be reused elsewhere in the Microsoft organization or donated to other organizations. Circular Centers allows Microsoft to reuse 90% of the servers and their components, ensuring that Microsoft can achieve its goal of being carbon negative. It also allows parts to be available, which improves the supply chain.

    You should not choose blockchain. The blockchain is an accounting of transactions in an electronic ledger. The ledger is duplicated and distributed by the computer systems on the blockchain to ensure that it makes it impossible to corrupt or modify. While blockchain can ensure that resources are used and accounted for, it has a substantial carbon footprint as currently practiced and is not a carbon-negative technology.

    You should not choose digital twins. A digital twin is a virtual representation of a physical object or process that serves as the real-time digital counterpart. You could create a virtual machine of a server in the cloud that represents a physical server located on-premises. While digital twins help a datacenter with the supply chain and anticipate growth, they do not help a datacenter to become carbon negative.

    You should not choose Azure Security and Resiliency Architecture (ASRA). This is the approach that Microsoft uses to ensure resiliency consistently and to provide high security across the Microsoft cloud infrastructure supply chain. This approach will improve the supply chain, but it does not help a datacenter become carbon negative.

22. You plan to deploy an Azure cloud with the following divisions:
    - Two divisions in North America, one located in Atlanta, GA, and the other in Montreal, Québec.
    - Two divisions in Europe, one located in London and the other in Paris.
    Each division will have its own administrator. Each division administrator can manage the Azure resources used by their respective division. How many Azure Active Directory (Azure AD) directories will this solution require?

    A) 2
    
    B) 4

    C) 3

    __D) 1__
    
    __*Anotacion:__ 

    While it is possible to create separate Azure Active Directory (Azure AD) directories for each division, there is no need for all that extra administrative effort. A single Azure AD can support the creation of multiple Azure administrative domains. A domain can be created for each division. The central administrator could:

    1. Create an administrative unit for each division.
    2. Populate the administrative unit with only students and staff within the division.
    3. Create a role with administrative permissions over only Azure AD users in each administrative unit.
    4. Add the division IT team to the role, along with its scope.

23. You are a system administrator for Nutex Corporation. Your business-critical web application is experiencing intermittent errors. You are unable to find the cause of the issue. You plan to use Azure Monitor to determine the root cause of the issue. Which of the following should you use for this?

    __A)Azure Log Analytics__

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

24. You are a system administrator for Nutex Corporation. You have hosted several web applications in the Azure cloud and want to monitor the performance of the applications and be notified whenever an issue arises. Which of the following statements are TRUE or FALSE regarding Azure Monitor? Drag the statements to the appropriate choice.

    __*Anotacion:__

    Below are the correct answers for the given statements.

    (Statement -> True / False)
    Alerts in Azure Monitor proactively notify you of critical conditions and can take corrective actions. -> TRUE
    You cannot create alerts using Azure Monitor. -> FALSE
    To manage alert instances, users should have the Azure built-in roles of either Monitoring Contributor or Monitoring Reader. -> TRUE
    You can set the user response of an alert to specify where it is in the resolution process. -> TRUE
    You can only see all alert instances in all your Azure resources generated in the last seven days on the Alerts page -> FALSE
    
    Alerts in Azure Monitor proactively notify you of critical conditions and potentially attempt to take corrective action. Alerts help you identify and address issues before the users of the system notice them. You can create alerts using Azure Monitor. You can have action groups with alerts. You can specify an action for the alert that can run a remediation to respond to the alert.

    Log alert rules proactively identify issues from data in your workspace. Each alert rule is created based on a log query that automatically runs at regular intervals. The results are then inspected to determine if the alert should be created. You can create alerts based on metrics and logs.

    To manage alert instances, a user must have the Azure built-in role of either Monitoring Contributor or Monitoring Reader. These roles are supported at any Azure Resource Manager scope, from subscription to granular level assignments at a resource level.

    You can set the user response of an alert to specify where it is in the resolution process. An alert is created when the criteria specified in the alert rule is met. The status of the created alert is New. You can change the status when you acknowledge or close an alert.

    The Alert page provides the summary of alerts created in the past 24 hours. You can access alerts generated in the past 30 days, not seven days.

25. The web team of the Nutex Corporation is developing a new enterprise solution. They are using the newest technologies, and the functionality is divided into many independent parts that can be maintained, scaled, or updated independently. Locally they have installed Docker on Windows 10 machines. They need a development environment for testing in Azure. What will you recommend as the fastest and simplest way to deploy the development environment in Azure?

    A)Azure Kubernetes Service (AKS)
    
    B)Azure Functions
    
    __C)Azure Container Instances (ACI)__
    
    D)Azure Virtual Machine (VM)
    
    __*Anotacion:__

    You should choose Azure Container Instances (ACI). ACI offers the fastest and simplest way to create, start up, and run a container which can be used as a development environment. ACI takes less than 30 seconds to start a container in the best scenarios, faster than using App Services to create a development environment.

    You should not choose Azure Kubernetes Service (AKS). It is an orchestration service that requires a YAML file for configuration. It is more complex and for more enterprise solutions.

    You should not create an Azure VM to host containers. You have to install Docker on it and then work with it. Also, the installation process requires to ensure if Hyper-V features are enabled.

    You should not choose Azure Functions, because they are used for serverless processing, and not for hosting containers.

26. You need to propose a budget for cloud services, including selecting the correct cloud service model (PaaS, IaaS, or SaaS). To help coordinate services, you must understand which responsibilities belong to each type of cloud provider and which would belong to your organization. In each service scenario, which areas are the responsibility of the service provider? Move the appropriate responsibility to the appropriate category.

    Service Provider Responsability -> Physical security / Identity and access management / Network controls
    
    SaaS -> Physical security / Identity and access management / Networks controls
    
    PaaS -> Physical security / Identity and access management / Networks controls 

    IaaS -> Physical security

    On-premises -> 

    __*Anotacion:__

    Network controls are the responsibilities of the SaaS and PaaS vendors. The customer has no responsibility for network controls in a SaaS. However, they have some control over network controls in a PaaS. The customer has full responsibility of network controls for an IaaS since the customer can allocate resources such as routers, virtual networks, and gateways in an IaaS.

    Identity and access management is a shared responsibility between the vendor and the customer in a SaaS and PaaS. These vendors decide what type of access that the customer has to its software in a SaaS and platform in a PaaS and the customer can decide which users in their subscription can have access to the SaaS or PaaS.

    Physical security is the sole responsibility of the customer in an on-premises environment. Ensuring that the physical datacenter that houses the computing resources are secure is the cloud vendor’s responsibility with a SaaS, PaaS, or IaaS environment.

27. You are a system administrator for Nutex, Inc. Your organization has Sales, Finance, and Marketing departments. You have created 30 virtual machines, ten for each department, in the Azure virtual network. All machines are in a single subnet named SubnetA, having an IP address range of 10.0.0.0/24. You want to ensure that the virtual machines of each department do not communicate with the virtual machines of the other departments. What should you do? Place the steps in the correct order.

    __*Anotacion:__

    To ensure that the virtual machines of each department do not communicate with the virtual machines of the other departments, you should take the following actions:

    1. Create two more subnets named SubnetB and SubnetC with separate IP address ranges of 172.16.0.0/24 and 192.168.0.0/24.
    2. Move the Finance department VMs to SubnetB and the Marketing department VMs to SubnetC, and leave the Sales department VMs in SubnetA.
    3. Create a custom routing table to restrict communication between SubnetA, SubnetB, and SubnetC.
    
    You can set up your Azure virtual network with your own IP addressing. You can divide that IP address space into subnets and allocate part of the defined address space to each subnet, or you can provide separate subnets. An Azure virtual network provides the capability of isolation and segmentation, which can help provide more security and restrict communication between subnets.

    By default, Azure routes traffic between subnets on any connected virtual networks. You can create custom route tables that control how packets are routed between subnets.

    You should not install a firewall in the Azure virtual network. You should install Azure Firewall to control outbound network access from the Azure subnet.

    You should not install two network interface cards (NICs) on each virtual machine. Multiple NICs are installed to connect a subnet to multiple subnets. NICs connected to subnets within the virtual network can communicate with each other without extra configuration.

    You should not use virtual network peering between the subnets. By using virtual network peering, you can link separate virtual networks together. Peering enables network resources in each virtual network to communicate with each other.

    You should not configure service endpoints between the subnets. Service endpoints are used to connect other Azure resource types, such as SQL databases and storage accounts.

28. Microsoft Azure has datacenters in several locations in North America, Europe, and Asia. Which of the following statements describes an Azure region?

    A)A geographical area containing more than one datacenter in close proximity networked together with a low-latency network

    __B)A geographical area containing one or more datacenters networked together with a low-latency network and are in close proximity__

    C)A geographical area containing only one datacenter

    D)A geographical area containing at least one, but potentially multiple, datacenters that are in close proximity and networked together through the Internet

    __*Anotacion:__

    An Azure region is a geographical area containing one or more datacenters that are networked together with a low-latency network and are in close proximity.

    Azure has some special regions used for compliance or legal purposes:

    - Regions such as US DoD Central, US Gov Virginia, and US Gov Iowa are physical and logical network-isolated instances of Azure for use by US government agencies and their partners. They are operated by screened US persons. These regions contain additional compliance certifications.
    - Regions are available in Asia, China East, China North, and certain other countries through a unique partnership between Microsoft and 21Vianet. Microsoft does not directly maintain the datacenters.
    - Germany Central and Germany Northeast regions are available through a data trustee model whereby customer data remains in Germany under control of T-Systems, a German Telekom company, acting as the data trustee. Any user or enterprise that needs their data to reside in Germany can use this service.
    
    Azure has regional pairing, which are two or more regions within the same geography. The lone exception is Brazil South, which is not paired with another region in the same geography. With regional pairing, platform updates (planned maintenance) are performed so that only one paired region is updated at a time. At least one region in each pair will be prioritized for recovery in the event of an outage affecting multiple regions.

    Some services or virtual machine features are only available in certain regions.

29. Your company has purchased a subscription to Microsoft Azure. Microsoft Azure uses a consumption-based model. Which of the following are benefits of the consumption-based model? (Choose three.)

    __A)No upfront cost.__

    __B)No need to purchase and manage infrastructure.__

    __C)Pay for additional resources if and when needed.__

    D)Resources that are purchased but not used are credited back.

    __*Anotacion:__

    Cloud service providers such as Microsoft Azure operate on a consumption-based model. With Azure’s pay-as-you-go pricing, the consumer only pays for the resources that they use.

    Some of the benefits of the consumption-based model are:

    - No upfront costs
    - No need to purchase and manage infrastructure that may or may not be fully used
    - Pay for additional resources if and when needed.
    
    With a consumption-based model, you do not have to purchase services that you do not need or may not use. Since the consumption-based model is on a pay-as-you-go basis, there is no need to issue credit for resources not used.

30. As an Azure administrator, you are required to enable multi-factor authentication (MFA) only for applications of the IT department. How should you implement this strategy?

    A)Azure Identity Protection

    __B)Azure Conditional Access policy__

    C)Azure Identity Hub

    D)Azure AD Connect

    __*Anotacion:__

    You should use an Azure Conditional Access policy. As shown in the graphics below, with a Conditional Access policy you can choose multiple cloud apps for which you will enable multi-factor authentication.

31. Your company has noticed that storage costs have decreased significantly over the past few years due to cloud providers’ ability to purchase larger amounts of storage at significant discounts. These savings have allowed your company to purchase additional cloud resources. Which cloud feature is represented in this scenario?

    __A)Economy of scale__

    B)High availability

    C)Fault tolerance

    D)Elasticity

    E)Disaster recovery

    F)Scalability

    G)Agility

    __*Anotacion:__

    You would choose economy of scale. The concept of economy of scale is the ability to do business cheaper and more efficiently when operating on a larger scale, in comparison to operating on a smaller scale.

    You would not choose agility. Agility is the ability to react quickly. Cloud services can allocate and deallocate resources quickly. These are on-demand services that are provisioned in minutes. There is no manual intervention in provisioning or deprovisioning services.

    You would not choose elasticity. This feature increases or decreases resources as needed, but unlike scalability, elasticity is done automatically. Elastic resources are based on the current needs and resources are added or removed dynamically to meet those needs, from the most advantageous geographic location. A distinction between scalability and elasticity is that elasticity is done automatically.

    You would not choose high availability. This feature allows services to run for extended periods, with very little downtime, depending on the service.

    You would not choose scalability. This feature can increase (scale-up) or decrease (scale-down) resources that are assigned to a workload. As demand increases, you can add additional resources or capabilities to manage the increase in demand (known as scaling up). Scalability does not have to be done automatically.

    You would not choose fault tolerance. Fault tolerance is the ability to remain up and running in the event of a component or service that is no longer functioning. Typically, redundancy is built into cloud services architecture so that if one component fails, a backup component takes its place. This type of service is said to be tolerant of faults.

    You would not choose disaster recovery. This feature allows you to recover from a cloud service outage caused by an event. Cloud services disaster recovery can happen very quickly with automation, with resources being readily available for use.

32. You are the administrator of Nutex. You want to run containers in Azure. You have to decide between the following Azure services:
    - Azure Container Instance
    - Azure Kubernetes Service.
    Apply the following service benefits from the left to the relevant service on the right. (Use each option only once.)

    __*Anotacion:__

    You should choose the following:

    - Features:
        Fast startup
        Custom sizes
        Persistent storage
        Per-second billing
        Hypervisor-level security
        Linux and Windows
        Full container orchestration
        Service discovery across multiple containers
        Automatic scaling

    - Azure container Instance:
        Fast startup
        Custom sizes
        Persistent storage
        Per-second billing
        Hypervisor-level security
        Linux and Windows

    - Azure kubernetes service:
        Full container orchestration
        Service discovery across multiple containers
        Automatic scaling
        Coordinated application upgrades


    Azure Container Instances (ACI) is the service that allows you deploy a container on Azure cloud without having to manage the underlying infrastructure. ACI allows you launch containers quickly. With ACI, you incur costs only when running the container. The billing is on a per-second instead of a per-minute billing. You can isolate an application in a container like a VM environment. You can specify custom sizes for an Azure Container by specifying exact values for CPU cores and memory. With ACI, you can mount Azure files for persistent storage. The shared files are part of the container and are in a persistent state. You can have scheduled Linux containers as well as Windows containers with the same API.  ACI allows to have Hypervisor-level security which can isolate your application like the same experience that occurs in a VM.

    The Azure Kubernetes Service (AKS) manages a Kubernetes environment in Azure. AKS provides full container orchestration because you deploy and manage containerized applications without container orchestration expertise. AKS is scalable to meet growing demands by designs because it includes built-in application autoscaling.

    Microsoft recommends AKS instead of ACI when you need service discovery across multiple containers, coordinated application upgrades, and automatic scaling.

33. Your company needs to host multiple virtual machines that run an application your customers use in the East US region of Azure. You need to ensure that no other VMs are placed on the physical machines in the data center. All VMs need to have high availability using availability zones. What should you use?

    A)Azure Board

    B)Azure Advisor

    __C)Dedicated Host__

    D)Azure DevTest Labs

    E)Azure Pipelines

    F)Desired State Configuration

    __*Anotacion:__

    Azure Dedicated Host is a service that provisions physical hardware in a data center dedicated to one or more of your company's and no one else's virtual machines. Dedicated hosts are physical servers in a data center that can provide hardware isolation at the physical server level. These dedicated hosts share the same network and storage as non-isolated hosts. Dedicated hosts can opt in or out of a maintenance window to reduce the impact of the workload running on a dedicated host. You can deploy multiple dedicated hosts for high availability using availability zones or fault domains for fault isolation.

    You would not choose the Desired State Configuration (DSC) because it helps define a state for your machines. DSC does not ensure that VMs will be physically isolated on specific hardware.

    You would not choose Azure Advisor. Azure Advisor examines resource configuration and usage and provides recommended solutions. Recommendations for cost, security, reliability (formerly High Availability), operational excellence, and performance are combined in a single dashboard. Azure Advisor makes recommendations but may not recommend having VMs be physically isolated on specific hardware.

    Azure DevTest Labs allows you to create virtual machines (VMs) and PaaS resources without approvals. Azure DevTest Labs enables your team to create multiple VMs or an empty resource group as a sandbox to isolate VMs. You can use reusable templates and artifacts to provide your environment using Microsoft VMs or Linux VMs quickly. VMs can be created from custom images that have all the software applications and any tools installed. Azure DevTest Labs does not ensure that VMs will be physically isolated on specific hardware.

    You would not choose to use Azure Pipelines because it integrates your code repository with builds and releases in Azure DevOps.

    You would not choose to use Azure Boards. Azure Boards use an agile methodology to track and plan projects using tools such as scrum boards, Kanban boards, and dashboards.


34. The Nutex Corporation wants to use Azure RBAC to limit the privileges given to some of its Azure users for security reasons. Which of the following statements about Azure RBAC is NOT true?

    A)Up to 5,000 custom roles can be created per Azure AD.

    __B)Transferring a subscription to a different Azure AD tenant permanently deletes all role assignments from the source Azure AD tenant and migrates the role assignments to the target Azure AD tenant.__

    C)Deny assignments block users from performing specific Azure resource actions even if a role assignment grants them access.

    D)The Owner role has full access to all resources, including the right to delegate access to other users.

    __*Anotacion:__

    Transferring a subscription to a different Azure AD tenant does NOT permanently delete all role assignments from the source Azure AD tenant and migrate the role assignments to the target Azure AD tenant. If you transfer a subscription to another Azure AD tenant, the role assignments in the source tenant are permanently deleted, but they are not migrated to the target tenant. You will need to recreate the role assignments in the target tenant. You also must manually recreate managed identities for Azure resources.

    The fundamental built-in roles with Azure RBAC are as follows:

    - The Owner role has full access to all resources, including the right to delegate access to other users.
    - The Contributor role can create and manage all types of Azure resources but cannot grant access to other users.
    - The Reader role can view existing Azure resources.
    - The User Access Administrator role can manage user access to Azure resources.
    
    Up to 5,000 custom roles can be created for each Azure Active Directory. Built-in roles may not always meet all of your specific needs. In such cases, custom roles can be created. Custom roles can be shared across subscriptions and are stored in an Azure Active Directory. For specialized clouds, such as Azure Government, Azure Germany, and Azure China 21Vianet, the limit is 2,000 custom roles. Custom roles can be created using Azure PowerShell, Azure CLI, or the REST API.

    Deny assignments block users from performing specific actions even if a role assignment grants them access. Like a role assignment, a deny assignment attaches a set of deny actions to a user, group, or service principal at a scope for the purpose of denying access. Deny assignments are created and managed by Azure to protect resources.


35. Your company has several virtual machines that run on both a Hyper-V server and a VMware vCenter Server. The on-premises servers in the Finance department and Marketing department will be migrated to Azure using Azure Migrate. An on-premises VM called the collector appliance will discover information about the on-premises VMs to help the migration process along. The collector appliance will be a VM on the vCenter Server. After an initial readiness test of the Azure Migrate assessment, the readiness status of your VMs in the Azure readiness view displays the VM named VM055 using a blue color. What is the reason for VM055’s status?

    A)the VM is running on a Hyper-V server

    B)the VM is running on wrong VMware vCenter version

    __C)the VM is offline__

    D)the VM is in a saved state
    
    __*Anotacion:__     

    The VM is offline, because VMs with readiness unknown status are normally offline VMs and are displayed using a blue color during readiness testing.

    You should not select the VM is running on a Hyper-V server, because VMs running on Hyper-V servers can also be a part of your Azure Migrate assessment. For that reason, you can use the Azure Site Recovery Deployment Planner or partner tools.

    You should not select the VM in a saved state, because a VM in this state will be shown as ready for Azure, conditionally ready for Azure, or not ready for Azure, but not as readiness unknown.

    You should not select the VM is running on the wrong VMWare vCenter version. If this were the case, then you would have problems with all virtual machines on that VMWare vCenter and with one only one VM. Besides, the vCenter Server is running version 6.5. VMware VMs that are managed by vCenter Server (version 5.5, 6.0, 6.5 or 6.7) can be used with Azure Migrate.


36. Verigon Corporation is an industrial HVAC vendor. Their systems rely on many Azure services, including Azure Storage Blob and the Azure IoT Hub. They take advantage of the Azure Functions serverless environment. Verigon would like to automate some steps to be taken when a rare occurrence is detected, such as an unplanned major increase in temperature. What Azure service would best allow Azure Functions to react to such status change incidents?

    A)Azure Service Bus

    B)Azure Data Factory

    __C)Azure Event Grid__

    D)Azure Event Hub

    E)Azure Kubernetes

    __*Anotacion:__

    Azure Event Grid would be the service for Verigon to use. Azure Event Grid serves as a fully-managed event routing service. It can raise events from almost any source (such as IoT hub) and route them anywhere (such as Azure Functions). It is intended for reactive programming to discrete events, such as status change. An event is the smallest amount of information that describes something that happened. It has information that is only relevant to that type of event. Event Grid offers durable delivery, meaning that if an event is not acknowledged by the endpoint, it will retry.

    The Azure Service Bus is not the best choice in this scenario. The Azure Service Bus is based on messages. A message is a raw data that is to be stored or consumed elsewhere.

    Financial transactions would be a good example. Verigon wants to know about events, not messages. However, the Service Bus can be configured to send events to Event Grid if there are messages in a queue.

    Kubernetes does not meet Verigon's needs in this scenario. The Azure Kubernetes Service allows for the deployment and management of containers.

    It is not an event-routing service.

    The Azure Data Factory service does not apply to the Verigon scenario. It is a cloud-based data integration service to transform data at scale from data stores. It is not an event-routing service.

    The Azure Event Hub is a data streaming service intended for millions of events per second. It is designed to ingest a massive volume of data. The scenario does not indicate a need for such speed and transaction processing, as Verigon is looking for rare occurrences.

37. Jocelyn has been asked to configure one of the Nutex web servers in the East US 2 region with a public IP address for external FTP access. She executes the following command in the Azure CLI: `az network public-ip create -g NutexResourceGroup -n IPNutexFTP --dns-name NutexFTP --allocation-method Static`. What would be the fully qualified domain name (FQDN) assigned to the resulting public IP address resource?

    A)eastus2.NutexFTP.azure.com

    B)eastus2.NutexFTP.cloudapp.azure.com

    __C)NutexFTP.eastus2.cloudapp.azure.com__

    D)NutexFTP.eastus2.azure.com
    
    __*Anotacion:__

    The default FQDN would be NutexFTP.eastus2.cloudapp.azure.com using the format domainnamelabel.location.cloudapp.azure.com.

    When creating a public IP address resource using the command specified, the --dns-name option will fill the domainnamelabel portion, and the location will be the Datacenter region the resource group resides in.

    An Azure DNS Service can be used with a custom domain name instead of the default, if customization is desired.

    All other domain names are incorrect:

    The option eastus2.NutexFTP.cloudapp.azure.com has the location and label in the wrong order.

    The option NutexFTP.eastus2.azure.com is missing the CloudApp section.

    The option eastus2.NutexFTP.azure.com is missing the CloudApp section and has the location and label in the wrong order.

38. You want to have Azure monitor your VMs for CPU usage. Which of the following actions can you configure when CPU usage rises above a designated threshold? (Choose all that apply.)

    __A)send email notifications__

    __B)call a webhook__

    C)execute a PowerShell script

    __D)start execution of an Azure runbook__

    E)call a performance monitor counter for a performance management object

    F)run a batch file

    __*Anotacion:__

    An alert triggers when the value of a specified metric crosses a threshold you designate. The actions that can be taken when metric alert triggers are:

    1. Send email/SMS/Push/Voice notifications
    2. Call a webhook
    3. Start execution of an Azure runbook
    4. Run a Logic App
    5. Use an IT Service Management Connector (ITSMC)

    You can send email notifications to owners, contributors, or readers. You can also add additional email addresses of administrators.

    Webhooks route a notification to another computer or system using HTTP or HTTPS endpoints.

    You can start the execution of an Azure runbook when you use Azure Automation. You can have a runbook run when an alert is triggered.

    You cannot have an Azure VM run a batch file, execute a PowerShell script, or launch a backup when CPU usage rises above a designated threshold. Only email notifications, webhooks, or runbooks can be triggered by an alert.

    You can use the Azure CLI az monitor metrics alert command to create and monitor alerts. The following example creates a simple metric alert rule that monitors if average Percentage CPU on a VM is greater than 80:

    az monitor metrics alert create -n Alert1 -g ResourceGroup1 --scopes {VirtualMachineResourceID} --condition "avg Percentage CPU > 80" --description CPUpercentage

    You can use Powershell cmdlets to create a classic alert rule as shown in the following example, which triggers whenever it consistently receives any traffic for 10 minutes and again when it receives no traffic for 10 minutes:

    Add-AzureRmMetricAlertRule -Name myMetricRuleWithWebhookAndEmail -Location "West US" -ResourceGroup myresourcegroup -TargetResourceId /subscriptions/dededede-7aa0-407d-a6fb-eb20c8bd1192/resourceGroups/myresourcegroupname/providers/Microsoft.Web/sites/mywebsitename -MetricName "BytesReceived" -Operator GreaterThan -Threshold 2 -WindowSize 00:10:00 -TimeAggregationOperator Total -Description "alert on any website activity"

    You can send an email or create a webhook when an alert triggers. However, you have to create the email or the webhook before creating the alert rule. If an alert rule is already created, you cannot associate webhook or emails with it. For this reason, you cannot associate a PowerShell script with an alert rule.

    You cannot associate Performance Monitor counters with an alert rule. You are limited to the signal logic metrics provided:

    These metrics are similar to, but not the same as, Performance Monitor.


39. Your company has the need to keep services up and running, with very little downtime, depending on the service. Which cloud feature is needed in this scenario?

    __A)High availability__

    B)Disaster recovery

    C)Agility

    D)Economy of scale

    E)Scalability

    F)Fault tolerance

    G)Elasticity

    __*Anotacion:__

    You would choose high availability. This feature allows services to run for extended periods, with very little downtime, depending on the service.

    You would not choose scalability. This feature can increase (scale-up) or decrease (scale-down) resources that are assigned to a workload. As demand increases, you can add additional resources or capabilities to manage the increase in demand (known as scaling up). Scalability does not have to be done automatically.

    You would not choose elasticity. This feature increases or decreases resources as needed, but unlike scalability, elasticity is done automatically. Elastic resources are based on the current needs and resources are added or removed dynamically to meet those needs, from the most advantageous geographic location. A distinction between scalability and elasticity is that elasticity is done automatically.

    You would not choose agility. Agility is the ability to react quickly. Cloud services can allocate and deallocate resources quickly. These are on-demand services that are provisioned in minutes. There is no manual intervention in provisioning or deprovisioning services. Agility does not allow you to have high availability or redundancy.

    You would not choose fault tolerance. Fault tolerance is the ability to remain up and running in the event of a component or service that is no longer functioning. Typically, redundancy is built into cloud services architecture so that if one component fails, a backup component takes its place. This type of service is said to be tolerant of faults.

    You would not choose disaster recovery. This feature allows you to recover from a cloud service outage caused by an event. Cloud services disaster recovery can happen very quickly with automation, with resources being readily available for use.

    You would not choose economy of scale. The concept of economy of scale is the ability to do business cheaper and more efficiently when operating on a larger scale, in comparison to operating on a smaller scale.

40. You have been hired by Verigon Inc. who develops web applications. You have an expert team of developers and administrators who build and maintain business-critical web applications. Your team members are well versed with Windows and network administration. Verigon has recently moved its business-critical web applications to the Azure cloud. Your team wants to perform repeatable testing, management, and administration tasks. Which of the following tools are BEST for this purpose? (Choose two.)

    __A)Azure PowerShell__

    B)Azure Resource Manager templates

    C)Azure portal

    D)Azure Arc

    __E)Azure CLI (command line interface)__

    __*Anotacion:__

    The best tools to use are Azure CLI and PowerShell to perform repeatable testing, management, and administration tasks. As the network administrator and team members are already experts and well versed with Windows, it would be easier for them to use these command-line tools. Azure command-line tools help automate routine operations with scripts, standardize database failovers, and pull data that provides powerful insights. They help manage Azure resources as well.

    The Azure portal is not the correct choice. Managing Azure using the portal takes too much time and is not repeatable. The Azure portal is a Microsoft-provided web-based, unified console that you can use to manage your Azure subscription and resources. It helps you build, manage, and monitor everything from simple web apps to complex cloud deployments. The Azure portal has continuous availability and resiliency built in. It has a presence in every Azure datacenter. Microsoft updates the Azure portal continuously, and it does not require downtime for maintenance activities.

    Azure Resource Manager (ARM) templates are not the correct choice You should use ARM templates to implement Infrastructure as Code (IaC) for your Azure solutions. The template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project.

    Azure Arc is not the correct choice. It provides a simplified way for governance and management by delivering a consistent multi-cloud and on-premises management platform. Azure Arc provides a centralized, unified way to manage your environment together by projecting your existing non-Azure and/or on-premises resources into Azure Resource Manager.

41. The Nutex Corporation wants to use the capabilities of Azure Security to secure their Azure infrastructure, customer data, and applications. You are asked to implement Azure Security. It is important that you understand its capabilities before you implement it. Match the capabilities of Azure Security with its appropriate description.

    __*Anotacion:__

    You would map the capabilities of Azure Security with their descriptions as follows:

    Azure Site Recovery -> Orchestrates replication, failover, and recovery of workloads and apps so that they are always available.

    Express Route -> A dedicated WAN link that extends the on-premises networks into the Microsoft cloud over a dedicated private connection facilitated by a connectivity provider.

    Forced tunnelling -> A mechanism that ensures that services are not allowed to initiate a connection to devices on the Internet.

    Resource class -> Pre-determined limits that govern compute resources and concurrency for query execution.

    Azure Site Recovery keeps corporate workloads and apps up and running when planned and unplanned outages occur. Azure Site Recovery helps orchestrate replication, failover, and recovery of workloads and apps so that they are available from a secondary location if the primary location goes down.

    ExpressRoute establishes connections to Microsoft cloud services, such as Azure, Office 365, and CRM Online. Connectivity can be from a point-to-point Ethernet network, an any-to-any (IP VPN) network, or a virtual cross-connection through a connectivity provider at a co-location facility. ExpressRoute connections travel the Internet and are more secure than VPN-based solutions. It allows the connections to offer lower latencies, faster speeds, better reliability, and higher security than typical connections over the Internet.

    Application Gateway optimizes the web farm productivity by offloading CPU intensive SSL termination to the application gateway (also known as “SSL offload” or “SSL bridging”). It also provides other Layer 7 routing capabilities, including round-robin distribution of incoming traffic, cookie-based session affinity, URL path-based routing, and the ability to host multiple websites behind a single application gateway. Azure Application Gateway is a layer-7 load balancer. It provides failover, performance-routing HTTP requests between servers, whether they are on the cloud or on-premises.

    Forced tunneling is commonly used to force outbound traffic to the Internet to go through on-premises security proxies and firewalls.

    VPN Gateway sends network traffic between an Azure Virtual Network and the on-premises site. A VPN gateway is a type of virtual network gateway that sends encrypted traffic across a public connection.


42. You are a system administrator for your organization and you are tasked with migrating all the files from an on-premises setup to the cloud. You are exploring Azure Storage services to achieve the objective. Map the types of storage accounts with Microsoft’s usage recommendations.

    __*Anotacion:__

    You should choose the following:

    (Type of Storage account -> Usage Recommendation)
    Standard general-purpose v2 -> Used for blobs, file shares, queues, and tables. Microsoft recommends this type of storage account for most scenarios.
    Premium block blobs -> Microsoft recommends this type of storage account for scenarios with high transaction rates or smaller objects, or that require consistently low storage latency.
    Premium file shares -> Microsoft recommends this type of storage account for enterprise or high-performance scale applications. This account type also supports SMB (Server Message Block) and NFS (Network File System) shares.	
    Premium page blobs -> This type of storage account is recommended for page blobs only.	
    
    Azure Storage is a service that stores files, messages, tables, and other types of information. Data stored in Azure Storage can be read or written from clients such as websites, mobile apps, desktop applications, and other custom solutions. Data in Azure Storage can be accessed from anywhere globally over HTTP or HTTPS.

    Standard general-purpose v2 storage supports blob storage and can have locally redundant storage (LRS), geo-redundant storage (GRS), and read-access geo-redundant storage (RA-GRS) as redundancy options. Standard general-purpose v2 is used for blobs, file shares, queues, and tables. Microsoft recommends this type of storage account for most scenarios.

    Premium block blobs support Blob storage and can have LRS and zone-redundant storage (ZRS) as redundancy options. Premium block blobs are recommended when transaction rates are high or smaller objects require consistently low storage latency.

    Premium file shares support Azure Files and can have LRS and ZRS as redundancy options. Premium file shares are recommended for enterprise or high-performance scale applications, and support Server Message Block (SMB) and Network File System (NFS) shares.

    Premium page blobs only support page blobs and can have LRS redundancy.

    The following table displays the correct mapping of the type of storage accounts with Microsoft’s usage recommendation.

    (Type of Storage account / Supported storage services / Redundancy options / Usage Recommendation)
    Standard general-purpose v2 / Blob Storage (including Data Lake Storage), Queues Storage, Tables Storage, and Azure Files / LRSGRSRA-GRS / Used for blobs, file shares, queues, and tables, and recommended by Microsoft for most scenarios.
    Premium block blobs / Blob Storage (including Data Lake Storage) / LRSZRS / Recommended for scenarios with high transaction rates or smaller objects that require consistently low storage latency.
    Premium file Shares / Azure Files / LRSZRS / Recommended for enterprise or high-performance scale applications. Supports Server Message Block (SMB) and Network File System (NFS) shares.
    Premium page blobs / Page blobs only / LRS / Recommended for page blobs only.

### Segundo intento

1. Which of the following is the proper use of an Azure ARM template?

    A)To organize resources and subscriptions

    B)To act as a broker with message queues and publish-subscribe topics (in a namespace).

    __C)The automatic creation of Azure resources__

    D)To deploy predictive analytics

    __*Anotacion:__

    Azure Resource Manager templates are JavaScript Object Notation (JSON) files that specify the infrastructure and configuration for your project. They can be used to automate the creation of resources. An ARM template can create identical resources in multiple locations.

    Organizing resources and subscriptions is better done through the use of management groups. Azure Management Groups can be used to create an effective and efficient hierarchy to manage Azure subscriptions and resources.

    The Azure Service bus, not an ARM template, is a broker with message queues and publish-subscribe topics (in a namespace).

    Deploying predictive analytics is better done with the Azure Machine Learning Studio. This is a drag and drop tool that allows you to build, test, and deploy predictive analytics using AI.

2. You would like to take advantage of an Azure service that can meet the following requirements:
    - Reduce boot times for virtual machines
    - Increase battery life on devices
    - Reduce device crashes
    What tool do you need?

    A)Microsoft Windows for Workgroups

    B)Azure Reserved Virtual Machines (VM) Instances

    __C)Microsoft Managed Desktop__

    D)Azure PowerShell

    E)Microsoft Windows PE

    F)Azure DevTest Labs

    __*Anotacion:__

    Microsoft Managed Desktop is a tool that can make managing systems easier. Benefits provided to systems managed by MMD are:

    - Reduces boot times on devices.
    - Almost doubles a device’s battery life
    - Reduces crashes on devices
    - When using Enterprise State Roaming, users have the same experience when they sign in with different devices.
    
    All other options are incorrect.

    Windows Preinstallation Environment (PE) is a lightweight operating system that can be used to troubleshoot Windows devices. It can be used for deployment of workstations and servers.

    Windows for Workgroups is a legacy operating environment that had support for SMB file sharing.

    Azure DevTest Labs is used to deploy a system to developers. Large numbers of systems running different operating systems can be deployed quickly and then deleted as soon as they are no longer needed.

    Azure PowerShell is a set of command line commands called cmdlets that manage resources. It can be a powerful automation tool when using scripts.

    Azure Reserved Virtual Machines (VM) Instances are virtual machines (VM) on the Microsoft Azure public cloud that has been reserved for dedicated use on a one- or three-year basis.


3. You are considering moving several of your network services to the cloud. You are evaluating a private, public, and hybrid cloud. Match the advantage to the proper cloud implementation.

    __*Anotacion:__

    You should choose the following:

    Public Cloud -> No need to purchase hardware or software / Service provider provides the maintenance / Scalability / Pay only for the service you use

    Private Cloud -> Scalability / Highest level of control and security

    Hybrid Cloud -> Scalability / Pay for extra computing power only when needed / Helpful for migrating services to the cloud

    A public cloud, such as Amazon Web Services or Microsoft Azure, provides the following advantages:

    - Hardware and software are provided by the cloud provider, so there is no need to purchase either.
    - The customer only pays for the services that they consume.
    - Scalability is almost unlimited because on-demand resources are available when you need it.
    - The reliability of the cloud is guaranteed and provides cost-effective reliability.
    
    A private cloud has computing resources exclusively used by a single organization. A private cloud has the following advantages:

    - A private cloud is more secure than a public cloud because cloud resources are not shared with others.
    - Private clouds provide scalability and efficiency.
    - Scalability is available in a private cloud and is as efficient as a public cloud.
    
    A hybrid cloud combines the best of a public cloud and a private cloud so you can take advantage of both. A hybrid cloud has the following advantages:

    - You can take advantage of cloud bursting. With cloud bursting, if there is a spike in demand for an application or resource, the organization goes to the public cloud to use additional computing resources.
    - You can use a hybrid cloud to ease transitioning to the cloud by phasing in workloads over stages.
    - A hybrid cloud has the ability to scale to the public cloud.

4. You are a system administrator for Nutex Corporation. You have hosted several web applications in the Azure cloud and want to monitor the performance of the applications and be notified whenever an issue arises. Which of the following statements are TRUE or FALSE regarding Azure Monitor? Drag the statements to the appropriate choice.

    __*Anotacion:__

    Below are the correct answers for the given statements.

    (Statement -> True / False)
    Alerts in Azure Monitor proactively notify you of critical conditions and can take corrective actions. -> TRUE
    You cannot create alerts using Azure Monitor. -> FALSE
    To manage alert instances, users should have the Azure built-in roles of either Monitoring Contributor or Monitoring Reader. -> TRUE
    You can set the user response of an alert to specify where it is in the resolution process. -> TRUE
    You can only see all alert instances in all your Azure resources generated in the last seven days on the Alerts page -> FALSE
    
    Alerts in Azure Monitor proactively notify you of critical conditions and potentially attempt to take corrective action. Alerts help you identify and address issues before the users of the system notice them. You can create alerts using Azure Monitor. You can have action groups with alerts. You can specify an action for the alert that can run a remediation to respond to the alert.

    Log alert rules proactively identify issues from data in your workspace. Each alert rule is created based on a log query that automatically runs at regular intervals. The results are then inspected to determine if the alert should be created. You can create alerts based on metrics and logs.

    To manage alert instances, a user must have the Azure built-in role of either Monitoring Contributor or Monitoring Reader. These roles are supported at any Azure Resource Manager scope, from subscription to granular level assignments at a resource level.

    You can set the user response of an alert to specify where it is in the resolution process. An alert is created when the criteria specified in the alert rule is met. The status of the created alert is New. You can change the status when you acknowledge or close an alert.

    The Alert page provides the summary of alerts created in the past 24 hours. You can access alerts generated in the past 30 days, not seven days.


5. Your company has a cloud-based application named MktTrends, which is used by the Marketing department. Which type of cloud computing model would deliver exactly 3.76GB of memory to the MktTrends application to complete a query task?

    __A)Serverless computing__

    B)IaaS

    C)PaaS

    D)FaaS

    __*Anotacion:__

    Serverless computing is used to deliver exact units of resources when an application needs it, unlike other cloud computing models where resources must be allocated ahead of time to be available when demanded. For example, if you use IaaS, you might add 4 GB of RAM so that an application has enough memory for peak usage times. Serverless computing allocates the exact amount that application needs, such as 3.76 GB, to complete the task.

    All other options do not deliver the exact number of resources when the application needs it.

    IaaS is a category of cloud computing services that is used by many cloud providers. With IaaS, you pay for resources such as servers, virtual machines (VMs), storage, networks, and operating systems from a cloud provider on a pay-as-you-go basis. These resources are provisioned and managed over the Internet.

    Platform as a service (PaaS) provides a company with an environment for developing, running, debugging, testing, patching, and deploying software applications. PaaS allows you to quickly create an application without having to worry about managing the underlying infrastructure. PaaS eliminates the need to install an operating system, web server, server patches, or other infrastructure to create applications. PaaS creates a complete deployment environment in the cloud that has tools to deliver simple cloud-based apps or sophisticated cloud-enabled enterprise applications. The tools and resources are purchased from the service provider on a pay-as-you-go basis.

    Function as a service (FaaS) is a type of service that uses a service-hosted remote procedure call. FaaS is a platform to run functions without worrying about the underlying infrastructure. FaaS lets the application logic created by developers execute, but the code is executed in stateless compute instances of the cloud provider.


6. You want to have Azure monitor your VMs for CPU usage. Which of the following actions can you configure when CPU usage rises above a designated threshold? (Choose all that apply.)

    __A)send email notifications__

    B)call a performance monitor counter for a performance management object

    __C)call a webhook__

    __D)start execution of an Azure runbook__

    E)run a batch file

    F)execute a PowerShell script

    __*Anotacion:__

    An alert triggers when the value of a specified metric crosses a threshold you designate. The actions that can be taken when metric alert triggers are:

    1. Send email/SMS/Push/Voice notifications
    2. Call a webhook
    3. Start execution of an Azure runbook
    4. Run a Logic App
    5. Use an IT Service Management Connector (ITSMC)

    You can send email notifications to owners, contributors, or readers. You can also add additional email addresses of administrators.

    Webhooks route a notification to another computer or system using HTTP or HTTPS endpoints.

    You can start the execution of an Azure runbook when you use Azure Automation. You can have a runbook run when an alert is triggered.

    You cannot have an Azure VM run a batch file, execute a PowerShell script, or launch a backup when CPU usage rises above a designated threshold. Only email notifications, webhooks, or runbooks can be triggered by an alert.

    You can use the Azure CLI az monitor metrics alert command to create and monitor alerts. The following example creates a simple metric alert rule that monitors if average Percentage CPU on a VM is greater than 80:

    `az monitor metrics alert create -n Alert1 -g ResourceGroup1 --scopes {VirtualMachineResourceID} --condition "avg Percentage CPU > 80" --description CPUpercentage`

    You can use Powershell cmdlets to create a classic alert rule as shown in the following example, which triggers whenever it consistently receives any traffic for 10 minutes and again when it receives no traffic for 10 minutes:

    `Add-AzureRmMetricAlertRule -Name myMetricRuleWithWebhookAndEmail -Location "West US" -ResourceGroup myresourcegroup -TargetResourceId /subscriptions/dededede-7aa0-407d-a6fb-eb20c8bd1192/resourceGroups/myresourcegroupname/providers/Microsoft.Web/sites/mywebsitename -MetricName "BytesReceived" -Operator GreaterThan -Threshold 2 -WindowSize 00:10:00 -TimeAggregationOperator Total -Description "alert on any website activity"`

    You can send an email or create a webhook when an alert triggers. However, you have to create the email or the webhook before creating the alert rule. If an alert rule is already created, you cannot associate webhook or emails with it. For this reason, you cannot associate a PowerShell script with an alert rule.

    You cannot associate Performance Monitor counters with an alert rule. You are limited to the signal logic metrics provided:



    These metrics are similar to, but not the same as, Performance Monitor.

7. You are a system administrator for Nutex, Inc. Your organization has Sales, Finance, and Marketing departments. You have created 30 virtual machines, ten for each department, in the Azure virtual network. All machines are in a single subnet named SubnetA, having an IP address range of 10.0.0.0/24. You want to ensure that the virtual machines of each department do not communicate with the virtual machines of the other departments. What should you do? Place the steps in the correct order.

    __*Anotacion:__

    To ensure that the virtual machines of each department do not communicate with the virtual machines of the other departments, you should take the following actions:

    1. Create two more subnets named SubnetB and SubnetC with separate IP address ranges of 172.16.0.0/24 and 192.168.0.0/24.
    2. Move the Finance department VMs to SubnetB and the Marketing department VMs to SubnetC, and leave the Sales department VMs in SubnetA.
    3. Create a custom routing table to restrict communication between SubnetA, SubnetB, and SubnetC.
    
    You can set up your Azure virtual network with your own IP addressing. You can divide that IP address space into subnets and allocate part of the defined address space to each subnet, or you can provide separate subnets. An Azure virtual network provides the capability of isolation and segmentation, which can help provide more security and restrict communication between subnets.

    By default, Azure routes traffic between subnets on any connected virtual networks. You can create custom route tables that control how packets are routed between subnets.

    You should not install a firewall in the Azure virtual network. You should install Azure Firewall to control outbound network access from the Azure subnet.

    You should not install two network interface cards (NICs) on each virtual machine. Multiple NICs are installed to connect a subnet to multiple subnets. NICs connected to subnets within the virtual network can communicate with each other without extra configuration.

    You should not use virtual network peering between the subnets. By using virtual network peering, you can link separate virtual networks together. Peering enables network resources in each virtual network to communicate with each other.

    You should not configure service endpoints between the subnets. Service endpoints are used to connect other Azure resource types, such as SQL databases and storage accounts.

8. In which of the following scenarios do you NOT need to define a local network gateway? Choose two.

    __A)site-to-site VPN__

    B)ExpressRoute

    __C)point to site__

    D)VNet to VNet

    __*Anotacion:__

    A local network gateway is an object that represents your local site (on-premises location) for routing purposes.

    In a point-to-site VPN, a single user is coinfected to the virtual network. Since neither end is the on-premises network, no local network gateway is required.

    In a site-to-site VPN, each end is on-premises; for this reason, a local network gateway required.

    In a VNet to VNet connection, neither end is your on-premises network. A VPN with a connection to the on-premises network is the only scenario where you need a local network gateway.

    In an ExpressRoute VPN, the connection is between Microsoft services and the on-premises network, so a local gateway is also needed.


9. You are a system administrator for Nutex Corporation. Your organization has an on-premises and an Azure environment. You have several VMs running Windows, macOS, and Linux operating systems. You have multiple Azure Storage accounts in Azure Storage, and it is becoming increasingly difficult and challenging to manage them. Which of the following options should you use to easily manage the Azure Storage accounts and to help in migrating your data from on-premises to the Azure VMs?

    __A)Azure Storage Explorer__

    B)Azure CLI (command line interface)

    C)Azure PowerShell

    D)AzCopy

    __*Anotacion:__

    You should use Azure Storage Explorer to manage the Azure Storage accounts and to help in migrating your data from on-premises to the Azure VMs. Azure Storage Explorer is a standalone application that allows you to work with Azure Storage data on Windows, macOS, and Linux operating systems. You can migrate data by copying and pasting files into a standard operating system using file system explorer. The duration from source to destination of the transfer depends on the size of the data and the network speed.

    You should not use AzCopy to manage several Azure Storage accounts. You would use the AzCopy tool to copy data to or from Azure Blob Storage, Azure Files, and Azure Table storage by using simple commands. You can either copy data between storage accounts or a file system and a storage account. You can download the AzCopy V10 executable file to your computer and run it from the command line interface.

    You should not use Azure PowerShell or Azure CLI. Azure PowerShell is a scripting language tool provided by Microsoft. It enables you to interact with Microsoft technologies via PowerShell cmdlets. Azure CLI allows you to run commands and scripts for migrating data from on-premise resources to Azure. Using PowerShell, you can also manage the transfer of data to and from Azure Storage accounts. While you can use both PowerShell and CLI to manage Azure Storage accounts, you would have to create and debug several scripts to manage any storage accounts. Azure Storage Explorer has a GUI interface that easily allows you to manage any storage accounts.


10. A company is using containers for deploying all of its web applications. During a security audit, you notice that Microsoft Defender for Cloud is not being used properly to provide misconfigurations related to containers. For which resource can you NOT use Microsoft Defender for Cloud to secure the containers?

    __A)Azure Container Instance (ACI)__

    B)Container hosts (VMs running Docker)

    C)Azure Container Registry (ACR)

    D)Azure Kubernetes Service (AKS)

    __*Anotacion:__

    Azure Container Instance (ACI) does not use Microsoft Defender for Cloud. ACI is a service that allows you to run containers in the cloud without using VMs.

    Defender for Cloud can protect Kubernetes clusters, container hosts that are VMs running Docker, and Azure Container Registries (ACRs)

    The following shows the resources protected by Microsoft Defender.

    You should not choose Azure Kubernetes Service (AKS). Microsoft Defender for Cloud can be used for assessments, finding misconfigurations, and for guidelines to improve security with AKS.

    Microsoft Defender for Cloud can show misconfigurations in your Docker environment as well as providing guidelines for mitigating threats indicated by Azure Defender. This is provided by Microsoft Defender for servers, which compares the configurations with the Center for Internet Security Docker Benchmark.

    Microsoft Defender for Cloud provides vulnerability assessments along with management tools for Azure Container Registry (ACR) registry entries.

11. You were tasked with choosing the most appropriate cloud deployment solution for an enterprise workforce that consists mainly of remote employees. You chose an IaaS solution. What is the MOST likely business purpose for your cloud solution?

    A)To supply on-demand development, testing, delivery, and management of software applications

    B)To provide a turnkey solution for email in the cloud

    __C)To deploy Azure virtual machines to the company’s employees__

    D)To ensure applications used by employees are updated as quickly as possible

    __*Anotacion:__

    Regardless of the type of VMs you are deploying to the environment, it will only require the basic services provided by the Infrastructure as a Service ( IaaS) model. An IaaS solution typically provides these components for customer use:

    - VMs
    - Bare metal servers
    - Load balancers
    - Networking services
    
    With this model, the provider manages the infrastructure, and the client installs and maintains all operating systems, middleware, and applications.

    The cloud computing model that supplies an on-demand environment for developing, testing, delivering, and managing software applications is Platform as a Service (PaaS). This provides a complete software development environment, adding middleware elements to the components provided by IaaS.

    The cloud computing model that provides a turn-key solution for email in the cloud and ensures the quickest application updates possible is Software as a Service (SaaS). This model lets clients use cloud-based apps over the Internet while the vendor handles all infrastructure, including updates to the applications.


12. The Nutex Corporation wants to migrate its on-premises applications and services to Azure. You are the analyst tasked to investigate the benefits of this migration to Azure. Which of the following statements about the Azure TCO Calculator is TRUE?

    A)Azure TCO Calculator primarily evaluates the total cost incurred to migrate on-premises application workloads to Microsoft Azure.

    B)Azure TCO Calculator calculates on-premises infrastructure costs based on three criteria: hardware, software, and networking costs.

    C)The Azure TCO Calculator application can be downloaded from the Azure website.

    __D)Customers interested in migrating from on-premises deployments to Azure must focus their calculations on the Compute, Storage, and Network requirements on Azure in order to evaluate the costs accurately.__

    E)The Azure Pipelines service is not available with the Azure Government offering.

    __*Anotacion:__

    Customers interested in migrating from on-premises deployments to Azure must focus their calculations on the Compute, Storage, and Network requirements on Azure in order to evaluate the costs accurately.

    Unfortunately, not all cloud TCO calculations are accurate enough to let you make an informed decision. Many are ballpark estimates because they have failed to account for all performance metrics essential for rightsizing, and they may rely on metrics that have been averaged instead of considering peaks and valleys. These imprecise assessment methods may cause you to estimate a configuration scenario that is not suited to your performance requirements.

    Metrics such as peak CPU utilization, allocated and peak RAM usage, observed storage on-premises (capacity and current occupancy), disk IOPS and bandwidth, throughput, and usage patterns must be analyzed. This approach focuses on three areas: Compute, Storage, and Network.

    The following statements are not true:

    - Azure TCO Calculator primarily evaluates the total cost incurred to migrate on-premises application workloads to Microsoft Azure.
    - Azure TCO Calculator calculates on-premises infrastructure costs based on three criteria: hardware, software, and networking costs.
    - The Azure TCO Calculator application can be downloaded from the Azure website.
    - Microsoft’s Azure Total Cost of Ownership (TCO) Calculator allows you to evaluate potential cost savings if you migrate on-premises application workloads to Microsoft Azure. You must specify the details of your existing infrastructure and various cost assumptions that you want the tool to work with. You receive a report that shows your on-premises costs compared to Microsoft Azure costs. While you may get a report of cost savings, TCO will NOT give you the total costs incurred to migrate on-premises application workloads to Microsoft Azure. TCO may allow you to compare costs on databases, storage, and networking, but does NOT calculate the labor rate that may be involved with the migration.

    The Azure TCO Calculator calculates the on-premises infrastructure costs based on more than three criteria. It takes the following costs into consideration:

    - Hardware
    - Software (for Windows as an OS)
    - Electricity
    - Data center
    - Networking
    - Disk storage
    - IT labor
    - Virtualization
    
    Azure TCO Calculator is an online calculator that can be accessed on the Azure website. Customers can use it to check their TCO but only the results can be downloaded.

    At the time of this writing, Azure Pipelines service is not available with the Azure Government offering.

13. You need to design a multi-factor authentication (MFA) for your Azure deployment. You need to secure the following with a second method of authentication.
    - First-party Microsoft apps
    - Web applications published through Azure AD App Proxy
    You are using Azure Active Directory and on-premises Active Directory. You will use Azure AD Connect with password sync. You want to have a phone call as a second factor for MFA. You use Multi-Factor Authentication (MFA) Server on-premises to design a multi-factor authentication (MFA) for your Azure deployment. Does your solution meet the requirement?

    __A)No__

    B)Yes

    __*Anotacion:__

    You should not use Multi-Factor Authentication (MFA) Server on-premises to design a multi-factor authentication (MFA) for your Azure deployment. You should use Azure Multi-Factor Authentication in the cloud instead. You can determine which of these two choices would be best by determining what objects that you want to secure, where your users are located, and what features of MFA that you want.

    The following illustrations shows what objects can be secured with a second a method of authentication with Multi-Factor Authentication (MFA) Server on-premises or Azure Multi-Factor Authentication in the cloud.

    (Objects to secure -> Method of authentication)
    Saas apps in the app gallery -> MFA in the cloud
    Remote access such as VPN, RDG -> MFA server / MFA in the cloud
    Web applications published through Azure AD App Proxy -> MFA in the cloud
    IIS applications not published through Azure AD App Proxy -> MFA Server
    First-party Microsoft apps -> MFA Server / MFA in the cloud

    The following illustration shows which MFA method Microsoft recommends.

    (User Location -> Method of authentication)
    On-premises Active Directory -> MFA Server
    Azure Active Directory -> MFA in the cloud
    Azure AD and on-premises AD using federation with AD FS -> MFA Server / MFA in the cloud
    Azure AD and on-premises AD using DirSync, Azure AD Sync, Azure AD Connect - no password sync -> MFA Server / MFA in the cloud
    Azure AD and on-premises AD using DirSync, Azure AD Sync, Azure AD Connect - with password sync -> MFA in the cloud

    In this scenario, users will in Azure Active Directory and on-premises Active Directory, and you will use Azure AD Connect with password sync.

14. Thanks to Azure, developers of the Dreamsuites Corporation can easily deploy and manage their own cloud workloads. They want to get the most out of their investment by optimizing their Azure deployments. As an Azure consultant, where would you direct Dreamsuites to obtain some personalized, detailed recommendations for reliability, performance and operational excellence?

    A)Azure Monitor

    __B)Azure Advisor Score__

    __C)Azure Advisor__

    D)Azure Secure Score

    E)Investigation Priority Score

    __*Anotacion:__

    Azure Advisor Score is a sub-feature of Azure Advisor. Dreamsuites can use the Azure Advisor Score to assess how well they are following the best practices defined by the Azure Advisor. Any problem area can be selected to see individual recommendations.

    Dreamsuites can meet their needs using Azure Advisor. Azure Advisor examines resource configuration and usage and provides recommended solutions. Recommendations for cost, security, reliability (formerly High Availability), operational excellence, and performance are combined in a single dashboard.

    Azure Monitor collects telemetry data from applications and services to identify how applications are performing. While useful, it does not contain the workload recommendations that Dreamsuites needs.

    An Investigation Priority Score does not meet the needs of the scenario. This score is given by Cloud App Security to help investigate "risky" users.

    Azure Secure Score does not directly meet all of Dreamsuites' needs. It is part of Azure Security Center and is an assessment of security issues at a glance. However, security recommendations are included as part of Azure Advisor.


15. The Nutex Corporation plans to comply with all the privacy, compliance, and data protection standards. You are asked to investigate the security, compliance, and privacy offerings and commitments from Microsoft. Which of the following statements about the Azure Trust Center are TRUE? (Choose two.)

    __A)Customers, including controllers and processors, who are not GDPR-compliant can be fined up to 4% of their annual global turnover or €20 million.__

    B)Azure Trust Center is built on the three foundational principles of trust.

    __C)Azure is K-ISMS certified.__

    D)Azure Sentinel is a compliance management tool available with Trust Center.

    __*Anotacion:__

    Azure is K-ISMS certified. Customers, including controllers and processors, who are not GDPR-compliant can be fined up to 4% of their annual global turnover or €20 million.

    K-ISMS certification is designed to ensure the security and privacy of data in the Korean region. Azure meets the latest compliance offerings in the K-ISMS.

    The EU General Data Protection Regulation (GDPR) was developed to create data privacy laws across Europe. It replaces Data Protection Directive 95/46/EC and differs in several significant ways, such as:

    - Larger jurisdiction
    - Larger fines
    - Consent must be requested in a clear and easily accessible manner
    - Breach Notifications will be mandatory and must be completed within 72 hours of breach awareness
    - Privacy
    
    Azure Trust Center is built on four, not three, foundational principles of trust:

    - security (keep customers’ data secure),
    - privacy (how customers are in control of their data),
    - compliance (comprehensive list of compliance offerings and solutions), and
    - transparency (being transparent about how Microsoft uses customers’ data).
    
    Azure Sentinel is not a compliance management tool available with Trust Center. Azure Sentinel is a tool that provides intelligent security analytics. The data for this analysis tool is stored in an Azure Monitor Log Analytics workspace. Azure Sentinel collects data at cloud scale, finds uncovered threats, minimizes false positives using analytics and threat intelligence, investigates threats, and responds to incidents rapidly with built-in orchestration and automation of common tasks.


16. You need to propose a budget for cloud services, including selecting the correct cloud service model (PaaS, IaaS, or SaaS). To help coordinate services, you must understand which responsibilities belong to each type of cloud provider and which would belong to your organization. In each service scenario, which areas are the responsibility of the service provider? Move the appropriate responsibility to the appropriate category.

    __*Anotacion:__

    You should choose the following:

    Saas -> Physical security / Identity and access management / Network controls 

    Paas -> Physical security / Identity and access management / Network controls 

    IaaS -> Physical security

    On-premises ->

    Network controls are the responsibilities of the SaaS and PaaS vendors. The customer has no responsibility for network controls in a SaaS. However, they have some control over network controls in a PaaS. The customer has full responsibility of network controls for an IaaS since the customer can allocate resources such as routers, virtual networks, and gateways in an IaaS.

    Identity and access management is a shared responsibility between the vendor and the customer in a SaaS and PaaS. These vendors decide what type of access that the customer has to its software in a SaaS and platform in a PaaS and the customer can decide which users in their subscription can have access to the SaaS or PaaS.

    Physical security is the sole responsibility of the customer in an on-premises environment. Ensuring that the physical datacenter that houses the computing resources are secure is the cloud vendor’s responsibility with a SaaS, PaaS, or IaaS environment.


17. You are part of the IT team at the Nutex Corporation. Your management has triggered an initiative to reduce the costs to manage apps and services on Azure. To work for this initiative, you must know the best practices to reduce Azure costs. Which of the following statements about analyzing Azure costs on the Azure portal are TRUE? (Choose three.)

    __A)The AWS Cost and Usage report can be integrated with Azure Cost Management to analyze AWS costs on the Azure portal.__

    B)The two types of Cost Management alerts are Budget alerts and Credit alerts.

    C)Cost Management reports that contain multiple currency types such as Euros, US dollars, and Canadian dollars.

    __D)Invoice Manager is a role available for Cost Management for customers with a Microsoft Customer Agreement.__

    __E)Azure costs can be filtered by the tags assigned to resources and services.__

    F)Budget alerts are available only for customers with an Enterprise Agreement.

    __*Anotacion:__

    The following statements are true:

    - Azure costs can be filtered by the tags assigned to resources and services.
    - Invoice Manager is a role available for Cost Management for customers with a Microsoft Customer Agreement.
    - AWS Cost and Usage report can be integrated with Azure Cost Management to analyze AWS costs on the Azure portal.
    
    Customers can filter and view Azure costs by the following: service, resource, tag assigned to resources and services, location, type of charge, invoice, and per day or per month.

    The five roles available for Cost Management for customers with a Microsoft Customer Agreement are:

    - Owner – manage billing settings and access, view all costs, and manage cost configuration.
    - Contributor – manage billing settings except for access, view all costs, and manage cost configuration.
    - Reader – view billing settings, cost data, and cost configuration.
    - Invoice Manager – view and pay invoices, and view cost data and configuration
    - Azure subscription creator – create Azure subscriptions, view costs, and manage cost configuration
    
    Integration with the AWS Cost and Usage report can analyze AWS costs for the following scopes: AWS linked accounts under a management group, AWS linked account costs, and AWS consolidated account costs.

    Azure portal automatically generates three, not two, types of Cost Management alerts: Budget, Credit, and Department spending quota alerts. Budget alerts notify customers when spending, based on usage or cost, reaches or exceeds the amount defined in the alert condition of the budget. Credit alerts notify customers when Azure credit monetary commitments are consumed. Department spending quota alerts notify customers when department spending reaches a fixed threshold of the quota.

    Budget alerts are available for customers with an Enterprise Agreement or a Microsoft Customer Agreement, and customers who use Web Direct or pay-as-you-go plans. Credit alerts and Department spending quota alerts are available only for customers with an Enterprise Agreement.

    | Alert type	| Enterprise Agreement	| Microsoft Customer Agreement	| Web direct/pay-as-you-go |
    |-------------------|-----------------------|-------------------------------|--------------------------|
    | Budget	| Yes	| Yes	| Yes |
    | Credit	| Yes	| No	| No |
    | Department spending quota	| Yes 	| No	| No |
    
    The limitations with integrating the AWS Cost and Usage report with Azure are:

    - Cost Management does not support cost reports that contain multiple currency types. An error message is shown if you select a scope that has numerous currencies.
    - Cloud connectors don't support AWS GovCloud (US), AWS Gov, or AWS China.
    
    Cost Management shows AWS usage costs only. Tax, support, refunds, RI, credits, or any other charge types are not supported yet.

18. Which of the following are characteristics of a public cloud? Choose three.

    A)Services are always free

    __B)Provider manages the network and virtualization software__

    C)Only one tenant is supported

    __D)Virtually unlimited storage__

    __E)Resource pooling__

    __*Anotacion:__

    The following are characteristics of a public cloud:

    - Virtually unlimited storage
    - Resource pooling
    - Provider manages the network and virtualization software
    
    In a public cloud, you can pay for the storage level that you want. You can have almost unlimited storage.

    In a public cloud, there is no dedicated hardware. The computing resources in the infrastructure provided by the provider are pooled together to server multiple customers.

    In a public cloud, the provider manages the network and virtualization software. The customer pays for the virtual machines and virtual networks that are provisioned, but the underlying structure is managed by the provider.

    In a public cloud, services are sometimes free, but generally have metered pricing. You pay for the services that you want when you want.

    A public cloud may support multiple tenants.


19. The Nutex Corporation needs to create, assign, and manage policies. Which of the following statements about Azure Policy are TRUE? (Choose two.)

    __A)Guest Configuration uses Desired State Configuration v2 to audit the settings of a Windows virtual machine.__

    B)Remediation tasks created to remediate non-compliant resources use the Audit policy effect.

    C)A new Policy Definition can be added from the PowerShell by using the New-PolicyDefinition cmdlet.

    D)A Policy Definition is a collection of Initiative Definitions that achieve a common goal.

    __E)A virtual machine that does not log into a specified Log Analytics workspace is deemed non-compliant.__

    __*Anotacion:__

    The following statements are true:

    - Guest Configuration uses Desired State Configuration v2 to audit the settings of a Windows virtual machine.
    - A virtual machine that does not log into a specified Log Analytics workspace is deemed non-compliant.
    
    Azure Policy can audit settings inside a machine. The validation is performed by the Guest Configuration extension and client. The extension, through the client, validates settings such as the configuration of the operating system, the configuration of the application, and the environment settings. To audit settings inside a machine, a virtual machine extension is enabled. The extension downloads applicable policy assignment and the corresponding configuration definition. You can use the Microsoft Desired State Configuration v2 utility to audit the settings of a Windows virtual machine.

    Virtual machines are deemed as noncompliant if they are logging to the Log Analytics workspace specified in the policy or initiative assignment. Azure Monitor feature reports this.

    A Policy Definition is not a collection of Initiative Definitions that achieve a common goal. A Policy Definition contains the conditions under which it is enforced and a defined effect that takes place if the conditions are met. An Initiative Definition is a collection of policy definitions that are tailored towards achieving a singular overarching goal.

    The cmdlet used to add a new Policy Definition is New-AzPolicyDefinition not the New-PolicyDefinition cmdlet. The New-PolicyDefinition cmdlet is a legacy cmdlet that is not used any more to create policy definitions.

    Remediation tasks created to remediate non-compliant resources do not use the Audit policy effect. Resources that are non-compliant to a deployIfNotExists policy can be put into a compliant state through Remediation. Remediation is accomplished by instructing Azure Policy to run the deployIfNotExists effect or the tag operations of the assigned policy on your existing resources. The Audit policy effect generates a warning event in the activity log but doesn't fail the request.


20. Jennifer has been asked to configure the authentication and authorization for the Nutex Sales app being deployed as an Azure web app. Only Active Directory authenticated Nutex sales representatives should be using the app, and the sales management team would like a single sign-on (SSO) experience. Which technologies will be required to accomplish the requested configuration? (Choose three.)

    __A)Active Directory Domain Services__

    __B)Active Directory Federated Services__

    __C)Azure Active Directory__

    D)OAuth 2.0

    E)Microsoft Account Authentication

    __*Anotacion:__

    Jennifer should configure Active Directory Domain Services (AD DS) and Azure Active Directory to synchronize using Active Directory Federated Services (AD FS). AD FS allows a user Single Sign-On access to applications by using AD FS as the identity provider to Azure Active Directory as a federation partner to integrate AD DS.

    While Azure web apps support authentication using a variety of authentication providers including Google, Facebook, Twitter, and Microsoft Account, a Microsoft Account will not provide the single sign-on (SSO) experience requested by management.

    Although Azure Active Directory supports using the OAuth 2.0 authentication protocol, it is not a requirement to provide single sign-on.

21. As an Azure administrator, you are required to enable multi-factor authentication (MFA) only for applications of the IT department. How should you implement this strategy?

    A)Azure AD Connect

    B)Azure Identity Protection

    __C)Azure Conditional Access policy__

    D)Azure Identity Hub

    __*Anotacion:__

    You should use an Azure Conditional Access policy. As shown in the graphics below, with a Conditional Access policy you can choose multiple cloud apps for which you will enable multi-factor authentication.

    The following graphic shows an Azure Conditional Access policy.

    The following shows how to grant MFA in a Conditional Access policy:

    You should not choose to use Azure Identity Protection because you cannot limit MFA to specific apps. Its aim is the detection and remediation of identity-based risks.

    You should not choose to use Azure Identity Hub because it cannot achieve the requirements of the question. It allows your users to sign into your iOS, Android, PHP, Windows, web, and Sharepoint apps using Facebook, ADFS, Office 365, and many more.

    You should not choose to use Azure AD Connect because it is used for synchronizing on-premises users to Azure AD.


22. The Nutex Corporation is considering shifting a considerable part of their offices to Germany. You are tasked with providing the impact analysis on the infrastructure and services hosted on Azure. Which of the following statements about Azure Germany are TRUE? (Choose two.)

    A)Configuration of the features available with Azure Germany is identical to Azure Global.

    __B)EU-based support staff provides technical and non-technical support to Azure Germany’s customers.__

    __C)Azure Germany offers a separate instance of Microsoft Azure services from within German data centers.__

    D)Azure Germany offers all the features available with Azure Global.

    __*Anotacion:__

    Azure Germany offers a separate instance of Microsoft Azure services from within German data centers, and EU-based support staff provides technical and non-technical support to Azure Germany’s customers.

    The data centers are in two cities: Frankfurt/Main and Magdeburg. The data centers connect through a private network. The German data centers ensure customer data remains in Germany. All customer data is exclusively stored in those data centers.

    Due to data privacy compliance and restrictions, technical and non-technical support for Azure Germany comes from EU-based support staff. The German data trustee supervises all support that requires platform access.

    Configuration of the features available with Azure Germany is not identical to Azure Global. There are configuration differences to Azure Global for features that are offered in Azure Germany, You should review your configurations and sample code to ensure that you are building and executing within the Azure Germany environment.

    Certain services and features that are available with Azure Global are not available with Azure Germany.


23. You are a system administrator for your organization. You have an on-premises setup where you host DNS servers and applications that are accessed locally and over the Internet. You have recently moved the Internet-accessible applications to the Azure cloud. During a recent DNS server failure, users and customers were unable to access the cloud-based applications, resulting in production loss. You want the DNS service to be more resilient and available to users and customers. Which of the following is the BEST way to achieve this objective?

    A)Roll back the applications from the Azure cloud to on-premises.

    B)Deploy an additional on-premises DNS server.

    __C)Host DNS zones in Azure DNS and integrate them with Azure-hosted applications.__

    D)No changes are required in the current setup.

    __*Anotacion:__

    In order to ensure that the DNS service is more resilient and available to users and customers, You should host DNS zones in Azure DNS and integrate them with Azure-hosted applications. Azure DNS is a cloud-based DNS service provided by Microsoft which is used to host and manage Domain Naming System (DNS) zones. A zone is a collection of DNS records. You can manage DNS zone data using the Azure portal, Azure PowerShell, Azure CLI, and Rest APIs. Azure DNS is hosted in the Azure infrastructure, which ensures that the service is more resilient to network failures than a DNS service on individual servers hosted on-premises or by third parties. You can fully integrate Azure DNS and Azure resources.

    Deploying an additional on-premises DNS server is not the correct answer. Because the business applications are hosted in the Azure cloud, deploying an additional DNS on-premises server is not a good choice. This would be required when business applications are hosted in an on-premises infrastructure and there is only a single DNS server to ensure that the DNS server is available if one server fails.

    Rolling back the applications from the Azure cloud to an on-premises setup is not the best solution. You would roll back the application in scenarios where there is an application-level failure after migrating to the Azure cloud and production will be halted for a longer duration than expected. It then would be wise to roll back the applications to the original setup until the issue has been fixed.

    You should not choose to make no changes in the current setup. This is not the correct answer because you have to make changes to the current setup in order to ensure the DNS service is more resilient and available to users and customers going forward.


24. You need to install an Azure Data Box Edge device from Microsoft to ensure that data is transferred securely to the cloud after it is preprocessed by removing Personally Identifiable Information (PII). What should you do? Choose the appropriate steps and place them in the correct order.

    __*Anotacion:__

    You should choose the following steps:

    1. Create and configure the Data Box Edge resource
    2. Install Azure Data Box Edge
    3. Assign the IP address of 192.168.100.5/24 on the computer connect to the Azure Data Box Edge device
    4. Activate the Azure Data Box Edge device
    5. Add and connect to shares on your Data Box Edge device
    6. Create an IoT Hub resource
    7. Configure a compute role on your Azure Data Box Edge device
    
    Azure Data Box Edge allows you to process data in a secure fashion, such as removing Personally Identifiable Information (PII) and sending it over the network.

    First, you need to create a Data Box Edge resource before you install a Data Box Edge physical device. You will then have to unpack the device and install the rack and associated cables.

    To complete the device setup, connect to the local web UI. You will assign the IP address of 192.168.100.5/24 on the computer connecting to the Azure Data Box Edge device.

    Next, connect your computer to PORT1 on the Data Box Edge physical device. You will then activate the physical device.

    After activation, you will add and connect to shares on the Data Box Edge device. Once the shares are added, then the Data Box Edge device can transfer data to Azure.

    You will then have to configure compute by creating an IoT Hub resource. Once the Edge compute rule is set up on the Edge device, an IoT device and an IoT Edge device are created.

    You cannot assign the IP address of 10.10.10.10/24 on the computer that connects to the Azure Data Box Edge. You need an adapter on the computer that connects to the Azure Data Box Edge to have an IP address of 192.168.100.5/24.


25. The Nutex Corporation purchased another company and is moving a large amount of that data to Azure. Which of the following statements about Azure Archive Storage are TRUE? (Choose three.)

    A)A large blob takes more time than several small blobs to rehydrate.

    __B)Data in an Archive blob cannot be copied to another Archive blob.__

    C)Blobs that are assigned an Archive Access tier must be first rehydrated to the Cool tier and later to the Hot tier.

    __D)The process of making archived Blob data online and reusable is known__ as rehydration.

    __E)Deleting or rehydrating an Archive blob before 180 days invites an early deletion fee from Microsoft.__

    __*Anotacion:__

    The following statements are true:

    - The process of making archived blob data online and reusable is known as rehydration.
    - Data in an Archive blob cannot be copied to another Archive blob.
    - Deleting or rehydrating an Archive blob before 180 days invites an early deletion fee from Microsoft.
    
    The data in a blob is in the Archive Access tier is offline and can't be read or modified. The archived Blob metadata is online and provides the blob’s properties. The two ways of retrieving and accessing data in an archived blob are rehydration and copying the Archive blob to a hot or cool tier. Rehydrating a blob can take up to hours.

    Rehydrating one large blob takes LESS time that rehydrating multiple small blobs.

    Early deletion fees DO NOT apply when archived blob is copied to an online blob. Blobs in the archive tier should be stored for a minimum of 180 days. Deleting or rehydrating archived blobs before 180 days will INCUR early deletion fees.

    The Copy Blob operation can be used to copy an archived blob. The original blob is not modified during or after the copy operation. Archive blobs can only be copied to online destination tiers, hot and cool. Copying an archived blob to another archived blob is NOT supported.

    Azure Archive Storage is an access tier available for blob storage. Archive Storage provides secure data transfer to the cloud using HTTPS and automatically secures that data at rest using 256-bit AES keys.

    Archive Storage can be used for long term backup retention, business policy mandated data archiving, and large volumes of video content and surveillance data backup retention.

    Archived blobs CAN be rehydrated to a hot or cool tier. The blob’s tier can be set by using the x-ms-access-tier request header.


26. You are the Azure administrator for the Nutex Corporation. You want to ensure that only users from the Marketing department can access the Azure AD application named CompanyApp through multi-factor authentication. They have to use multi-factor authentication from work and from their home office. What settings do you have to configure to ensure that only Marketing department users can access CompanyApp using a smartcard and PIN?

    __A)Switch Enable Access Rules to ON, Apply to Groups, and add the Marketing group. Under Rules, select Require multi-factor authentication.__

    B)Set Enable Access Rules to ON, Apply to All Users, select Except, and add the Marketing group. Under Rules, select Require multi-factor authentication.

    C)Set Enable Access Rules to OFF at Enable Access Rules, Apply to Groups, and add the Marketing group. Under Rules, select Require multi-factor authentication.

    D)Set Enable Access Rules to OFF at Enable Access Rules, Apply to All Users, select Except, and add the Marketing group. Under Rules, select Require multi-factor authentication.

    __*Anotacion:__

    You have to switch Enable Access Rules to ON, Apply to Groups, add the Marketing group, and select Require multi-factor authentication under Rules. First, you have to enable an application MFA access rule by configuring it to ON. You want only Marketing group to be able to use multi-factor authentication for that app, so you should create a single access rule based on one group. Because you want them to use a smartcard and PIN if they are at work or at home, you have to select Require multi-factor authentication.

    You should not configure Enable Access Rules to ON, Apply to All Users, select Except, add the Marketing group, and select Require multi-factor authentication under Rules. Here you select All Users with the exception of Marketing group. This means that all users have to use a smartcard and a PIN, without the Marketing department users.

    You should not configure OFF at Enable Access Rules. You need to enable access rules to apply multi-factor authentication requirements to the Marketing group and exclude other users from the requirement.

27. Your company’s Chief Financial Officer wants to have a tighter control on spending for the cloud infrastructure. She wants to have a tool to apply data analysis to the existing monthly costs of Azure. An associate recommends that she use Azure Advisor. Will this solution meet the CFO’s needs?

    A)Yes
    
    __B)No__
    
    __*Anotacion:__

    Azure Cost Management is a tool that can perform that task. Azure Advisor finds unused resources such as VMs and receives recommendations about Azure reserved instance purchases. Azure Advisor does not apply data analysis to the existing monthly costs of Azure.

    Azure Cost Management consists of Cost Management + Billing, which is a suite of tools that optimizes, analyzes, and manages your workload costs. You can use these tools to perform the following tasks:

    - Streamline bill-paying
    - Manage costs
    - Download cost and usage data from your invoice
    - Use data analysis to monthly costs
    - Limit spending through the use of thresholds
    - Find opportunities for changes in workloads that can reduce spending

28. The Nutex Corporation wants to enhance the security for its Azure Active Directory by utilizing the Azure AD Smart Lockout feature. Which of the following statements about the Azure AD Smart Lockout feature is TRUE? (Select One)

    __A)Azure AD Smart Lockout is tracked at the level of a data center.__

    B)An Azure AD account locks out for shorter durations for subsequent occurrences of account lockouts due to failed attempts.

    C)Azure AD Smart Lockout must be enabled explicitly for a new Azure AD deployment.

    D)An Azure AD administrator can unlock an Azure AD cloud account if the account is locked out by Azure AD Smart Lockout.

    __*Anotacion:__

    Azure AD Smart lockout locks out bad actors who are trying to guess the AD users’ passwords or use brute-force methods to log in. This feature recognizes sign-ins coming from valid users and treat them differently than ones from attackers and other unknown sources. Smart lockout locks out the attackers while letting your valid users continue to access their accounts and be productive.

    Azure AD Smart Lockout is tracked at the level of a data center. Each Azure AD data center tracks Smart Lockout independently. A user will have the (threshold_limit * datacenter_count) number of attempts when the user hits each data center.

    AD administrator CANNOT unlock a cloud account if it has been locked out by the Smart Lockout capability. The administrator must wait for the lockout duration to expire.

    By default, Smart Lockout locks the account from sign-in attempts for one minute after ten failed attempts. The account locks again after each subsequent failed sign-in attempt, for one minute at first and LONGER in subsequent attempts.

    Azure AD Smart Lockout does not have to be enabled explicitly for a new Azure AD deployment because iSmart lockout is always ON for all Azure AD deployments by default. With these default settings Microsoft offers a good mix of security and usability.


29. Match the cloud type with the correct definition.

    __*Anotacion:__

    IaaS is a cloud category that provides customers with network infrastructure, physical computing resources, data partitioning, scaling, security, and backup.

    PaaS is a cloud category that a customer uses to create their own applications and manage those applications without having to maintain the infrastructure to develop the applications.

    With SaaS, the customer uses software for a fee from a cloud provider. Typically, with SaaS, the software is stored in a central location and customers access the software on a subscription basis.

    Data Science as a Service (DSaaS) outsources the delivery of data that is gathered via progressive analytics applications. The data gathered via DSaaS is used to provide analysis against existing data. The analysis can be used for data science purposes, such as what type of customer would buy your product, how your product rates against your rivals, and other analytical issues.

    Network as a Service (NaaS) outsources services for network transport connectivity, such as routers and subnets.


30. After a recent breach, you have decided to increase the security of the Azure login process. Which Azure tool should you use?

    A)Credential Manager

    B)Azure Key Vault

    C)Azure Functions

    __D)Azure Multi-Factor Authentication (MFA)__

    E)Azure Information Protection (AIP)

    __*Anotacion:__

    Azure Multi-Factor Authentication (MFA) allows you to require multiple factors when authenticating. It works by requiring two or more of the following authentication methods:

    - A password, which is "something you know".
    - A device like a phone or hardware key, which is "something you have".
    - Biometrics such as face scan or fingerprint, which is "something you are".
    
    Azure Information Protection (AIP) is a cloud-based solution that is part of the Microsoft Information Protection (MIP) solution. It uses labels to classify assets and apply tags.

    All other choices are incorrect.

    Azure Key Vault is an encrypted solution for storing organizational; secrets such as passwords and encryption keys.

    Azure Functions allows you to write serverless code in your language of preference to handle events at scale, with minimal overhead and cost.

    Credential Manager is an applet in Control Panel on a Windows devices that allows you to view and delete logon information for websites, connected application and networks.


31. You’ve been appointed as an Azure Administrator at the Nutex Corporation. The Nutex Corporation has recently appointed two Helpdesk Administrators. You are asked to add their accounts to the Azure AD and grant them the role and privileges of a Helpdesk Administrator. What four steps should you perform in the Azure portal? Place the appropriate four steps in the correct order.

    __*Anotacion:__

    You should choose the following:

    | Correct order |
    |---------------|
    | Log in to the Azure portal |
    | Click Azure Active Directory > Users > New User |
    | Create the user account on the User page |
    | Specify the role of a Helpdesk Administrator on the User page |

    For an Azure AD user to manage Azure AD resources, the user must be assigned an appropriate role, based on the actions the user needs permission to perform.

    You must perform the following steps to grant the users the role of a Helpdesk Administrator:

    1. Log in to the Azure portal
    2. Click Azure Active Directory > Users > New user.
    3. Create a new account on the User page by specifying the name, username, and password.
    4. Select the Directory Role as a Helpdesk Administrator on the New User.
    
    Groups in Azure AD are a mere collection of users with similar non-RBAC privileges. So, creating a new group by the name of Helpdesk Administrator and assigning the new employees to the group does not assign them the privileges of the Helpdesk Administrator.

32. You have been told by your Chief Financial Officer to reduce costs. You want to implement Azure Spot Virtual Machines to reduce costs. Which of the following are true regarding Azure Spot Virtual Machines? Choose two.

    __A)Can be evicted based on the maximum price that you set.__

    B)Must be manually deleted if evicted

    __C)Can be evicted based on capacity__

    D)Are supported on B-series, D-series, and E-series

    E)Have same SLA as regular VMs

    __*Anotacion:__

    An Azure Spot VM can be evicted based on capacity or the configured maximum price. The availability of an Azure Spot VM depends on the capacity factors such as size, region, or time of day. If capacity is exceeded, the Azure Spot VM is evicted. You can configure an eviction policy to deallocate the VM or delete the VM.

    An Azure Spot VM is evicted if the maximum price is less than the current price. If the price for the VM has gone up and is currently greater than the maximum price on the VM, then the VM gets evicted. You are sent a message 30 seconds before eviction to notify you.

    An Azure Spot Virtual Machine takes advantage of cost savings with unused capacity but does not offer the same SLA or high availability guarantees of regular VMs.

    Azure Spot Virtual Machines are supported on all series except B-series and any promo versions of any size in a series. B-series VMs are low-cost virtual machines.

    If an Azure Spot VM is evicted, it is not deleted by default. However, you can configure the eviction policy to delete it when evicted automatically. When an Azure Spot VM is evicted, the underlying storage is deleted, so you are not charged for storage.


33. The Nutex Corporation has recently adopted Azure. You are the Azure Administrator at the Nutex Corporation. You recently learned that not all tasks can be accomplished from the Azure Portal, and that knowledge of Azure CLI and PowerShell is necessary to administer Azure. Which of the following statements about Azure CLI is TRUE?

    A)Azure Cloud Shell uses different Azure file shares for Bash and PowerShell.

    B)Azure Cloud Shell offers an integrated graphical text editor based on the Visual Studio Code editor.

    __C)Azure Cloud Shell times out after 20 minutes of no interactive activity.__

    D)If you mount a new file share, the new user image created for the $Home directory overwrites the user image used for the previous file share.

    __*Anotacion:__

    Azure Cloud Shell times out after 20 minutes of no interactive activity. Azure Cloud Shell is a browser-accessible shell for managing resources in Azure. You can choose the shell experience that best suits the way you work, either Bash or PowerShell.

    Azure Cloud Shell does not use different Azure file shares for Bash and PowerShell. Azure Cloud Shell utilizes Azure File Storage to persist files across sessions. On initial start, Cloud Shell prompts you to associate a new or existing file share to persist files across sessions.

    If you are mounting a new file share, a new user image is created for your $Home directory, but it does not overwrite the user image used for the previous file share. Your previous $Home image is kept in your previous file share.

    Azure Cloud Shell offers an integrated graphical text editor based on the open-source Monaco editor, not the Visual Studio Code editor.

34. The Nutex Corporation wants to adopt the Azure Monitor solution to collect metrics and logs for their services. You are part of the Azure Administrative team that must use the metrics and logs to ensure minimal disruption to services and come up with a plan to improve the performance of the services. Match the best practice to use Azure Monitor on the left with the benefit of using the best practice on the right.

    __*Anotacion:__

    You would map the best practice to use Azure Monitor with the benefit of using the best practice as follows:

    Visualize end-to-end transactions and connections -> Enable monitoring for all apps

    Improve the reponse time and quality of the incident management process -> Setup actionable alerts to notify and remediate

    Improve the response time and quality of the support functions -> Use role-based dashboards and workbooks for reporting

    Track the health and performance individual components for any investigations or debugging -> Bucket related resources in resource groups 

    Discover potential root causes when something fails -> Enable monitoring for all relevant components

    The following are the best practices and the benefits:

    - Enable monitoring for all apps and specify custom events, metrics, or page views that are relevant to your app or business.
    
    This helps easily visualize end-to-end transactions and connections across all the components.

    - Enable monitoring for all relevant components in the infrastructure – Azure Monitor can track the health and performance of the entire hybrid infrastructure, be it VMs, Containers, Storage, Network, or any other Azure service. Customers receive platform metrics, activity logs, and diagnostics logs from most of the Azure resources. Having monitoring enabled across the entire infrastructure helps discover a potential root cause when something fails.
    - Bucket related resources in resource groups – Use resource groups to bucket all the resources that make up the applications. Azure Monitor for resource groups provides a simple way to keep track of the health and performance of the entire full-stack application, and to drill down into respective components for any investigations or debugging.
    - Use role-based dashboards and workbooks for reporting – Azure Monitor is a monitoring solution for Azure resources, and you can create custom role-based dashboards from common metrics and logs.
    
    Workbooks help with knowledge sharing between devs and ops. Workbooks can be used as dynamic reports with metric charts and log queries, as well as troubleshooting guides that can be used by customer support or ops to handle basic problems.

    - Set up actionable alerts to notify and remediate – Alerts must be set up around a monitoring strategy and with automated actions for all predictable failure states. Alerts can be configured for static or dynamic thresholds and actions can be linked to all of them. The actions could be as simple as SMS, emails, push notifications, or voice calls for simple notifications.
     
    Alerts can even be fed to existing ITSM tools or any other alert management system through webhooks. This allows you to design remediation with Azure Automation Runbooks or use Auto-scaling in case of elastic workloads.


35. The Nutex Corporation wants to work with the US government for some Azure services. You must explain the capabilities of Azure Government to management. Which of the following statements about Azure Government are TRUE? (Choose three.)

    __A)Azure Government Marketplace contains only Bring Your Own License (BYOL) and Pay-As-You-Go (PayGo) images of products.__

    B)Azure Government uses does not use physically isolated data centers located strategically around the globe.

    __C)The Azure Pipelines service is not available with the Azure Government offering.__

    D)Hybrid Identity exists only on the cloud after the on-premises directory and cloud directory are synchronized.

    __E)Azure Government uses the same underlying technologies as global Azure.__

    __*Anotacion:__

    The following statements are true:

    - Azure Government uses the same underlying technologies as global Azure.
    - Azure Government Marketplace contains only Bring Your Own License (BYOL) and Pay-As-You-Go (PayGo) images of products.
    - The Azure Pipelines service is not available with the Azure Government offering
    
    Azure Government uses the same underlying technologies as global Azure, such as infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS), and Software-as-a-Service (SaaS). Azure Government includes auto scaling, Geo-Synchronous data replication, storage, data management, identity management, and network, among other services.

    The Azure Government Marketplace connects government agencies with independent software vendors (ISVs) that are offering their solutions in Azure Government. Azure Marketplace is different to the Azure Government Marketplace in the following ways:

    1. Only Bring Your Own License (BYOL) and Pay-As-You-Go (PayGo) images are available in Azure Government Marketplace.
    2. A different set of images is available in Azure Government Marketplace.
    
    Azure Pipelines is not available as part of Azure Government. Azure Pipelines is used by teams to configure continuous deployment for applications hosted in Azure subscriptions.

    Azure Government use physically isolated data centers located strategically around the globe. U.S. government agencies or their partners interested in cloud services that meet government security and compliance requirements can use Azure Government. Azure Government delivers a dedicated cloud enabling government agencies and their partners to transform mission-critical workloads to the cloud. Azure Government services handle data that is subject to certain government regulations and requirements, such as FedRAMP, NIST 800.171 (DIB), ITAR, IRS 1075, DoD L4, and CJIS.

    Hybrid entities do not exist only on the cloud after the on-premises directory and cloud directory are synchronized. Three identity models can be used with Azure Government. They are On-premises (the Active Directory environments that most customers use today), Cloud identities (those that originate, are managed, and exist only in Azure AD), and Hybrid identities (those that originate as on-premises identities but become hybrid through directory synchronization to Azure AD).

37. You are a system administrator for Verigon Corporation. You have been tasked with planning to move an on-premises business application to the Azure cloud. You are exploring Azure services and looking for a solution to move applications to a virtualized environment. Which of the following Azure services provides a portable environment for virtualized applications where you can run multiple instances of an application on a single host machine?

    A)Azure virtual machines

    B)Azure Functions

    C)Azure App Service

    __D)Azure Container Instances__

    __*Anotacion:__

    Azure Container Instances provides a portable environment for virtualized applications, allowing you to run multiple instances of an application on a single host machine. Azure Container Services is a Platform as a Service (PaaS) offering that manages isolated containers without orchestration. Containers managed by Azure Container Instances can be spun up faster than VMs and do not require the same overhead for management.  

    Azure VMs are not as portable as container instances. An Azure VM is an on-demand, scalable computing resource that can virtualize the IT infrastructure. You can host several Azure virtual machines on a single physical host and virtualize the environment. Container instances are a more portable environment than virtual machines since you can run multiple containers on a host.

    Azure App Service will not provide a portable environment for virtualized applications where you can run multiple instances of an application on a single host machine. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile backends. It is a PaaS offering for developing applications but is not a portable environment for running those applications like a container.

    Azure Functions will not provide a portable environment for virtualized applications where you can run multiple instances of an application on a single host machine. Azure Functions provides a serverless solution where you have to write less code, maintain less infrastructure, and save on costs. You focus on the code that you want to run, and Azure Functions handles the rest as part of the platform and infrastructure. It scales automatically based on demand and is best to use when demand is variable. Azure automatically allocates and deallocates the resources, and you are charged only for the CPU time when your function runs. Functions are a key component of serverless computing. It can be either stateless or stateful and can run locally or in the cloud. Azure Functions does not run virtualized applications but can be called by a virtualized application.


38. Dreamsuites Corporation's rapid growth has exponentially increased the need for their development teams to create new environments. Dreamsuites needs to ensure that these environments comply with Dreamsuites’ standards and requirements. What Azure service will allow for such a repeatable set of Azure resources?

    A)Azure DevTest Labs

    __B)Azure Blueprints__

    C)Azure Cosmos DB

    D)Azure Resource Manager templates

    E)Azure Batch

    __*Anotacion:__

    Azure Blueprints will meet Dreamsuites' needs. Blueprints allow templates, access controls, and policies to be deployed as a single compliance package. The components are referred to as artifacts and can include items such as Azure Resource Manager (ARM) templates, resource groups, policy assignments, and more. Blueprints are designed for environment setup.

    Azure Resource Manager templates can be a part (artifact) of an Azure Blueprint deployment, but as a standalone, they do not meet the scenario requirements. ARM templates don't exist natively in Azure.

    The Azure Cosmos DB is the backend database behind Azure Blueprints, but not the actual service required by the scenario.

    Azure Batch is used to create and manage large pools of virtual machines. It does not meet the requirements of this scenario.

    Azure DevTest labs allow for the quick provisioning of test environments, but this is only a subset of the standardization required in the scenario.

    Unlike Azure Resource Manager templates, Azure Blueprints retain a connection between the blueprint and what was deployed from it. This allows for tracking and auditing.


39. The Nutex Corporation wants you to get detailed reports for costs incurred to host and deliver apps on Azure. You want to create reports that provide insights into various factors that affect Azure costs. Which of the following factors affect Azure costs? (Choose four.)

    __A)Ingress data__

    __B)The resource types required by Azure Special services such as ExpressRoute__

    __C)The location where the product/service is hosted geographically__

    __D)Egress data__

    E)The number of reports that you download from the Azure portal

    F)The amount of time you spend on the Azure portal

    __*Anotacion:__

    The following factors affect Azure costs:

    - Ingress data
    - Egress data
    - The location where the product/service is hosted geographically
    - Special services, such as ExpressRoute
    - The resource types required by Azure services
    
    Ingress data is not always charged. The charges depend on the plan you use for Azure services. Ingress to Azure datacenters from on-premises environments is not charged, whereas ingress data from VPNs is charged.

    Azure charges customers based on the geographical locations in which the apps and services are deployed. Prices vary by the regions that define the geographical locations.

    Egress data is always charged. The charges depend on whether the egress data is for regular services, or VPN connectivity, or features such as ExpressRoute. The charges also depend on the regions that egressed data.

    Special services such as ExpressRoute incur additional costs because ExpressRoute lets customers extend their on-premises networks into the Microsoft cloud over a private connection facilitated by their connectivity provider.

    The services you purchase or products you deploy have specific resource types depending on the category of service or the product. The unit charges for resource types vary by category.

    The amount of time you spend on the Azure portal does not affect Azure costs. Microsoft does not charge you for using the Azure portal.

    The number of reports that you download from the Azure portal does not affect Azure costs. Downloading reports is not charged, and you can download unlimited reports.

40. The Nutex Corporation has an on-premises datacenter that hosts business-critical applications. As part of a cost reduction strategy, your organization is looking into moving to the cloud. You must understand the hierarchy of the organizational structure in Azure before moving resources from the on-premises location. Drag the levels from the left and drop them in the right column to create the top-down hierarchy of the organization in Azure.

    __*Anotacion:__

    When planning to move from on-premises to the cloud, you must understand the organizing structure for resources, which has four levels:

    - Management Groups – this will enable you manage access, policy, and compliance for multiple subscriptions. Subscriptions that are part of a management group will automatically inherit the conditions applied to the management group.
    - Subscriptions – this groups together user accounts and resources. Each subscription has a limit or quota on the number of resources you can create and use.
    - Resource groups – these are containers which have all the Azure resources, such as web apps, databases, and storage accounts.
    - Resources – these are instances of services that you will create, such as virtual machines, storage, or SQL databases.

41. The web team of the Nutex Corporation is developing a new enterprise solution. They are using the newest technologies, and the functionality is divided into many independent parts that can be maintained, scaled, or updated independently. Locally they have installed Docker on Windows 10 machines. They need a development environment for testing in Azure. What will you recommend as the fastest and simplest way to deploy the development environment in Azure?

    A)Azure Kubernetes Service (AKS)

    B)Azure Virtual Machine (VM)

    __C)Azure Container Instances (ACI)__

    D)Azure Functions

    __*Anotacion:__

    You should choose Azure Container Instances (ACI). ACI offers the fastest and simplest way to create, start up, and run a container which can be used as a development environment. ACI takes less than 30 seconds to start a container in the best scenarios, faster than using App Services to create a development environment.

    You should not choose Azure Kubernetes Service (AKS). It is an orchestration service that requires a YAML file for configuration. It is more complex and for more enterprise solutions.

    You should not create an Azure VM to host containers. You have to install Docker on it and then work with it. Also, the installation process requires to ensure if Hyper-V features are enabled.

    You should not choose Azure Functions, because they are used for serverless processing, and not for hosting containers.


42. Metroil Corporation deploys several proprietary applications. They want a cloud-based solution that will let each application run in its own "sandbox." As their IT consultant, you suggest using Azure Container Instances (ACI). What are some advantages to this method? (Choose three.)

    A)ACI automatically scales to meet high demand

    __B)You can access containers directly from a URL__

    C)ACI allows fast creation of virtual machines

    __D)ACI can access Linux containers__

    __E)ACI offers role-based access control (RBAC)__

    __*Anotacion:__

    With an Azure Container Instance (ACI), you can access containers directly from a URL. You just need an IP address and an FQDN.

    All connections must take place over HTTPS, using TLS to secure client connections.

    An ACI is not used to create virtual machines. An ACI is an alternative to using virtual machines. Each VM has to run its own copy of an operating system. Containers can share an underlying operating system. Sharing an underlying operating system makes containers "leaner" and more portable than VMs. Applications are isolated in containers just as they would be in a VM. Containers are faster because they do not have to boot the whole OS.

    An ACI can access both Linux and Windows containers. You can bring either of these from Docker Hub, which is a private container registry. Docker offers a library of images that you can start with.

    An ACI offers role-based access control (RBAC) via a set of built-in Azure roles. If you need to get more granular, you can define your own custom roles.

    While you can run several container instances in a container group, an ACI does not offer automatic scaling. There is no orchestration mechanism. If you have high demand, the Azure Kubernetes Service (AKS) is a better option.

    An ACI is just one of many solutions for running simple applications.

    Besides traditional VMs, you could also choose the Azure Service Fabric option or Azure App Services.

