# Changelog

Todas las notas de lanzamiento se siguen con formato [SemVer].

## [v1.0.0] - 2025-10-03
### Añadido
- Catálogo web interactivo de códigos HTTP para bug bounty / pentesting.
- Cobertura completa de códigos oficiales 1xx–5xx (incluido 425 Too Early).
- ~20 códigos "extra" no oficiales (ej.: Cloudflare, Nginx, cPanel, frameworks comunes).
- Interfaz web local (HTML/JS) con persistencia en `localStorage` (modo offline).
- Búsqueda interna por número, nombre o descripción.
- Soporte para búsqueda rápida del navegador (Ctrl+F) que salta a la sección correspondiente.
- Favoritos: marcar/desmarcar códigos para filtrar visualmente.
- Panel de notas por cada código (crear, editar, eliminar, ver última modificación).
- Ocultar/mostrar categorías (1xx, 2xx, 3xx, 4xx, 5xx, extra).
- Importar / Exportar preferencias, favoritos y notas en JSON (`importa.json` / `exporta.json`).
- Controles Start/Stop y atajos (S = iniciar, P = parar) para flujos que lo requieran.
- Header fijo, buscador fijo y encabezados de tabla pegajosos para navegación cómoda.
- Diseño pensado para uso local, minimalista y rápido.

### Corregido
- N/A — primera versión estable.

### Notas
- Licencia: MIT.
- Recomendación: no ocultar secciones si planeás usar Ctrl+F del navegador (las secciones colapsadas no son buscadas por Ctrl+F).
