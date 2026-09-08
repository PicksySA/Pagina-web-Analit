# AnalytIA Sports Website

Web oficial y legal de AnalytIA Sports.

El sitio está preparado como web estática para GitHub Pages y para funcionar
más adelante bajo el dominio:

```text
https://analytiasports.es
```

No usa backend, base de datos, cookies, analytics, JavaScript ni dependencias
externas obligatorias.

## Páginas

- `index.html`: página principal.
- `privacy-policy.html`: política de privacidad.
- `terms.html`: términos y condiciones.
- `delete-account.html`: eliminación de cuenta.
- `support.html`: soporte.
- `auth/confirmed/index.html`: confirmación de email de Supabase Auth.
- `auth/reset-password/index.html`: alias para redirigir recuperación de contraseña al flujo existente.
- `404.html`: página de error.
- `assets/css/styles.css`: estilos.

## Activar GitHub Pages

En GitHub:

```text
Settings → Pages → Deploy from branch → main → root
```

## URLs

Con dominio propio:

- `https://analytiasports.es`
- `https://analytiasports.es/privacy-policy.html`
- `https://analytiasports.es/terms.html`
- `https://analytiasports.es/delete-account.html`
- `https://analytiasports.es/support.html`
- `https://analytiasports.es/auth/confirmed`
- `https://analytiasports.es/auth/reset-password`

## Supabase Auth

Para el dominio de producción indicado para Supabase, configurar:

```text
Site URL:
https://analytiasports.com

Redirect URLs:
https://analytiasports.com/auth/confirmed
https://analytiasports.com/auth/reset-password
```

La página `/auth/confirmed` usa provisionalmente el deep link:

```text
analytiasports://auth/confirmed
```

Queda pendiente configurar el deep link/app link equivalente en la app móvil
antes de depender de este botón en producción.

## Revisión de publicación

- Identidad confirmada el 2026-09-08: Sergio Serrano Molina y Aaro Gonzalez
  Andreu como corresponsables del tratamiento, con
  `soporte@analytiasports.es` como contacto comun. Se han utilizado los nombres
  exactamente como los ha facilitado el usuario.
- Presentacion: responsables, derechos y contacto se agrupan al final de la
  politica, sin desplegable ni caja destacada. La identidad sigue visible y
  localizable en `privacy-policy.html#privacy-contact`.
- El correo se muestra una vez en privacidad y en soporte. Los terminos enlazan
  a soporte; eliminacion conserva su accion directa por email, sin otro bloque
  de contacto repetido. No cambian las condiciones sustantivas del servicio.
- Pendiente: formalizar el acuerdo de corresponsabilidad y concretar su
  contenido esencial para los usuarios. No se afirma que este acuerdo ya exista
  ni que la identificacion complete la revision legal de privacidad.
- Confirmar que el correo de contacto recibe emails.
- Comprobar que todas las páginas son públicas y funcionan en HTTPS.
- Conectar los enlaces legales desde la app.
- Revisar periódicamente los textos legales si cambia el servicio.
