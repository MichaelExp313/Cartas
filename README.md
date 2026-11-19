# 🍽️ Mis Cartas

App web instalable (PWA) para guardar las cartas de tus restaurantes favoritos con fotos.

## Funciones
- Crear restaurantes con **nombre** y **varias fotos** (cámara o galería, selección múltiple).
- Ver las fotos a pantalla completa: deslizar entre fotos, **pellizcar o doble toque para ampliar** y leer bien la carta.
- Elegir la foto de portada, eliminar fotos, compartir cualquier foto con el botón que aparece en su miniatura, renombrar y borrar restaurantes.
- Buscador (aparece cuando tienes 4 o más restaurantes).
- **Copia de seguridad**: exportar e importar todo en un archivo `.json` (útil para pasar los datos a otro móvil).
- **Tema claro y oscuro**: botón ☀️/🌙 arriba para cambiarlo, o modo automático desde el menú ⋮.
- Funciona **sin conexión** y se instala con su propio icono.

Las fotos se comprimen (máx. 2000 px) y se guardan en el propio dispositivo (IndexedDB). No se suben a ningún servidor.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `mis-cartas`).
2. Sube todos los archivos de esta carpeta (todos sueltos, sin carpetas) a la raíz del repositorio.
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/mis-cartas/`.

## Instalar en el móvil
- **Android (Chrome):** abre la web y pulsa *Instalar* en el aviso, o menú ⋮ → *Instalar aplicación*.
- **iPhone (Safari):** botón *Compartir* → *Añadir a pantalla de inicio*.

## Actualizar la app
Si cambias archivos, sube el número de versión en `sw.js` (`cartas-v1` → `cartas-v2`) para que los móviles descarguen la nueva versión.
