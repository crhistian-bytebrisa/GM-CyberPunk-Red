---
description: Iniciar resolución de combate por turnos.
---

# /combate

Invocar skill `combat`. Leer `memory/personaje.md` y `memory/inventario.md`. Resolver combate por turnos:
1. Tirar iniciativa (1d10 + REF).
2. Por turno: move action + action (+ bonus action).
3. Ataque: 1d10 + Stat + Skill vs DV del objetivo.
4. Daño: dados de daño - SP del armor. Armor ablation: -1 SP por impacto que causa daño.
5. Critical injuries si 2+ dados salen 6.
6. Wound states y death saves.
7. Actualizar HP, estado, memoria al final del combate.