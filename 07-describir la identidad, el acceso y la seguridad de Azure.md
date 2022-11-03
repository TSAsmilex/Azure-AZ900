# Identidad, acceso y seguridad en Azure

## 7.1 Introducción

- Describir Azure Active Directory (AD) y Azure AD DS.
- Describir los métodos de autenticación en Azure.
- Describir el acceso condicional de Azure AD.
- Describir el control de acceso basado en rol (RBAC) de Azure.
- Describir el concepto _Zero Trust_.
- Describir el propósito del modelo de defensa en profundidad.
- Describir el propósito de _Microsoft Defender for cloud_.

## 7.2 Azure directory services

_Azure Active Directory_ (Azure AD) es un servicio que permite loggearse y acceder a Microsoft Cloud y aplicaciones cloud que desarrolles. También puede usarse para mantener tus despliegues de AD in situ.

Para entornos in situ, Azure AD funciona sobre _Windows Server_ y proporciona servicios de identificación y gestión de acceso. Cuando proteges indentidades in situ con Active Directary, Microsoft no monitorea el intento de identificación. Cuando conectas Azure AD, Microsoft te ayuda a protegerte ya que revisa intentos de indentificación dudosos sin costes extra.

### ¿Quién usa Azure AD?

- **Administradores IT** usando Azure AD pueden controlar acceso a aplicaciones y recursos.
- **Desarrolladores de aplicaciones** Azure AD proporciona un acercamiento basado en el estandar para añadir funcionalidades, como SSO o credenciales de usuario.
- **Usuarios**: gestionan los accesos a sus cuentas y acciones relacionadas como restaurar contraseñas.
- **Suscriptores a servicios online**: como Microsoft Office o Azure con una única cuenta.

### ¿Qué hace Azure AD?

- **Autentificación** incluye verificación de identidad para acceder a aplicaciones y recursos, tiene funcionalidades como lista de contraseñas prohibidas, _multifactor aauthentication_ , reseteo de contraseñas y servicios _smart lockout_.
- **_Single sign-on_** (SSO) donde guardas un usuario y contraseña para acceder a multiples aplicaciones.
- **Gestion de aplicacion** gestionar tus aplicaciones cloud e in situ usando Azure AD.
- **Gestion de dispositivos** Azure AD permite registrar dispositivos lo que permite que sean gestionados a través de Microsoft Intune.

### ¿Cómo puedo conectar mi AD in situ con Azure AD?

Si tienes un entorno in situ con AD y Azure AD puedes conectarlos para no tener que duplicar identificaciones usando Azure AD Connect. Puedes usar funciones como SSO, _multifactor authentication_ y reseteo de contraseña para los dos sistemas.

### ¿Qué es Azure Active Directory Domain Services?

Azure Active Directory Domain Services (Azure AD DS) es un servicio que proporciona gestion sobre servicios de dominio, como union de dominio, politicas de grupo, _lightweight directory access protocol_ (LDAP) y autentificación Kerberos/NTLM. Con Azure AD DS tienes el beneficio de un servicio de dominios sin la necesidad de desplegarlo, gestionarlo y parchear el controlador de dominios (_domain controller or DCs_) en la nube. Azure AD DS gestion de dominios te permite ejecutar aplicaciones de legado en la nube que no pueden usar métodos modenos de autentificación, este cambio se puede hacer sin necesidad de gestionar el AD DS de la nube. Azure AD DS usa Azure AD tenant para tener SSO.

### ¿Cómo funciona Azure AD DS?

Cuando creas un dominio gestionado por Azure AD DS defines un espacio de nombres único ó nombre de dominio. Dos servidores controladores de dominos de windows se despliegan en tu region Azure sleccionada, posteriormente no necesitas hacer nada ya que la plataforma Azure se encarga de gestionarlo.

### ¿Esta la información sincronizada?

NO ༼ つ ◕_◕ ༽つ

En parte.

El dominio gestoniado realiza sincronización _one-way_ desde Azure AD hacia Azure AD DS y no a la inversa. Si estamos in situ, nuestro AD se conecta con Azure AD y después hacia Azure AD DS.

![Sincronización](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/azure-active-directory-sync-topology-7359f2b8.png)

## 7.3 Métodos de autentificación

La autentificación es el proceso de establer la identidad de una persona, servicio o dispositivo, lo cual requiere de credenciales para probar quienes son. Azure permite métodos como contraseñas, _singles sign-on_ (SSO), _multifactor authentication (MFA)_ y sin contraseña (*passwoedless*).

