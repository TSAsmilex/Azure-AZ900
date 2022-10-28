# Descripción de la informática en la nube

## 1.1 Introducción a los aspectos básicos

Azure es una plataforma de servicios en la nube.
Ofrece la posibilidad de ejecución de máquinas virtuales o "equipos virtualizados".
Azure ofrece servicios de nube como, almacenamiento remoto, hospedaje de datos, administración de cuentas y funcionalidades como IA o IoT.
Aspectos básicos de Azure = procesos, red y almacenamiento.

## 1.2 Introducción a la informática en la nube

*Nada a descatacar*

## 1.3 Qué es la informática en la nube

Infraestructura TI común como, máquinas virtuales, bases de datos, redes y almacenamiento, servicios como IoT, ML e IA.

La infraestructura física no restringe a la informática en la nube de TI.

### Resumen del video incluido

Pagar por los servicios en la nube + alguien que lo mantenga.(Es como comprar un ordenador en la nube dice el video).

Los servicios básicos de un proveedor nube son potencia de proceso y almacenamiento.

Escalabilidad tanto en potencia de cómputo como en espacio de almacenamiento. "Solo se paga por lo que consumes"

## 1.4 Descripción del modelo de responsabilidad compartida

En los **modelos tradicionales**, la compañía se debía encargar del mantenimiento físico y remplazo de servidores. IT se encarga de mantener todo el software activo y actualiado(parches y versiones).

Con el **modelo de responsabilidad compartida**, la seguridad física, equipo, y red de conexiones son responsabilidad del proveedor de la nube. El usuario o consumidor es responsable de la información y de la seguridad de acceso.

**On-premises** (es decir, el modelo tradicional) tiene la responsabilidad del 100%. Con IaaS (*Infraestructure as a Service*), PaaS (*Platform as a Service*), y SaaS (*Software as a Service*) estas resposabilidades empiezan a delegarse en la nube (de menor a mayor medida). Pero el cliente siempre será responsable de la información, quien tiene acceso a ella y que dispositivos pueden acceder. El proveedor nube siempre será responsable de la infraestructura física, la responsabilidad software depende del nivel del modelo de servicio de la nube.

![Tabla resumen de las diferentes responsabilidades.](https://learn.microsoft.com/en-us/training/wwl-azure/describe-cloud-compute/media/shared-responsibility-b3829bfe.svg)

## 1.5 Definir modelos de la nube

Existen tres modelos principales de cloud: privado, público e híbrido.

Los **privados** son una evolución de los centros de datos corporativos. Es un cloud usado por una única entidad o compañía, que pese a tener un mayor coste, le da más control. Puede estar alojado en su propio centro de datos, en otro o incluso ser de un tercero.

En contrapartida, los **públicos** están completamente gestionados por un tercero. Cualquiera puede acceder y usar sus recursos.

Los **híbridos** utilizan una mezcla de clouds privadas y públicas interconectadas. Se usa una nube privada para suplir un incremente de demanda temporal, la cual posee una capa extra de protección. Los usuarios pueden escoger si desplegar en la nube privada o púlica.

| **Cloud pública**                                         | **Cloud privada**                                                                               | **Cloud híbrida**                                                               |
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| No hace falta invertir en bienes de capital para crecer.  | Control total sobre los recursos y la seguridad del sistema.                                    | Es la que proporciona mayor flexibilidad de todas.                              |
| Se pueden aprovisionar aplicaciones rápidamente.          | No se mezclan los datos de una organización con cualquier otra (=> aislamiento de información). | Las organizaciones determinan dónde quieren correr sus aplicaciones.            |
| Las organizaciones pagan por lo que usan.                 | Hace falta comprar hardware, instalarlo y mantenerlo.                                           | Control sobre la seguridad, cumplimiento de la normativa y requisitos legales.  |
| No se tiene un control total sobre los recursos           |                                                                                                 |                                                                                 |

El concepto de **multi-cloud** surge con la idea utilizar diferentes proveedores de nube, aprovechando las mejores características de cada uno. Esto tiene el inconveniente de que tienes que manejar varios sistemas al mismo tiempo, así como interconectarlos, lo cual presenta una sobrecarga añadida. 

Por último, existen un par de productos de Azure denominados **Azure Arc** (gestión de entornos de clouds) y **Azure VMWare Solutions** (Máquinas de VMWare desplegadas en Azure)

**Solución Azure VMware**

Si tienes VMware en una nube privada con VMware Solution puedes usar tu WMware en Azure con integración y escalabilidad sin notarlo.

## 1.6 Describir modelos basados en consumo

**Capital expenditure (CapEx)** son referentes a los gastos de materiales o  recursos físicos que solo se compran una vez. Edificios, ordenadores, coches de empresa, etc...

**Operational expenditure (OpEx)** referente al gasto en servicios y productos. Alquileres, pago de credenciales o pago de servicios en la nube.

Los servicios en la nube estan dentro de OpEx, debido a que no se paga por una infraestructura ni sus gastos derivados sino que pagas por los recursos IT que se utilizan.

Entre sus beneficios se incluyen:

1. Sin coste de entrada.
2. No es necesario comprar infraestructuras innecesarias dependiendo del uso de tus usuarios.
3. Pago solo por uso.

En el modelo tradicional es necesario preveer el gasto y las capacidades de tu centro de datos y arreglar esos errores de potencia, temperatura o conexión puede requerir mucho tiempo y coste.

En el mododelo de la nube no existen estos problemas ya que requiere solo añadir demanda e incrementar las máquinas virtuales.

### Comparar precios de modelos de nube

Debido a que en los modelos de nube solo pagas por lo usado permite la reducción de costes y de infraestructuras a la par que escalar tu negocia a necesidad.

Ya que no necesitas realizar el mantemiento de las infraestructuras (lo hace el proveedor del servicio en la nube), pagas solo por el tiempo que uses sus servicios. Estos servicios ayudan a traer soluciones a problemas de gran tamaño y soluciones a los usuarios.

## 1.7 Preguntas

[Respuestas](Recopilacion%20preguntas%20Azure.md).

## 1.8 Recapitulación