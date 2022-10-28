# Describir los componentes de la arquitectura del nucleo de azure

## 4.1 Introducción

Este módulo contiene describir, regiones de Azure, pares de regiones, regiones soberanas, disponibilidad de zones, centros de datos Azure, recursos Azure, subscripciones y administración de grupos .

## 4.2 Que es Microsoft Azure

Servicio de nube de Microsoft con Iaas, Paas y SaaS. Sigue los principios de la nube y sus funcionamientos, da más facilidades y configuración premontadas, tambien da acceso a docker y cubenetes. IA, IoT, base de datos, machine learning. Usan Azure portal, su web de control para azure.

**Que puedo hacer con azure?** Azure ofrece más de 100 servicios que te permiten ejecutar tus aplizaciones para explorar nuevos paradigmas como bots inteligentes. Mucha gente mueve sus programas a una máquina virtual en Azure, aunque Azure es mucho más, ya que ofrece IA o ML(machine learning)

## 4.3 Comienza con Azure accounts

Necesitas uan subscripción Azure para para poder usar sus recursos, pero puedes usar un grupo "Azure sandbox" durante el periodo de aprendizaje con módulo. Puedes tener cuenta de empresa y separar subscripciones de empleados segun sus necesitades.

[Resumen de cuentas Azure](https://learn.microsoft.com/en-us/training/wwl-azure/describe-core-architectural-components-of-azure/media/account-scope-levels-9ceb3abd.png)

**Crear cuenta** en su web tienes la versión gratis con 12 meses y las aplicaciones mas populares. Tambien existe una cuenta estudiante con el nivel similar a la gratuita. 

## 4.4 Ejercicios de Learn Sandbox

Puedes usar 10 sandboxes de 1 hora al día. Usan azure con poweshell, Azure esta hecho en python, la mitad de los comandos que te dicen probar no fufan 👍.

## 4.5 Describir la infraestructura física de Azure

La infraestructura se asemeja mucho a la de servidores tradicionales. Los centros de datos son prácticamente iguales a los de otros servidores corporativos clásicos. 

Empieza con centros de datos de gran tamaño, preparados en potencia, refrigeración y conexión. Se dividen estos centros en regiones (geográficas para mejor rendimiento y conexión). Dentro de cada Región existen zonas disponibles, que son centros de datos dentro de la misma región. Es posible replicar tu aplicacion en diferentes zonas diponibles pero con un coste asociado.

Existen 3 categorías: servicio de zona (solo en una zona), servicios de zona redundantes (se puede replicar entre zonas) y servicios no regionales (sin zona asociada y siempre disponible). Existen pares de regiones dentro de la misma zona geográficas, que permiten tener más seguridad y mantenimiento de servicios. 

Por otra parte, algunas regiones no pareadas se encuentran aisladas. A estas se les denomina llamadas regiones sobrenas.

## 4.6 Describir la gestion de la infraestructura de Azure

**Recursos Azure y grupos de recursos**, los grupos de recursos son recursos que puedes agrupar en un paquete(si, literalmente es una mierda de explicacion pero así aparece),puedes mover recursos entre paquetes, un recurso no puede estar en más de un grupo. Puedes aplocar acciones a un grupo y se aplicará a todos los recursos, ejecutar, borrar, quitar acceso, dar acceso. 

**Subscripciones Azure** 

![Cuenta azure](https://learn.microsoft.com/en-us/training/wwl-azure/describe-core-architectural-components-of-azure/media/subscriptions-d415577b.png)

Una cuenta azure se identifica en Azure Active Directry, cada cuenta puede tener multiples subscrupciones para manejar las cuentas de diversoso usuarios, puedes separarlos por foma de pago o establecer diferentes niveles de política de acceso para restringir el uso de los productos.

**Crear subscripciones adicionales de Azure** Igual que los grupos de recuros  puedes dividir por funciones o acceso, se dividen en 3 tipos, por entorno(subscripciones con desarrollo, testeo y seguridad), por organización estructural(puedes dar a un departamento pocos recursos y al departamente IT todos) y por facturación(separando costes y para tener un mejor control de los posibles costes).

![Gerarquía de grupos](https://learn.microsoft.com/en-us/training/wwl-azure/describe-core-architectural-components-of-azure/media/management-groups-subscriptions-dfd5a108.png)

La gerarquía de grupos permite tener un arbol de hasta seis niveles de profundidad sin incluir el Root. Cada grupo gestionado solo permite un padre del que heredan su subscripción.

## 4.7 Ejercicio crear recurso azure

## 4.8 Preguntas

[Respuestas](./Recopilacion%20preguntas%20Azure.md)

## 4.9 Recapitulación