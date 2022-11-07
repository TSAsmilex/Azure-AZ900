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