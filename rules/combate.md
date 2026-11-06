# Combate — Cyberpunk Red

## Iniciativa
- **1d10 + REF** (una vez al inicio del combate; el mismo orden se mantiene para toda la pelea).
- **Ambush:** Los emboscadores actúan primero sin tirada, luego se tira iniciativa normal.
- **Desempate:** Mayor REF, luego mayor DEX.

## Turno por personaje
Cada personaje tiene en su turno:
- **Move Action:** MOVE × 2 m/yds (o MOVE casillas en grid).
- **Action:** atacar, usar skill, usar item, etc.
- **Bonus Action:** algunas habilidades/implantes.

## Ataque (Ranged)
- **1d10 + REF + Skill de arma** vs DV del objetivo.
- DV basado en distancia y tipo de arma (ver tabla de Ranged Combat DVs).
- Si el resultado ≥ DV: impacta.

## Ataque (Melee)
- **1d10 + DEX + Skill de arma melee** vs DV del objetivo.
- Armas melee ignoran la mitad de la armadura del objetivo (SP/2).

## Defensa (Dodge/Evasion)
- El defensor puede usar **Evasion** (DEX + Evasion) para esquivar.
- Tirada de Evasion vs ataque. Si Evasion ≥ ataque: esquiva.

## Daño
- **Daño = dados de daño del arma - SP (Stopping Power) del objetivo.**
- Si el daño no supera el SP, no pasa nada (no hay daño mínimo de 1).
- **Armor ablation:** Cada impacto que causa daño reduce el SP del armor en 1.
- **Daño a HP:** El daño que supera el SP se resta de los HP del objetivo.

## Hit Locations
- No hay tirada aleatoria de ubicación. El daño es al cuerpo por defecto.
- **Aimed shot:** El atacante puede apuntar a una ubicación específica (cabeza, brazo, pierna) con penalización de DV (+4 o más).

## Critical Injuries
- Se activan cuando **2 o más dados de daño** salen 6.
- **+5 de daño bonus** y se tira en la tabla de Critical Injuries (cuerpo o cabeza).
- **Body crits:** brazo/pierna amputado, pulmón colapsado, lesión espinal, costillas rotas, objeto extraño, músculo desgarrado.
- **Head crits:** ojo perdido, lesión cerebral, oído dañado, conmoción, mandíbula rota, objeto extraño.
- Cada crit añade +1 al penalizador de Death Save.

## Wound States
| HP restante | Estado | Efecto |
|---|---|---|
| > 50% | Saludable | Sin penalización |
| ≤ 50% | Seriously Wounded | -2 a todas las acciones |
| ≤ 25% | Mortally Wounded | -4 a todas las acciones, Death Save cada turno |
| 0 | Muerto | Death Save fallido |

## Death Save
- **1d10 ≤ BODY** (modificado por rounds dying y críticos).
- Si falla: el personaje muere.
- Si pasa: sobrevive pero sigue en estado crítico.

## Cover
- Sin cobertura: DV normal.
- Cobertura parcial: +2 a DV del atacante.
- Cobertura total: +4 a DV del atacante (o inmune a ataques a distancia).

## Ranged Combat DVs (distancia)
| Arma | 0-6m | 7-12m | 13-25m | 26-50m | 51-100m | 101-200m | 201-400m | 401-800m |
|---|---|---|---|---|---|---|---|---|
| Pistola | 13 | 15 | 20 | 25 | 30 | 30 | N/A | N/A |
| Escopeta | 13 | 15 | 20 | 25 | 30 | 35 | N/A | N/A |
| Rifle de asalto | 17 | 16 | 15 | 13 | 15 | 20 | 25 | 30 |

## Melee Combat
- **1d10 + DEX + Skill de arma melee** vs DV del objetivo.
- Armas melee ignoran la mitad de la armadura del objetivo (SP/2).

## Autofire
- **Autofire (x2):** Dispara 2 veces por turno. Cada disparo es una tirada separada.
- **Autofire (x3):** Dispara 3 veces por turno.

## Área de efecto (granadas, cohetes, etc.)
- Afecta a todos en el área.
- SP se reduce solo en la ubicación del cuerpo (no en la cabeza).
- Si 2+ dados de daño salen 6: todos los afectados reciben Critical Injury.

## Reglas para el GM
- Describir el combate de forma visual y cinematográfica.
- No ocultar información que el personaje percibiría.
- Marcar tiradas secretas del GM como "tirada del GM" sin revelar resultado numérico.
- Aplicar wound states y critical injuries inmediatamente.