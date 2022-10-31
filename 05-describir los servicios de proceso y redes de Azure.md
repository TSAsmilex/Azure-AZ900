# Describir los servicios de proceso y redes de Azure

## 5.1 Introducción

Este módulo tien 14 apartados, en los que se aprenderá de máquinas virutales, Azure escritorio virtual, recursos requeridos para máquinas virtuales, Azure web Apps, re virtual y endpoints.

## 5.2 Describir máquinas virtuales de Azure

Las máquinas virtuales pertenecen a IaaS, con todo lo que ello conlleva. 

**Conjutnos de escalado de máquinas virtuales** permiten configurar y gestionar grupos de MV identicas, permitiendo estabilizar carga de trabajo y monitorización. Azure se encarga de automatizas este trabajo, incrementando y decrementando el numero de VM.

**Conjuntos de disponibilidad de máquinas virtuales** son otra herramienta para hacer entornos más disponibles y seguros. La disponibilidad se establece haciendo grupos de dos maneras: actualziar dominio(estos grupos se reinician conjuntamente y permite aplicar als actualziaciones, en el tiempo de mantenimiento se recuperarán) y dominio de error (se agrupoan por conexion electrica física, por lo que se sabrá cuando ocurre un corte de suministro. Se suelen ahacer varias grupos de error para evitar que todas las VM caigan).

**Cuando usar VM** durante testeo y desarrollo, ejecución de aplicaciones en la nube, extensión de un centro de datos a la nube y para recuperación de desastres.

## 5.3 Ejercicio

## 5.4 Describir el escritorio virtual de Azure

Ofrece un windows accesible desde pc/ios/android en la nube para usarlo con la interfaz de usuario normal. Escalable como cualquier MV.

**Mejora de seguridad** usando Azure Actuva Directory. Se puede estableces autentificadores "multifactor" y control de acceso por roles a los usuarios. Los datos estan en la máquina fisica y las aplicaciones estan en la nube, por lo que mejora el riesgo de perder datos confidenciales. Existen máquinas de Windows 10 y 11 que permiten multi-usuario en una sola máquina virtual.

## 5.5 Describir contenedores Azure

MV suponen una reducción del coste en hardware para la empresa, pero si quieres aumentar la productividad lanzando multiples instancas de una aplicación en una misma máquina virtual los contenedores son mejores.

**¿Que son contenedores?** , son entornos virtualizados. En diferencia a las MV no gestionas el sistema operativo de un contenedor, ya que son ligeros se despliegan más rápido. 

**MV vs Contenedores** MV es lo que es, una simulación de un ordenador completo, pero cada máquina virtual solo puede correr un único sistema operativo. El contenedor solo tiene una aplicación y sus dependencias, el host-container se encarga de controlar el SO de los contenedores. Los contenedores son ligeros y permiten mantener la separación entre ellos. 

**Contenedores Azure**, son PaaS y te permite subir tus contenedores y Azure lanzara sus sercicios. Los contenedores son soluciones para la arquitectura de microservicios, donde se separa la solución en pequeñas e independientes piezas.

## 5.6 Describir Azure Funtions

Servicio _serverles computing_ que se encarga de mantener las MV y los contenedores activos. Ayudar a la gestion de un servidor, actualizaciones por ejemplo, evitando que solo tengas que centrarte en desarrollo. 

**Beneficios de  Azure Funtions** son perfectos para cuando solo necesitas preocuparte de que tu código se encuentre ejecutandose. Azure Funtions escala automáticamente, tambien se encarga de lanzar los servicios Azure necesarios y de limpiar los recursos no usados, por lo que no te cobrarán extra. Funtions es esencial para el _serverless computing_ ya que peromite correr cualquier tipo de código sin necesidad de preparar un entorno.

## 5.7 Describir las opciones de hospedaje de aplicaciones

