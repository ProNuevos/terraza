# La Terraza Bar & Cocina

Aplicación de una página migrada a Angular. El HTML original se conserva como referencia en `bar-la-terraza.html`.

## Requisitos

- Node.js compatible con Angular CLI 22
- npm

## Desarrollo

```bash
npm install
npm start
```

El servidor local queda disponible en `http://localhost:4200/`.

## Compilar y probar

```bash
npm run build
npm test
```

La carta, las pestañas, el formulario de reserva y los enlaces de WhatsApp se administran desde el componente Angular `src/app/app.ts`.

Las fotografías del hero, la galería y las ofertas están en `public/images`. Se pueden reemplazar allí por imágenes propias conservando los nombres de archivo.
