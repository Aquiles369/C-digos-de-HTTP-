# Release Notes — v1.0.0 (2025-10-03)

## Resumen
Lanzamiento inicial del **Catálogo web interactivo de códigos HTTP** orientado a bug bounty y pentesting. Herramienta offline y ligera para identificar rápidamente qué significa un código HTTP recibido en pruebas o recon. Ideal para auditorías rápidas y laboratorios locales.

## Highlights
- Cobertura completa de códigos oficiales 1xx–5xx (incluye 425 Too Early).
- Añadidos ~20 códigos "extra" usados en el día a día (Cloudflare, Nginx, cPanel, frameworks).
- Búsqueda interna potente + compatibilidad con Ctrl+F para saltar a la sección del código.
- Notas por código y favoritos que persisten en `localStorage`.
- Importación/exportación de configuración y notas en JSON para compartir perfiles o backups.

## Formato
- Interfaz: HTML + JavaScript (archivo único: `Estados_servidor.html`).
- Persistencia: `localStorage` (sin backend).
- Licencia: MIT.

## Cómo usar (rápido)
1. Descargar o clonar el repositorio.
2. Abrir `Estados_servidor.html` en el navegador (recomendado: Chrome/Chromium).
3. Escribir el código HTTP en el buscador interno (ej.: `429`) o presionar `Ctrl+F` y escribir `429`.
4. Añadir notas, marcar favorito o exportar/importar tu configuración en JSON.

## Características (detalle)
- **Búsqueda por categoría y texto**: filtra por 1xx / 2xx / 3xx / 4xx / 5xx / extra.
- **Favoritos**: guarda y filtra solo los códigos que te interesan.
- **Notas por código**: guardá evidencia, ejemplos o comentarios por cada estado.
- **Import/Export JSON**: comparte tu perfil (favoritos + notas + preferencias).
- **Atajos**: `S` (iniciar) / `P` (parar) para flujos que lo requieran.
- **UX**: header/buscador fijo y encabezados de tabla pegajosos para no perder contexto al scrollear.

## Consideraciones
- Esta herramienta es **offline**: todo queda en tu máquina. Ideal para entornos aislados y laboratorios.
- Si ocultás una categoría, tené en cuenta que `Ctrl+F` del navegador **no** encontrará dentro de secciones colapsadas; usar el buscador interno.
- Los códigos "extra" son prácticos pero no oficiales — úsalos como referencia de comportamiento real de proveedores (ej.: Cloudflare).

## Bugs conocidos / Roadmap
- V1: estabilidad y funcionalidad básica completadas.
- Roadmap próximo (ideas): modo oscuro, exportar PDF de resumen, entrar ejemplos de respuesta server-side para cada código, filtros por proveedor (Cloudflare/Nginx), y versión CLI para búsquedas rápidas.
- Si querés que algo aparezca en la próxima release, decímelo y lo priorizo (o lo añadís y me marcás el PR, rey).

## Licencia
- MIT. Uso responsable y legal únicamente.

---
