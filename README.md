# Paulo Baldessari — rediseño React (versión 2)

Proyecto responsive desarrollado con React 19, JavaScript, Vite, Motion y Lucide Icons. Incluye acordeón animado de servicios, menú móvil, slider de testimonios, animaciones de entrada, CTA a WhatsApp (con ícono SVG real) y visuales reutilizados del sitio oficial.

## Uso local

```bash
npm install
npm run dev
```

## Publicación

```bash
npm run build
```

Subir la carpeta `dist/` a cualquier hosting estático. Para GitHub Pages, se puede publicar `dist/` con GitHub Actions o `gh-pages`. `vite.config.js` usa `base: './'` para funcionar en un subdirectorio.

## Fotografías / permiso

Las fotografías son URL públicas de `paulobaldessari.com`; NO están incorporadas como archivos en el ZIP. Antes de una publicación definitiva, pedir autorización al titular y alojar copias optimizadas localmente. Si se rompe alguna URL, cambiar el objeto `photos` en `src/main.jsx`.

## Información

Los textos, países, organizaciones y testimonios se conservan de la versión anterior basada en el sitio oficial. No se inventaron logros ni testimonios. `services`, `countries`, `clients` y `quotes` se editan fácilmente en `src/main.jsx`. Revalidar referencias antes del lanzamiento.

## WhatsApp

El número se configura en `WA` al principio de `src/main.jsx`. Confirmar que sigue vigente antes de publicar.


## Versión 3 — Orientada a consultas
- Selector de consulta con tres objetivos y mensajes prearmados a WhatsApp.
- CTA propio para cada uno de los seis servicios.
- Respuestas breves a dudas antes de contactar.
- Metadatos Open Graph para compartir.

Antes de publicar: ejecutar `npm install` y `npm run build`; verificar cada fotografía remota, WhatsApp y la navegación móvil. No se validó el build en este entorno por falta de instalación de dependencias. Confirmar derechos y disponibilidad de las imágenes del sitio original.


## Testimonios v4
Los retratos de Roberto Colombo, Eric Gantier y Juan Pablo Lopez de la Rosa provienen de la página oficial de testimonios de Paulo: https://paulobaldessari.com/testimonios/. Son fotografías de 100x100 px y se sirven desde esa web: antes de publicar en producción, solicitar autorización y alojar versiones con mayor resolución cuando estén disponibles.
Las cinco estrellas son un tratamiento VISUAL, no una valoración real de 5/5 ni una calificación de LinkedIn. Nunca comunicar que LinkedIn verificó una puntuación. El primer enlace lleva a las recomendaciones del perfil de Paulo, y los otros dos a los perfiles públicos de los autores. Las citas son fragmentos literales publicados en la web oficial de Paulo.
