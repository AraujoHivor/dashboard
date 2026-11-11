# Dashboard del Clima

Proyecto de práctica de Desarrollo de Aplicaciones Web y Móviles. El objetivo es construir un dashboard responsivo con React, TypeScript y Material UI, utilizando componentes reutilizables, props tipadas y un selector interactivo de ciudades mediante `useState`.

## Guías desarrolladas

- **Guía 08:** estructura responsiva con `Grid`, encabezado y alertas con componentes MUI.
- **Guía 09:** selección de ciudad mediante `onChange`, `handleChange` y `useState`.

Las secciones de indicadores, gráfico, tabla e información adicional son marcadores de posición para actividades posteriores. No se implementa la consulta a la API en estas guías.

## Ejecutar en local

```bash
npm install
npm run dev
```

## Publicar con GitHub Pages

Instalar `gh-pages` (solo hace falta una vez en el proyecto):

```bash
npm install gh-pages --save-dev
npm run deploy
```

Sitio previsto: https://AraujoHivor.github.io/dashboard/

Para publicar en otro nombre de repositorio, hay que actualizar `homepage` en `package.json` y `base` en `vite.config.ts`.
