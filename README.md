# AnalytIA Sports Legal Website

Repositorio de la web oficial/legal mínima de AnalytIA Sports.

Esta web está pensada para funcionar como sitio estático en GitHub Pages y para
servir las URLs legales necesarias antes de publicar la app en Google Play.

No usa backend, base de datos, cookies, analytics, JavaScript ni dependencias
externas obligatorias.

## Páginas incluidas

- `index.html`: página principal.
- `privacy-policy.html`: política de privacidad.
- `terms.html`: términos y condiciones.
- `delete-account.html`: solicitud de eliminación de cuenta.
- `support.html`: soporte.
- `404.html`: página de error.
- `assets/css/styles.css`: estilos.

## Activar GitHub Pages

En GitHub:

```text
Settings → Pages → Deploy from branch → main → root
```

Cuando GitHub Pages esté activo, la web funcionará con la URL temporal del
repositorio.

## URLs futuras con dominio propio

Cuando el dominio esté conectado:

- `https://analytiasports.com`
- `https://analytiasports.com/privacy-policy.html`
- `https://analytiasports.com/terms.html`
- `https://analytiasports.com/delete-account.html`
- `https://analytiasports.com/support.html`

## Checklist antes de Google Play

- Completar responsable legal definitivo.
- Confirmar que `soporte@analytiasports.com` existe y recibe emails.
- Revisar textos legales con asesoría legal/compliance si procede.
- Conectar el dominio `https://analytiasports.com`.
- Comprobar que todas las páginas son públicas y funcionan en HTTPS.
- Comprobar enlaces desde la app hacia:
  - Política de privacidad.
  - Términos.
  - Eliminación de cuenta.
  - Soporte.
- No añadir enlaces a servicios de apuestas, comunidades externas de pago,
  afiliados, pagos externos ni promesas de beneficio económico.

## Notas

Los textos incluidos son una base operativa para publicación inicial. No
incluyen empresa, CIF, dirección fiscal ni razón social porque esos datos no
están definidos en este repositorio.
