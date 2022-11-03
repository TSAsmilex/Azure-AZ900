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

- **Autentificación** incluye verificación de identidad para acceder a aplicaciones y recursos, tiene funcionalidades como lista de contraseñas prohibidas, _multifactor aauthentication_ , reseteo de contraseñas y servicios _smart lockout_.
- **_Single sign-on_** (SSO) donde guardas un usuario y contraseña para acceder a multiples aplicaciones.
- **Gestion de aplicacion** gestionar tus aplicaciones cloud e in situ usando Azure AD.
- **Gestion de dispositivos** Azure AD permite registrar dispositivos lo que permite que sean gestionados a través de Microsoft Intune.

### ¿Como puedo conectar mi AD in situ con Azure AD?

Si tienes un entorno in situ con AD y Azure AD puedes conectarlos para no tener que duplicar identificaciones usando Azure AD Connect. Puedes usar funciones como SSO, _multifactor authentication_ y reseteo de contraseña para los dos sistemas.

### ¿Que es Azure Active Directory Domain Services?

Azure Active Directory Domain Services (Azure AD DS) es un servicio que proporciona gestion sobre servicios de dominio, como union de dominio, politicas de grupo, _lightweight directory access protocol_ (LDAP) y autentificación Kerberos/NTLM. Con Azure AD DS tienes el beneficio de un servicio de dominios sin la necesidad de desplegarlo, gestionarlo y parchear el controlador de dominios (_domain controller or DCs_) en la nube. Azure AD DS gestion de dominios te permite ejecutar aplicaciones de legado en la nube que no pueden usar métodos modenos de autentificación, este cambio se puede hacer sin necesidad de gestionar el AD DS de la nube. Azure AD DS usa Azure AD tenant para tener SSO.

### ¿Como funciona Azure AD DS?

Cuando creas un dominio gestionado por Azure AD DS defines un espacio de nombres único ó nombre de dominio. Dos servidores controladores de dominos de windows se despliegan en tu region Azure sleccionada, posteriormente no necesitas hacer nada ya que la plataforma Azure se encarga de gestionarlo.

### ¿Esta la información sincronizada?

NO ༼ つ ◕_◕ ༽つ

El dominio gestoniado realiza sincronización _one-way_ desde Azure AD hacia Azure AD DS y no a la inversa. Si estamos in situ, nuestro AD se conecta con Azure AD y después hacia Azure AD DS.

![Sincronización](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/azure-active-directory-sync-topology-7359f2b8.png)

## 7.3 Describir métodos de autentificación

La autentificación es el proceso de establer la identidad de una persona, servicio o dispositivo, lo cual requiere de credenciales para probar quienes son. Azure permite métodos como contraseñas, _singles sign-on_ (SSO), _multifactor authentication (MFA)_ y sin contraseña (*passwoedless*).

![Autentificación](https://learn.microsoft.com/en-us/training/wwl-azure/describe-azure-identity-access-security/media/passwordless-convenience-security-30321b4d.png)

### ¿Que es _single sign-on_?

SSO permite al usuario loguearse una única vez y posteriormente utilizar esa credencial para acceder a multiples recursos y aplicaciones de diferentes proveedores. Más identificaciones suponen más contraseñas a recordar y cambiar, además que incrementa el riesgo de un incidente de seguridad relacionado con las credenciales.

Con SSO el usuario debe recordar solo un ID y contraseña, por lo que no necesita encontrarse mensajes de loging en cada programa y simplifica el modelo de seguridad. SSO simplifica tambien la gesitón de usuarios e identificacioes, pero, SSO es solo tan seguro como su autentificador inicial ya que el resto de las conexiones posteriores se realizan en base a la seguridad de la inicial.

### ¿Que es _Multifactor Authentication_ (MFA)?

Consiste en pedir al usuario por un factor extra cuando intente acceder, lo que permite proteger un poco contra casos en los que la contraseña se ha visto comprometida.

Existen 3 categorías:
- Algo que el usuario sabe, una pregunta
- Algo que el usuario tiene, un mensaje sms con código al móvil
- Algo que el usuario es, detección biométrica

MFA ayuda a incrementar la seguridad frente a robo de credenciales(ID + contraseña).

**MFA en Azure AD** es lo mismo pero con propaganda.

### ¿Que es _passwordless authentication_?

Consiste en eliminar la contraseña y dejar solo los métodos de autentificacion MFA. Pero esta configuración debe ser establecida en tu dispositivo antes para que pueda funcionar. Azure ofrece 3 posibles occiones para este método:

- **_Windows Hello for business_** diseñado para windows, donde se establece un pin y biométricas para un único usuario. Utiliza _public key infrastructure_ (PKI) y SSO.
- **_Microsoft authenticator App_** aunque es un metrodo de MFA, puede usarse también eliminando la contraseña ya que convierte el móvil en una fuerte credencial, recibiendo un mensaje en el teléfono y usando sus biométricas o pin.
- **_FIDO2 security keys_** Fast IDentity Online que promueve estándars de autentificacion y reduce el uso de contraseñas como método de autentificación. (FIDO2 pertenece al estandar de la autentificación web _WebAuthn_). Las claves de seguridad FIDO2 son típicamente pendrive USB, Bluetooth o NFC, por lo que usando un dispositivo físico no hay contraseña a ser expuesta.

> Un ejemplo es nuestra tarjeta de identificacion del pc 

## 7.4 Describir identificaciones externas en Azure