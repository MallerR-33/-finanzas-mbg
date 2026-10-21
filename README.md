# Finanzas.MBG — PWA para iPhone

## Archivos
- `index.html`: aplicación web.
- `manifest.webmanifest`: nombre, icono y configuración PWA.
- `sw.js`: caché básica para abrir la interfaz sin conexión tras la primera visita.
- `icon-192.png` y `icon-512.png`: iconos de la aplicación.

## Publicar gratis con GitHub Pages desde el iPhone
1. En Safari abre https://github.com y crea una cuenta o inicia sesión.
2. Crea un repositorio nuevo llamado `finanzas-mbg`. Para que Pages sea público, selecciona **Public**. No subas datos personales ni contraseñas al repositorio.
3. En el repositorio toca **Add file → Upload files**. Sube los cinco archivos de esta carpeta: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`. No subas datos personales.
4. Toca **Commit changes**.
5. En el repositorio abre **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, rama `main`, carpeta `/(root)` y guarda.
6. Espera a que termine el despliegue. GitHub Pages mostrará una dirección similar a `https://TU-USUARIO.github.io/finanzas-mbg/`. Abre esa dirección en Safari.
7. En Safari toca **Compartir → Añadir a pantalla de inicio**. Si aparece la opción **Abrir como app web**, actívala y toca **Añadir**.

Los nombres exactos de los botones pueden variar un poco según el idioma/interfaz de GitHub.

## Importante
- Un repositorio público hace público el código, NO pongas secretos, datos de usuarios ni registros financieros en él.
- Los registros financieros se guardan en el almacenamiento local del navegador de cada dispositivo. No hay servidor de sincronización.
- El almacenamiento del navegador puede borrarse; exporta tus movimientos como respaldo.
- La bóveda usa cifrado en el navegador, pero este prototipo no ha sido auditado y no debe usarse todavía para contraseñas importantes.
- El service worker requiere HTTPS; GitHub Pages lo proporciona. La caché puede conservar la interfaz básica sin conexión después de cargarla una vez.
