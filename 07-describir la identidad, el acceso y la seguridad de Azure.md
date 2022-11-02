# Describir la identidad, el acceso y la seguridad de Azure

# 7.1 Introducción

- Describir Azure Active Directory (AD) y Azure AD DS.
- Describir los métodos de autenticación en Azure.
- Describir el acceso condicional de Azure AD.
- Describir el control de acceso basado en rol (RBAC) de Azure.
- Describir el concepto _Zero Trust_.
- Describir el propósito del modelo de defensa en profundidad.
- Describir el propósito de _Microsoft Defender for cloud_.

## 7.2 Describir servicios Azure Directory

_Azure Active Directory_ (Azure AD) es un servicio que permite loguease y acceder a Microsoft Cloud y aplicaciones cloud que tu desarrolles, además puede usarse in situ.

Para entornos in situ, Azure AD funciona sobre _Windows Server_ y proporciona servicios de identificación y gestión de acceso. Cuando proteges indentidades in situ con Active Directary, Microsoft no monitorea el intento de identificación. Cuando conectas Azure AD, microsoft te ayuda a protegerte ya que revisa intentos de indentificación dudosos sin costes extra.

### ¿Quien usa Azure AD?

- **Administradores IT** usando Azure AD pueden controlar acceso a aplicaciones y recursos.
- **Desarrolladores de aplicaciones** Azure AD proporciona un acercamiento basado en el estandar para añadir funcionalidades SSO o credenciales de usuario.
- **Usuarios** pueden gestionar sus identificaciones y hacer acciones de mantenimiento.
- **_Online service subscribers_** como Micrisoft office ó Azure con una única cuenta.

### ¿Que hace Azure AD?