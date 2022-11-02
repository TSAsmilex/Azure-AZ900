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

20. A resource group can contain resources from multiple Azure regions.

    __a) Yes__

    b) No

21. You have a resource group named RG1. You need to prevent the creation of virtual machines only in RG1. The solution must ensure that other objects can be created in RG1. What should you use?

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
    