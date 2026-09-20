# Biblioteca de animaciones de Seguir

## Objetivo
Crear una galería web de overlays animados de “Seguir” con previews reales y exportación de video.

## Alcance autorizado
- [ ] ODD-01 — Construir galería de variantes, filtros y controles de personalización. (ruta: inline; evidencia: interfaz estática funcional)
- [ ] ODD-02 — Implementar motor canvas para preview animado y exportación WebM con alpha / MP4 cuando el navegador lo soporte. (ruta: inline; evidencia: descarga de video real)
- [ ] ODD-03 — Validar sintaxis y entregar el sitio. (ruta: inline; evidencia: inspección y prueba en navegador)

## Restricciones
- Mantener transparencia real en WebM; no insertar fondos negro, blanco o verde.
- MP4 sin alpha se presenta solo como exportación sin transparencia y depende del soporte del navegador.

## TDD
Desactivado: sitio estático sin runner configurado.

## Próximo paso
Implementar la interfaz y el motor de animación.