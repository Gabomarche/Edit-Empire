# Edit Empire — web

Portfolio de **Edit Empire** (Gabriel): edición de video y postproducción con IA.

Es una web estática: no necesita instalar nada ni compilar.

```
index.html      → la página completa (estilos y código incluidos)
assets/         → videos, fotos, audios y favicon
netlify.toml    → configuración para Netlify
```

## Publicar en Netlify (con actualización automática)

1. En [app.netlify.com](https://app.netlify.com) → **Add new site → Import an existing project → GitHub**.
2. Elegí el repositorio **Edit-Empire**.
3. Dejá todo como viene (sin comando de build, carpeta de publicación `.`) y tocá **Deploy**.

Desde ese momento, cada cambio que se suba a la rama `main` se publica solo en uno o dos minutos.

## Publicar en Hostinger

En el **Administrador de archivos** de Hostinger, sube dentro de `public_html`: `index.html`, la carpeta `assets`, `robots.txt`, `sitemap.xml`, `site.webmanifest` y `.htaccess` (en Mac es un archivo oculto: en Finder, Cmd + Shift + punto para verlo).

## Agregar una reseña o un trabajo

- Reseñas: audio (`.m4a`) y logo cuadrado (`.jpg`) en `assets/`, y una tarjeta nueva en la sección “NO LO DIGO YO” del `index.html`.
- Trabajos: video vertical (`.mp4`, 540×960) y portada (`.jpg`) en `assets/`, y una tarjeta nueva en “ELIGE UN ESTILO”.
