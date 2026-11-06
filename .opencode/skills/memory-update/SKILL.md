---
name: memory-update
description: Update persistent memory files after scenes/sessions (character, NPCs, missions, inventory, world, log).
---

# Actualización de memoria

## Cuándo

Al final de cada escena significativa, combate, transacción, o cuando el jugador lo pida. También al cerrar sesión.

## Procedimiento

1. Identificar qué cambió: personaje (HP, XP, skills), NPCs (nuevos/relaciones), misiones (progreso/estado), inventario (equipo/dinero), lugares, facciones (reputación), mundo (eventos/heat).
2. Editar los archivos correspondientes en `memory/`.
3. Añadir entrada en `memory/bitacora.md` con fecha, resumen, cambios.
4. Mostrar al jugador un resumen de cambios (diff humano).

## Reglas

- Solo cambiar lo que efectivamente ocurrió.
- No borrar historia; marcar misiones como "completada/fallida" en lugar de borrar.
- Si hay contradicción, preguntar al jugador cuál es la verdad.
- Mantener formato consistente con las plantillas.
- Nunca inventar datos para "rellenar".
