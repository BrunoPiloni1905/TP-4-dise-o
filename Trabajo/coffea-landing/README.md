# Coffea - Landing page (TP4 Diseño UX-UI)
Landing estática hecha solo con HTML5 y CSS3 (sin JavaScript).

## Estructura
- `index.html`, `404.html`, `netlify.toml`
- `css/`: `main.css` importa las capas (tokens, base, layout, components, utilities) con `@layer`
- `assets/img` y `assets/icons`: imágenes e íconos

## Convenciones
BEM, mobile-first, colores/fuentes/radios/espacios en `css/tokens.css`.

## Levantar en local
Abrir `index.html` en el navegador (o usar la extensión Live Server de VS Code).

## Despliegue
Subir el repo a GitHub, conectarlo a Netlify (sin build command, publish directory `.`). La rama `main` publica a producción y cada Pull Request genera un Deploy Preview.

## Pendientes
- Las imágenes son placeholders: reemplazar por los exports de Figma (AVIF/WebP + JPG) y confirmar licencia.
- Validar tablet/mobile con diseño; medir Lighthouse sobre la URL de Netlify.
