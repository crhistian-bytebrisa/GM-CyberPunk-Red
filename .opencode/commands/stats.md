---
description: Muestra las estadísticas del personaje de forma estilizada (rol, nivel, stats, HP, eb, heat, skills principales).
---

# /stats

Leer `memory/personaje.md` e `memory/inventario.md`. Presentar en bloque estilizado:

```
╔══════════════════════════════════════╗
║  [NOMBRE] — [ROL]                    ║
║  Alias: [alias]  |  Edad: [edad]     ║
╠══════════════════════════════════════╣
║  HP: [hp]/[hp_max]  ·  eb: [eb]      ║
║  Humanity: [humanity]  ·  LUCK: [luck]║
║  Heat: NCPD [n] / Corp [n] / Gangs [n]║
╠══════════════════════════════════════╣
║  STATS (1-10)                        ║
║  INT [n]  REF [n]  DEX [n]  TECH [n] ║
║  COOL [n]  WILL [n]  LUCK [n]        ║
║  MOVE [n]  BODY [n]  EMP [n]         ║
╠══════════════════════════════════════╣
║  TOP SKILLS                          ║
║  [skill] [nivel]  [skill] [nivel]    ║
║  ...                                 ║
╠══════════════════════════════════════╣
║  CYBERWARE                           ║
║  [pieza] (HL [n])                    ║
║  ...                                 ║
╠══════════════════════════════════════╣
║  ROL ABILITY: [nombre] (nivel [n])   ║
║  MISIONES: [activas] activas,        ║
║  [completadas] completadas           ║
╚══════════════════════════════════════╝
```

Incluir: nombre, alias, edad, rol, HP, eb, Humanity, LUCK, heat, stats, top 5-8 skills, cyberware, rol ability, misiones activas/completadas. Si no hay personaje, ofrecer `/crear-personaje`.