![Autentificación](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/passwordless-convenience-security-30321b4d.png)

### ¿Que es _single sign-on_?

SSO permite al usuario loguearse una única vez y posteriormente utilizar esa credencial para acceder a multiples recursos y aplicaciones de diferentes proveedores. Más identificaciones suponen más contraseñas a recordar y cambiar, además que incrementa el riesgo de un incidente de seguridad relacionado con las credenciales.

Con SSO el usuario debe recordar solo un ID y contraseña, por lo que no necesita encontrarse mensajes de logging en cada programa y simplifica el modelo de seguridad. SSO simplifica tambien la gesitón de usuarios e identificacioes, pero, SSO es solo tan seguro como su autentificador inicial ya que el resto de las conexiones posteriores se realizan en base a la seguridad de la inicial.

### ¿Que es _Multifactor Authentication_ (MFA)?

Consiste en pedir al usuario por un factor extra cuando intente acceder.

Piensa en qué ocurre cuando intentas iniciar sesión en una página web moderna. Se envía un código a tu correo o a tu teléfono, ¿verdad? En esto consiste el MFA.

La autenticación multifactor soluciona el problema de seguridad que presentan las contraseñas. Si un atacante consigue tu contraseña, seguiría necesitando otro medio para garantizar el acceso a tu cuenta.

Existen 3 categorías:

- Algo que el usuario sabe, una pregunta
- Algo que el usuario tiene, un mensaje sms con código al móvil
- Algo que el usuario es, detección biométrica

MFA ayuda a incrementar la seguridad frente a robo de credenciales (ID + contraseña).

**MFA en Azure AD** es lo mismo pero con propaganda.

### ¿Que es _passwordless authentication_?

Consiste en eliminar la contraseña y dejar solo los otros métodos de autentificación MFA. Para lograrlo, se debe configurar debidamente tu dispositivo. Azure ofrece 3 posibles occiones para este método:

- **_Windows Hello for business_** diseñado para windows, donde se establece un pin y biométricas para un único usuario. Utiliza _public key infrastructure_ (PKI) y SSO.
- **_Microsoft authenticator App_** aunque es un metrodo de MFA, puede usarse también eliminando la contraseña ya que convierte el móvil en una fuerte credencial, recibiendo un mensaje en el teléfono y usando sus biométricas o pin.
- **_FIDO2 security keys_** Fast IDentity Online que promueve estándares de autentificacion y reduce el uso de contraseñas como método de autentificación. (FIDO2 pertenece al estandar de la autentificación web _WebAuthn_). Las claves de seguridad FIDO2 son típicamente pendrive USB, Bluetooth o NFC, por lo que usando un dispositivo físico no hay contraseña a ser expuesta.

> Un ejemplo es nuestra tarjeta de identificacion del pc

## 7.4 Identificaciones externas en Azure

Se entiende como identificación externa a aquella que esta fuera de tu organización, por lo tanto debe de ponerse algún medio para poder identificarse, ya sea con el propio Azure o _Business to business_ (B2B).

![Imagen de identificación externa](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/azure-active-directory-external-identities-5a892021.png)

- **_Business to business collaboration_ (B2B)** , usando identificaciones de otras aplicaciones Microsoft u otras aplicaciones empresariales. (Google, facebook)
- **B2B conexión directa** , se establece conexión con otra organización Azure AD, lo que permite crear canales de equipos para compartir recursos con los usuarios externos. Los usuarios B2B no estan representados en tu directorio pero son administrados por el centro administrador de equipos.
- **Azure AD _business to customer_ (B2C)**, para aplicaciones SaaS que permiten a los usuario registrarse en la app o consumir de la misma usando Azure AD B2C como servicio de acceso e identificacion. (*Es una conexión B2B colaborativa pero para una aplicación en concreto*).

Usando Azure AD puedes gestionar los recursos y los límites de los usuarios invitados gracias a la incorporación der Azure AD B2B, pudiendo incluso preguntar directamente a los usuario o de manera automática para tener un meor control de acceso.
> Nota para Andres: Esta ultima parte es un poco confusa porque esta propaganda y texto mezclado, más o menso creo que resumen funciona, pero estoy confuso jajajajj

## 7.5 Accesos condicionales en Azure

Herramienta que permite o deniega acceso a recursos dependiendo del usuario. Ayuda a los administradores IT a autorizar diferentes usuarios y a proteger activos de la organización.

Permite tambien cambiar el metodo de MFA según el usuario, del cual recolecta información para reforzar la decisión de permitir o rechazar un acceso.
![Diargama de ejemplo](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/conditional-access-9bd268b8.png)

