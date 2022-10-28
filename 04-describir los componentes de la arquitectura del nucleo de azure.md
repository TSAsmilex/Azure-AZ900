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

Puedes usar 10 sandboxes de 1 hora al día. Usan azure con poweshell, Azure esta hecho en python, la mitad de los comandos que te dicen probar no fufan 👍

## 4.5 Describir la infraestructura física de Azure

Empieza con centros de datos de gran tamaño, preparados en potencia, refrigeración y conexión. Se dividen estos centros en regiones (geográficas para mejor rendimiento y conexión). Dentro de cada Región existen zonas disponibles, que son centros de datos dentro de la misma región. Es posible replicar tu aplicacion en diferentes zonas diponibles pero con un coste asociado. Existen 3 categorías, servicio de zona (solo en una zona), servicios de zona redundantes(se puede replicar entre zonas) y servicios no regionales( sin zona asociada y siempre disponible). Existen pares de regiones dentro de la misma zona geográficas, que permiten tener más seguridad y mantenimiento de servicios. Existen regiones no en pares que se encuentran aisladas, llamadas regiones sobrenas.




