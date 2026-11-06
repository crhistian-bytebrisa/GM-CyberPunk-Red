---
name: npc-creation
description: Create and register NPCs (name, role, motivation, attitude, secret, voice) consistent with Cyberpunk Red lore.
---

# Creación de NPCs

## Procedimiento

1. Preguntar propósito del NPC (aliado, enemigo, contacto, vendor, quest giver).
2. Generar: nombre, alias, edad, apariencia, rol/profesión, facción, motivación principal, actitud hacia el jugador (1-10), secreto, voz/estilo de habla, stats resumidos (si relevante para combate).
3. Mostrar al jugador y permitir ajustes.
4. Registrar en `memory/npcs.md` usando `templates/npc.md`.

## Reglas

- Los NPCs tienen agenda propia; no existen solo para el jugador.
- Dar al menos un secreto o gancho por NPC importante.
- Reutilizar NPCs existentes antes de crear nuevos (consultar `memory/npcs.md`).
- Mantener consistencia de voz y actitud entre apariciones.
- Si el NPC es combatiente, asignar stats mínimos (REF, BODY, HP, armadura, arma).

## Actitud (escala)

1-2 hostil, 3-4 desconfiado, 5 neutral, 6-7 amable, 8-9 leal, 10 devoto.
