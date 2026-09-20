# Biblioteca de animaciones de Seguir

## Objetivo
Crear una galería web de overlays animados de “Seguir” con previews reales y exportación de video.

## Alcance autorizado
- [x] ODD-01 — Construir galería de variantes, filtros y controles de personalización. (ruta: inline; evidencia: 18 tarjetas, filtros y panel reactivo en `dist/index.html`; commit `bd430e0`)
- [x] ODD-02 — Implementar motor canvas para preview animado y exportación WebM con alpha / MP4 cuando el navegador lo soporte. (ruta: inline; evidencia: Canvas a 60 FPS; MediaRecorder genera toda la secuencia; commit `bd430e0`)
- [x] ODD-03 — Validar sintaxis y publicar el sitio. (ruta: inline; evidencia: `node --check` correcto; versión 1 desplegada)

## Restricciones
- Mantener transparencia real en WebM; no insertar fondos negro, blanco o verde.
- MP4 sin alpha se presenta solo como exportación sin transparencia y depende del soporte del navegador.

## TDD
Desactivado: sitio estático sin runner configurado.

## Resultado
Implementación completada. Sitio privado publicado en Motion Follow.
