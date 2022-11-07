# Describir las características y herramientas de Azure para el gobierno y el cumplimiento

## 9.1 Introducción

- Describir el propósito de Azure Blueprints
- Describir el propósito de Azure Policy
- Describir el propósito de los bloqueos de recursos
- Describir el propósito del portal de confianza de servicios

## 9.2 Decribir el propósito de Azure Blueprints

Azure Blueprint te permite estandarizar subscripciones a la nube y ambientes de desarrollo así como definir configuraciones repetibles o polítcas a aplicar para asignarlas rápidamente sin tener que dedicat tiempo a la configuración de los mismos. 

### ¿Que son artefactos?

Cada componente de un _blueprint_. Puede tener o no parámetros adicionales, llamados configuraciones. Puedes definir el valor de un parámentro cuando creas una definición en el _blueprint_ o cuando lo asignas, haciendo así que un mismo _blueprint_ sea flexible. Azure Blueprint desplegará un nuevo entorno de desarrollo con todos los requisitos de configuración como roles, políticas, Azure Resource Manager templates y grupos de recursos.

### ¿Como Azure Blueprint ayuda a monitorizar despliegues?

Azure Blueprint es "versisonable", ya que puedes modificar la configuración inicial e irla incrementando conjunto a tu aplicación. Azure Blueprint tiene su propio "Git", es decir, tiene sistema de versionado.

## 9.3 Describir el propósito de Azure Policy

Permiten crear, asignar y gestionar políticas de control(como reglas de configuración) o auditar recursos.

### ¿Como Azure Policy define políticas?

Puedes definir políticas individuales o grupos relacionados a políticas, conocidos como iniciativas. Las políticas asociadas a grupos pueden establecerse a diferentes niveles, grupos, recursos, subscripciones, etc. Tiene definiciones ya predeterminadas, además que evalua las máquinas virtuales y las monitorea, también en algunos casos Azure Policy puede automaticamente controlar recursos con compulados y configuraciones para verificar la integridad de los recursos. Esta integrado con Azure DevOps para aplicar integración continua.

### ¿Que son las iniciativas Azure Policy?

Es una manera de agrupar políticas relacionadas juntas, algunas definiciones incluidas son:
- **Monitorear en el centro ede seguridad bases de datos SQL no encriptadas**
- **Monitorear vulnerabilidades del sistema oeprativo en el centro de seguridad**
- **Monitorea _Endpoint protection_ perdidos en el centro de seguridad**

## 9.4 Describir el proposito de los cerrojos de recursos.

Los cerrojos protegen de ser borrados o cambiados accidentalmente, ya que incluso con Azure RBAC existe el reisgo de que recursos críticos sean borrados o cambiados, se pueden aplicar a grupos, individualmente o a subscripciones.

### Tipos de cerrojos de recursos

- Borrado, se puede leer y modificar
- Solo lectura, pues eso, solo lectura 😆

### ¿Como gestiono los cerrojos de recursos?

Desde Azure portal, PowerShell, the Azure CLI o Azure Resource Manager template.

### ¿Como borro o cambia un cerrojo?

No se modificar un cerrojo directamente, debe borrarse y reaplicarse de nuevo.

## 9.5 Ejercicio

> No lo he realizado porque es desde Azure Portal y esta a nivel de saber leer español básico para poder hacerlo

## 9.6 Descrubir el propósito de _Microsoft Service Trust portal_

Es un portal que proporciona contenido, herramientas y otros recursos de Microsoft seguridad, privacidad y practicas de conformidad. Básicamente es un portal para conocer la manera de implementar de Microsoft y seguir sus practicas.

### Acceder a _Service Trust Portal_

Propaganda con proganada en tu propaganda. Simplemente te dice donde pulsar en su portal.

## 9.7 Preguntas

[Respuesta](./Recopilacion%20preguntas%20Azure.md)

## 9.8 Sumario
