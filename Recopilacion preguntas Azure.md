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

2. Tradewind Traders is planning to migrate to Azure cloud services. The company currently operates multiple MySQL database solutions on-premises. Management has asked you to spend some time researching the MySQL features available in Azure specifically the ability to perform automatic backups and point in time restores. You have determined that these features are available for MySQL in Azure. 

For how many days are point-in-time restores supported for MySQL in Azure?

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
   
32. Tradewind Traders has recently migrated to Azure cloud services and management wants to start benefiting from DevOps. DevOps is a new approach that helps to align technical teams to work towards their common goal. Which of the following provides a suite of services that address each stage of the software development lifecycle (SDL)?

    __a) Azure DevOps Services__

    b) Azure DevTest Labs

    c) GitHub and GitHub Actions
    
    __*Anotacion:__Azure DevOps is a suite of services that address every stage of the Software Development Lifecycle (SDL).
   


