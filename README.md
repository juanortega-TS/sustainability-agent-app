# Alianza News Hub · enlace público

Este repositorio es **público a propósito** y solo contiene tres archivos,
servidos con GitHub Pages en https://juanortega-ts.github.io/alianza-news-hub-app/ :

| Archivo | Para qué |
|---|---|
| `icon.png` | Ícono de la pestaña de la app (Apps Script solo acepta una URL pública `.png`) |
| `vista-previa.png` | Imagen de la tarjeta al compartir el enlace (WhatsApp, Teams, correo) |
| `index.html` | Página puente: muestra la vista previa y lleva a la app |

La app en sí vive en Google Apps Script y **exige una cuenta de alianzateam.com
autorizada**. Este repositorio no guarda código de la app, datos, claves ni nada más:
la única información que expone es la dirección de la app, que igual pide iniciar sesión.

El código está en el repositorio privado `juanortega-TS/alianza-news-hub-gas`.

Si cambia la implementación `/exec` de Apps Script, hay que actualizar la URL en `index.html`.
