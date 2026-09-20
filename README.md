# GRAYCAVE_ARC

Archivo personal de artículos, fotografía, arte, notas y proyectos.

## Estructura

- `index.html` — portada
- `archive.html` — artículos, notas y proyectos
- `photography.html` — galería fotográfica
- `about.html` — página personal
- `styles.css` — diseño completo del sitio
- `script.js` — tema claro/oscuro y menú móvil

## Cómo editarlo

La mayor parte de la apariencia está centralizada al inicio de `styles.css` mediante variables como:

```css
--bg: #0b0c0e;
--panel: #111317;
--text: #f3f3ef;
--muted: #999c9f;
--accent: #d6ff3f;
```

Cambiar esos valores modifica rápidamente los colores principales del sitio.

Los textos y secciones se pueden editar directamente en cada archivo `.html`.

## Publicación con GitHub Pages

En GitHub abre:

`Settings → Pages → Build and deployment → Deploy from a branch`

Selecciona:

- Branch: `main`
- Folder: `/ (root)`

Después pulsa `Save`.

La web quedará publicada bajo la URL de GitHub Pages asociada a este repositorio.
