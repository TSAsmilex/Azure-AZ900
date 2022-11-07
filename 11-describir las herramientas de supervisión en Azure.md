# Describir las herramientas de supervisión en Azure

## 11.1 Introducción

- Describir el propósito de Azure Advisor
- Describir el estado del servicio de Azure
- Describir Azure Monitor, incluidos Azure Log Analytics, Azure Monitor Alerts y Application Insights

## 11.2 Describir el propósito de Azure Advisor

Evalua tus recursos Azure y hacer recomendaciones para mejorar su fiabilidad, seguridad y rendimiento, alcancer objetivos de operaciones y reducir el coste. Las recomendaciones estan disponible para Azure Portal y la API para recibir notificaciones de alerta. 

Las recomendaciones se dividen en 5 categorías:

- **Fiabilidad**
- **Seguridad**
- **Rendimiento**
- **_Operational Excellence_** para un flujo de trabajo eficiente y buenas practicas de despliegue.
- **Costes**

## 11.3 Describir Azure Service Health

Permite mantener vigilados los recursos Azure, especificamente los desplegados y el estado general de Azure. Ofrece servicios como:

- **Azure Status** es una imagen amplia del estado de Azure, una vista global del estado de salud de todos los serivicios de Azure a través de todas las regiones.
- **Service Health** es una vista más estrecha de los serivcios Azure y regniones, se dentra en los que estas usando. Puedes establecer alertas para problemas de serivicio, mantenmienentos o cambios que afecten a tus servicios Azure y regiones.
- **Resource Health** es una vista a medida de los recursos Azure. Da información de recursos específicos o de istancias concretas de máquinas virtuales.

Usando las 3 puedes ver toda la información de los servicios Azure.

## 11.4 Describir Azure Monitor

Monitorea, se que es una respuesta inexperada el hecho de que monitoree, pero es lo que hace, monitorea recursos en nube e in situ.

![Resumen](https://learn.microsoft.com/en-us/training/wwl-azure/describe-monitoring-tools-azure/media/azure-monitor-overview-614cd2fd.svg)

### Azure Log Analytics

Herramienta para escribir y lanzar consultas sobre los logs de Azure Montior. Es una herramienta robusta para filtrar, ordenar y analizar , puedes incluso realziar consultas especializadas.

### Azure Monitor Alerts
 
Es una manera utomática de estar informado cuando Azure Monitor detecta un límite ser cruzado, te envia una notificación de alerta. Las alertas pueden monitorear los logs y lanzar distintos eventos según las metricas establecidas.

### Application Insights

Son una caracteristica de Azure Monitor, para aplciaciones web, esten ejecutandose en Azure, in situ o en un sitio de entornos nube diferente. Puedes usar el SDK en tu aplciación o usar directamente _Application insight_. La información obtenida es tal como:
- Ratios de respuesta, peticiones y fallos.
- Ratios de dependenias, tiempos de respuesta con respecto a servicios externos.
- Vista de páginas y reportes de rendimiento de carga para cada navegador.
- Llamadas AJAX con sus ratios de fallos y tiempo de respuesta.
- Usuarios y sesiones.
- Rendimeinto de servidores 

## 11.5 Preguntas

[Respuestas](./Recopilacion%20preguntas%20Azure.md)

## 11.6 sumario