Siendo signal la locacion del usuario, el dispositivo o la aplicación a la intentan acceder. La decisión se toma si el usuario accede desde una localización conocida o no y posteriormente se le permite o deniega el acceso.

### ¿Cuándo usar el acceso condicional?

- MFA pero depende del rol, la localización o la red.
- Establecer acceso a servicios solo desde clientes conocidos.
- Establecer acceso solo desde dispositivos gestionados.
- Bloquear acceso desde fuentes no fiables.

## 7.6 Describir el _Azure role-based access control_ RBAC

El principio del mínimo privilegio explica que solo se debe dar acceso al minimo nivel necesario para completar una tarea.

Gestionar permisos por usuario es complicado por lo que se establece control por roles y se asgina permisos de acceso a ese rol. Con Azure RBAC puedes usar roles predifinidos  o crear nuevos, incluso asignando a individuos y grupos uno o más roles.

### ¿Como se aplica RBAC?

El RBAC se aplica a un _scope_ (alcance), tal y como indica la tabla, saliendo el nivel de usuario sobre ese alcance.

![Tabla RBAC](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/role-based-access-scope-4b12a8f3.png)

Azure RBAC es jerarquico, los permisos a un alcance padre se dan a todos los alcances hijos.

### ¿Como es Azure RBAC impuesta/aplicada?

Se aplica en cualquier acción realziada dentro de los recursos Azure y que pasa por el gestor de recursos de Azure. Azure RBAC no lo gestiona por ti en tu aplicación. RBAC usa un modelo de permitir, por defecto no tienes permitido nada y se te aginan roles con permisos.

## 7.7 Describir el modelo _zero trust_

Es un modelo de seguridad que asume el peor escenario posble y protege los recursos. Asume que habrá una violación y por ello verifica cada petición originada en una red no controlada.

Microsoft recomienda el modelo _Zero Trust_ proque:
- **Verificación explicita**, siempre autentifica y autoriza en todos los puntos de datos disponibles.
- **Privilegio mínimo** usando el modelo _Just-In-Time or Just-Enought-Access_ (JIT/JEA)
- **Asumir violaciones** minimiza el daño y el acceso, verifica encriptación _end-to-end_ y usa analíticas para detección de amenazas y emjora de defensas.

### Ajustando el _Zero Trust_

Aqui solo explica que en vez de proteger con una VPN, el método _Zero Trust_ sigue desconfiando de ti y requiere autentificación.

![Zero Trust](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/zero-trust-cf9202be.png)

## 7.8 Describir _defense-in-depth_

Es una estrategia de defensa que utiliza diferentes niveles y mecanismo para ralentizar el avance de un ataque no autorizado de acceso a datos.

### Capas de _defense-in-depth_

![Capas como las cebollas](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/defense-depth-486afc12.png)

Cada capa ofrece protección, por loq ue si una capa es violada el resto esta preparada para prevenir que prosiga. Con ello se elimina tener la seguridad como una única capa y en cambio se opta por varias, las cuales son:

- **Seguridad Física**, asegurando fisicamente el acceso al edificio y al hardware, con ello se puede prevenir robos o manipulaciones.

- **Identificación y acceso**, SSO y MFA, además esta capa da control de acceso y necesita evento de auditoria y cambios.

- **Perímetro** de red que protege frente ataques de red, identificando atacantes y eliminando su impacto. Como por ejemplo protección DDoS antes de que afecte a gran escala o usar cortafuesgos para identificar atacantes malicisioso.

- **Red** limita las comunicaciones entre los recursos internos, deniega por defecto, restringe el acceso a través de intenet e implementa seguridad de coenxión en la red in situ.

- **_Compute_**, Virus, sistemas sin parchar y sistemas no asegurados correctamente dejan hueco a ataques. Esta capa se centra en asegurar el acceso a máquinas virtuales e implementar protección _endpoint_ en dispositivos y mantener el systema actualizado y parcheado.

- **Aplicación** integra la seguridad en el ciclo de desarrollo de una aplicación para asegurar que nuestra aplicación esta libre de vulnerabiidades, guarda apropiadamente secretos sensibles de la applicación y hace un desarrollo con la seguridad como requisito de diseño.

- **Datos** aquello quebuscan los atacantes, debemos revisar la confidencialidad, integridad y disponibilidad de estos. Los atacantes generalmente buscan la base de adtos, el disco de las máquinas cirtuales, en servicios SaaS o datos de la nube.

##
