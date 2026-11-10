# buzonoriente.github.io

Enlace corto a **El buzón navideño** (Carta a los Reyes Magos): https://buzonoriente.github.io

La página `index.html` solo redirige al enlace directo de la app en Google Apps Script (`/exec`), para que en el móvil se abra a pantalla completa y no dentro del marco de Google Sites (que en iPhone no deja desplazarse).

No contiene nada de la app ni de sus datos. El código de la app está en el repositorio privado `magnetprotec-ship-it/carta-reyes-magos`.

`icono/index.html` (https://buzonoriente.github.io/icono) **no redirige**: muestra el icono y cómo añadirlo a la pantalla de inicio. Al pulsar «Ya lo he añadido» guarda una marca en ese navegador, y desde entonces esa página (y el acceso directo creado desde ella) lleva directamente a la app.

Iconos: `icono-512.png`, `icono-192.png`, `apple-touch-icon.png` (180) y `favicon-32.png`, más `manifest.webmanifest` (nombre corto «Buzón Reyes»).

Si algún día cambia el enlace `/exec`, hay que actualizarlo en los tres sitios de `index.html` y en `icono/index.html`.
