# Expo Autos

Landing page de una sola página para Expo Autos, lote de autos seminuevos en Chihuahua, Chih.

Sitio estático (HTML/CSS/JS puro, sin build step) listo para desplegarse en GitHub Pages, Netlify o cualquier hosting estático.

## Estructura

- `index.html` — la página.
- `css/styles.css` — estilos.
- `js/script.js` — animación de aparición al hacer scroll.
- `assets/` — imágenes del sitio.
- `design/` — bundle original exportado de Claude Design (prototipo `.dc.html`, transcripciones del chat de diseño y el sistema de diseño usado como referencia). No forma parte del sitio publicado.

## Pendientes antes de publicar

- Fotos reales de las unidades en inventario (actualmente placeholders).
- Datos reales de inventario (marca, modelo, año, kilometraje, precio) — los actuales son de ejemplo.
- Horario real del negocio (sección de contacto).

## Ver localmente

```bash
python3 -m http.server 8000
```

Y abre `http://localhost:8000`.
