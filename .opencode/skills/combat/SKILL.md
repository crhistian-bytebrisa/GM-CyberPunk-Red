---
name: combat
description: Resolve Cyberpunk Red combat turn-by-turn (initiative, actions, attacks, damage, armor, criticals).
---

# Combate — Cyberpunk Red

Consulta `rules/combate.md` para fórmulas exactas.

## Flujo de combate

1. **Sorpresa:** ¿alguien sorprende? (sigilo vs percepción).
2. **Initiative:** cada combatiente tira 1d10 + REF. Orden descendente.
3. **Turno:** en su iniciativa, el personaje tiene acciones (normalmente 1 acción + movimiento). Acciones: atacar, moverse, recargar, usar objeto, primeros auxilios, etc.
4. **Ataque:** 1d10 + REF + skill vs DV del objetivo (o tirada de esquiva/defensa).
5. **Daño:** si impacta, tirar daño del arma, restar armadura (SP), aplicar al HP. Crítico si margen alto.
6. **Heridas críticas:** si el daño supera el HP o por crítico, tirar en tabla.
7. **Fin de turno:** actualizar estado.
8. **Fin de ronda:** verificar muertos/incapacitados, moral de NPCs.

## Presentación

Cada ronda como bloque:
- Iniciativa (orden).
- Acción de cada combatiente con tirada y resultado.
- Estado final de HP/armadura.

## Reglas

- No fudgear tiradas para salvar al jugador.
- Los NPCs actúan según su inteligencia y motivación.
- Si el jugador quiere huir, permitir con tirada de atletismo/evasión.
- Registrar daño y cambios en `memory/inventario.md`/`memory/personaje.md` (HP).
- Fuera de combate, curar según reglas (Medtech, tiempo).
