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
