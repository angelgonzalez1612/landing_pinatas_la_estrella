# Landing Piñatas La Estrella

Landing page y catálogo estático para `Piñatas La Estrella`, construido con Astro.

## Stack

- `Astro`
- `Tailwind CSS v4` cargado desde `src/styles/global.css`
- Componentes `.astro`

## Rutas

- `/` landing principal
- `/catalogo` catálogo de modelos

## Desarrollo

Requisitos:

- `Node.js >= 22.12.0`

Comandos:

```bash
npm install
npm run dev
npm run build
npm run preview
```

## Estructura

```text
src/
  components/
    Pinata.astro
  pages/
    index.astro
    catalogo.astro
  styles/
    global.css
```

## Pendientes antes de producción

- Reemplazar teléfono, dirección y enlaces de WhatsApp por datos reales.
- Conectar el formulario a un backend o servicio real.
- Mejorar accesibilidad de tarjetas y modales.
- Revisar SEO y metadatos finales.
