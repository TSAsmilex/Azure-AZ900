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