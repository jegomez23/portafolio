# Portafolio — Juan Esteban Gómez

Sitio estático de portafolio personal: proyectos, experiencia y contacto. Bilingüe (ES/EN), sin dependencias ni build — HTML, CSS y JavaScript puros.

## Estructura

- `index.html` — la página del portafolio (todo el contenido y los estilos viven aquí).
- `support.js` / `image-slot.js` — runtime del canvas de diseño (animaciones, fondo, slots de imagen).
- `assets/` — imágenes usadas por el sitio.
- `Juan Esteban - Experience-print-i8vuay.dc.html` — versión anterior con estilos de impresión (para exportar a PDF).

## Ver en local

No requiere build. Basta con servir la carpeta:

```bash
npx serve .
```

y abrir http://localhost:3000.

## Despliegue en Vercel

1. Sube el repositorio a GitHub.
2. En [vercel.com/new](https://vercel.com/new), importa el repositorio.
3. Framework preset: **Other** (sitio estático, sin comando de build ni carpeta de salida).
4. Deploy — Vercel sirve `index.html` en la raíz automáticamente.

También se puede desplegar desde la terminal con `npx vercel` (o `npx vercel --prod` para producción).
