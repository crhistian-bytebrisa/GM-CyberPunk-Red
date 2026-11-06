---
name: npc-creation
description: Create and register NPCs (name, role, motivation, attitude, secret, voice) consistent with Cyberpunk Red lore.
---

# Creación de NPCs

## Procedimiento

1. Preguntar propósito del NPC (aliado, enemigo, contacto, vendor, quest giver).
2. Generar: nombre, alias, edad, apariencia, rol/profesión, facción, motivación principal, personalidad base (2-3 rasgos), actitud inicial hacia el PJ (1-10), relación inicial con el PJ (favor, deuda, grudge, alianza, etc.), agenda propia, secreto, voz/estilo de habla, stats resumidos (si relevante para combate).
3. Mostrar al jugador y permitir ajustes.
4. Registrar en `memory/npcs.md` usando `templates/npc.md`.

## Reglas

- Los NPCs tienen agenda propia; no existen solo para el jugador.
- Dar al menos un secreto o gancho por NPC importante.
- Reutilizar NPCs existentes antes de crear nuevos (consultar `memory/npcs.md`).
- Mantener consistencia de voz y actitud entre apariciones.
- Si el NPC es combatiente, asignar stats mínimos (REF, BODY, HP, armadura, arma).
- Consultar `rules/npcs.md` para el sistema de personalidad y relaciones.
- Actualizar actitud del NPC hacia el PJ cuando ocurran eventos relevantes.

## Actitud (escala)

-10 a -8 enemigo mortal, -7 a -5 hostil, -4 a -2 desconfiado, -1 a +1 neutral, +2 a +4 amistoso, +5 a +7 leal, +8 a +10 devoto.

## Personalidad base (rasgos)

Leal, Traicionero, Honesto, Mentiroso, Valiente, Cobarde, Ambicioso, Conformista, Empático, Frío, Impulsivo, Calculador, Codicioso, Generoso, Orgulloso, Humilde. Elegir 2-3.

## Cambios de actitud (eventos)

Salvar la vida del NPC: +3 a +5. Matar a un aliado: -4 a -6. Cumplir promesa: +1 a +2. Romper promesa: -2 a -3. Dar regalo valioso: +1 a +2. Robar al NPC: -3 a -4. Ayudar en misión: +1 a +2. Fallar misión que afecta al NPC: -1 a -2. Insultar: -1 a -2. Mostrar respeto: +1. Traicionar: -5 a -8. Ser traicionado: -8 a -10.
