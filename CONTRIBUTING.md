# Cómo contribuir

## Flujo de trabajo

1. Crea una rama corta y enfocada desde la rama principal actualizada.
2. Define primero el comportamiento esperado con una prueba que falle cuando el cambio lo permita (TDD).
3. Implementa el cambio mínimo para hacerla pasar y refactoriza sin alterar el comportamiento.
4. Ejecuta las pruebas, analizadores y validaciones aplicables. Reporta resultados reales; no afirmes que algo pasó si no se ejecutó.
5. Abre un pull request pequeño, explica el motivo y solicita revisión.
6. Atiende comentarios y conserva el historial entendible.

No hagas cambios directos en `main`. Todo cambio debe pasar por pull request y revisión, salvo un procedimiento de emergencia documentado por el repositorio.

## Calidad y seguridad

- No desactives pruebas, hooks, analizadores ni reglas para conseguir una validación verde. No uses supresiones sin una justificación técnica revisable.
- No incluyas secretos, tokens, credenciales, datos personales, información de clientes ni detalles sensibles en código, pruebas, registros, capturas, issues o pull requests.
- Usa datos ficticios mínimos en pruebas y ejemplos.
- Mantén el cambio dentro del alcance acordado y evita refactorizaciones no relacionadas.
- Si detectas una vulnerabilidad, sigue `SECURITY.md`; nunca la publiques en un issue.
