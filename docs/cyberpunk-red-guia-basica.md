# Cyberpunk Red — Guía de Reglas Básicas (Resumen)

> **Fuente:** Cyberpunk RED Core Rulebook (R. Talsorian Games, 2020).  
> **Nota:** Este documento es un resumen educativo. Para las reglas completas y exactas, consulta el manual oficial.

---

## 1. Estadísticas (STATS)

Hay **10 Stats** en Cyberpunk RED, cada uno en escala 1-10 (humanos normales; 8+ excepcional, 10 sobrehumano).

| Stat | Abrev. | Uso |
|---|---|---|
| Inteligencia | INT | Razonamiento, memoria, skills técnicas/mentales, puntos de skill |
| Reflejos | REF | Combate a distancia, iniciativa, reacción |
| Destreza | DEX | Combate cuerpo a cuerpo, atletismo, sigilo |
| Técnica | TECH | Reparar, programar, operar tecnología, cyberware |
| Sangre fría | COOL | Resistir miedo, intimidación, presión; interacción social dura |
| Voluntad | WILL | Resistir control mental, dolor, tortura |
| Suerte | LUCK | Gastar puntos para mejorar tiradas (1 punto = +1 al resultado) |
| Movimiento | MOVE | Velocidad, distancia recorrida |
| Cuerpo | BODY | HP, resistencia, daño físico, carga |
| Empatía | EMP | Humanidad, interacción social, liderazgo |

### Creación de personaje (Complete Package / Calculated)
- **62 puntos** para distribuir entre los 10 stats (mínimo 2, máximo 8 por stat).
- **HP** = BODY × 5 + 10 (base; ajustar por heridas).
- **Humanity** = EMP × 10 (se reduce con cyberware).
- **Iniciativa** = 1d10 + REF.
- **Carga** = BODY × 10 kg sin penalización.
- **Velocidad base** = MOVE × 2 m/turno (en grid: MOVE casillas).

### Skills
- Cada skill tiene un nivel (0-10 típico).
- Tirada: **1d10 + Stat + Skill** vs DV.
- Si no tienes la skill: 1d10 + Stat (sin skill), GM puede penalizar.
- **Puntos de skill en creación:** INT × 10 (base) + bonos de rol. Ninguna skill puede superar nivel 6 en creación (nivel 8 con "difficult skills" que cuestan 2 puntos por nivel).
- La habilidad especial del rol se compra con puntos de rol aparte.
- **Mejora:** XP por sesión (típicamente 2-4). Gastar XP para subir skills (costo creciente por nivel).

### DV (Dificultad) de referencia
| DV | Dificultad |
|---|---|
| 9 | Trivial |
| 13 | Fácil |
| 15 | Medio |
| 17 | Difícil |
| 21 | Muy difícil |
| 24+ | Casi imposible |

### Tiradas
- **1d10 + Stat + Skill** vs DV.
- **Crítico:** 10 natural = tirar otro d10 y sumar (exploding). 1 natural = pifia.
- **Oposición:** tirada vs tirada (el mayor gana; empate gana quien defiende).

---

## 2. Roles (10)

Cada rol tiene una **Habilidad Especial** única que sube con puntos de rol.

1. **Rockerboy** — músico/rebelde. Habilidad: *Charismatic Impact* (inspirar/rebelar masas).
2. **Solo** — mercenario/asesino. Habilidad: *Combat Awareness* (mejorar combate: iniciativa, percepción de amenazas).
3. **Netrunner** — hacker. Habilidad: *Interface* (entrar a la NET, controlar sistemas).
4. **Tech** — ingeniero/mecánico. Habilidad: *Maker* (fabricar/modificar equipo).
5. **Medtech** — médico. Habilidad: *Medicine* (curar, cirugía, instalar cyberware).
6. **Media** — periodista. Habilidad: *Credibility* (verdad/noticia que afecta opinión pública).
7. **Exec** — ejecutivo corporativo. Habilidad: *Teamwork* (recursos corporativos, subordinados).
8. **Lawman** — policía/detective. Habilidad: *Authority* (respaldo legal, arrestos).
9. **Fixer** — intermediario/contrabandista. Habilidad: *Operator* (contactos, mercado negro, conseguir equipo).
10. **Nomad** — nómada de carretera. Habilidad: *Moto/Family* (vehículos, familia nomad).

**Notas de juego:**
- El rol define el trasfondo y contactos, no limita skills (cualquiera puede aprender cualquier skill).
- La habilidad especial sube con puntos de rol (como una skill).
- Al crear, el jugador elige un rol y recibe bonos de inicio acordes.

---

## 3. Combate

### Iniciativa
- **1d10 + REF** (una vez al inicio del combate; el mismo orden se mantiene).

### Acciones por turno
- **Move Action:** MOVE × 2 m/yds (o MOVE casillas en grid).
- **Action:** atacar, usar skill, usar item, etc.
- **Bonus Action:** algunas habilidades/implantes.

### Ataque (Ranged)
- **1d10 + REF + Skill de arma** vs DV del objetivo (DV basado en distancia y tipo de arma).
- Si el resultado ≥ DV: impacta.

### Ataque (Melee)
- **1d10 + DEX + Skill de arma melee** vs DV del objetivo (DV basado en distancia).

### Defensa (Dodge/Evasion)
- El defensor puede usar **Evasion** (DEX + Evasion) para esquivar.
- Tirada de Evasion vs ataque. Si Evasion ≥ ataque: esquiva.

### Daño
- **Daño = dados de daño del arma - SP (Stopping Power) del objetivo.**
- Si el daño no supera el SP, no pasa nada (no hay daño mínimo de 1).
- **Armor ablation:** Cada impacto que causa daño reduce el SP del armor en 1.
- **Daño a HP:** El daño que supera el SP se resta de los HP del objetivo.

### Hit Locations
- No hay tirada aleatoria de ubicación. El daño es al cuerpo por defecto.
- **Aimed shot:** El atacante puede apuntar a una ubicación específica (cabeza, brazo, pierna) con penalización de DV (+4 o más).

### Critical Injuries
- Se activan cuando **2 o más dados de daño** salen 6.
- **+5 de daño bonus** y se tira en la tabla de Critical Injuries (cuerpo o cabeza).
- **Body crits:** brazo/pierna amputado, pulmón colapsado, lesión espinal, costillas rotas, objeto extraño, músculo desgarrado.
- **Head crits:** ojo perdido, lesión cerebral, oído dañado, conmoción, mandíbula rota, objeto extraño.
- Cada crit añade +1 al penalizador de Death Save.

### Wound States
| HP restante | Estado | Efecto |
|---|---|---|
| > 50% | Saludable | Sin penalización |
| ≤ 50% | Seriously Wounded | -2 a todas las acciones |
| ≤ 25% | Mortally Wounded | -4 a todas las acciones, Death Save cada turno |
| 0 | Muerto | Death Save fallido |

### Death Save
- **1d10 ≤ BODY** (modificado por rounds dying y críticos).
- Si falla: el personaje muere.
- Si pasa: sobrevive pero sigue en estado crítico.

### Cover
- Sin cobertura: DV normal.
- Cobertura parcial: +2 a DV del atacante.
- Cobertura total: +4 a DV del atacante (o inmune a ataques a distancia).

### Ranged Combat DVs (distancia)
| Arma | 0-6m | 7-12m | 13-25m | 26-50m | 51-100m | 101-200m | 201-400m | 401-800m |
|---|---|---|---|---|---|---|---|---|
| Pistola | 13 | 15 | 20 | 25 | 30 | 30 | N/A | N/A |
| Escopeta | 13 | 15 | 20 | 25 | 30 | 35 | N/A | N/A |
| Rifle de asalto | 17 | 16 | 15 | 13 | 15 | 20 | 25 | 30 |

### Melee Combat
- **1d10 + DEX + Skill de arma melee** vs DV del objetivo.
- Armas melee ignoran la mitad de la armadura del objetivo (SP/2).

### Autofire
- **Autofire (x2):** Dispara 2 veces por turno. Cada disparo es una tirada separada.
- **Autofire (x3):** Dispara 3 veces por turno.

### Área de efecto (granadas, cohetes, etc.)
- Afecta a todos en el área.
- SP se reduce solo en la ubicación del cuerpo (no en la cabeza).
- Si 2+ dados de daño salen 6: todos los afectados reciben Critical Injury.

---

## 4. Curación

### First Aid
- **1d10 + INT + First Aid** vs DV 13 (fácil) para curar daño básico.
- Éxito: cura 1d10 HP (o stat + skill, según reglas).
- Fallo: no cura, posible complicación.

### Paramedic / Medicine
- **1d10 + INT + Paramedic/Medicine** vs DV según gravedad.
- Puede curar heridas críticas y estabilizar personajes mortally wounded.

### Recuperación natural
- HP se recupera con descanso (típicamente 1d10 por día de descanso completo).
- Heridas críticas requieren cirugía o curación avanzada.

### Stabilize
- **1d10 + First Aid/Paramedic + INT** vs DV 13 para estabilizar a un personaje mortally wounded.
- Éxito: el personaje deja de sangrar, pero sigue en estado crítico.

---

## 5. Cyberware y Humanity

### Humanity
- **Humanity inicial** = EMP × 10.
- Cada pieza de cyberware tiene un costo en **Humanity Loss (HL)**.
- Si Humanity llega a 0: **cyberpsychosis** (pierde control; GM toma el personaje).
- A menor Humanity, más inestable. El GM puede pedir tiradas de EMP/COOL para resistir impulsos.

### Tipos de cyberware
- **Modas (Fashionware):** cosmético, bajo HL (1-2).
- **Neuralware:** interfaz, procesadores, etc. (HL 1-5).
- **Cybereyes/Cyberears:** sensores, zoom, etc. (HL 1-3).
- **Cyberlimbs:** brazos/piernas con mejoras (HL 3-5).
- **Cyberweapons:** armas implantadas (HL 4-6).
- **Orgánicos:** mejoras internas (reflejos, etc.) (HL 1-3).

### Instalación
- Requiere Medtech/cirujano. Tirada de Cybertech/Medicine vs DV.
- Fallo: complicaciones, infección, daño.
- Tiempo de recuperación.

### Cyberpsychosis
- A Humanity baja (0-10), el personaje sufre impulsos violentos.
- Cyberpsychos son antagonistas icónicos (MaxTac los caza).

---

## 6. Economía

### Moneda
- **Eurodólares (eb).**

### Precios de referencia
- **Armas de mano (pistola):** 100-500 eb.
- **Armas largas (rifle/SMG):** 500-1500 eb.
- **Armadura ligera (SP 7-11):** 100-500 eb.
- **Armadura pesada (SP 12+):** 500-2000 eb.
- **Cyberware menor:** 500-2000 eb + cirugía.
- **Cyberware mayor:** 2000-10000+ eb.
- **Cyberdeck básico:** 1000-3000 eb.
- **Programas:** 100-1000 eb c/u.
- **Médico/curación:** 50-500 eb.
- **Comida/día:** 10-30 eb.
- **Lifestyle mensual (bajo):** 200-500 eb.
- **Lifestyle mensual (medio):** 1000-2000 eb.
- **Lifestyle mensual (alto):** 5000+ eb.

### Recompensas de misión
- Pequeña/riesgo bajo: 200-500 eb.
- Media: 500-2000 eb.
- Alta/riesgo alto: 2000-5000 eb.
- Corporativa: 5000-20000+ eb (con strings attached).

### Negociación
- Tirada de Trading/Persuasion vs DV del vendedor.
- Éxito: descuento 10-30%.
- Fallo crítico: markup o pérdida de contacto.

---

## 7. Netrunning

### Requisitos
- Interfaz neural + cyberdeck. Solo roles con skill Interface (Netrunner) o equivalente.

### Conceptos
- **NET:** espacio virtual con **arquitecturas** (estructuras de datos con pisos/nodos).
- **Cyberdeck:** hardware; define velocidad, memoria, programas simultáneos.
- **Programas:** ataque (Sword, Hellbolt), defensa (Shield, Armor), utilidad (Scanner, Cloak, Worm).
- **ICE:** defensas del sistema (Anti-Personnel, Anti-System, etc.).
- **Iconos:** representación visual de usuarios, archivos, ICE.

### Flujo de intrusión
1. **Conexión:** el netrunner se conecta a un punto de acceso (físico o remoto).
2. **Entrada a NET:** aparece en el "exterior" de la arquitectura.
3. **Pisos:** la arquitectura tiene pisos (1, 2, ...). Se avanza piso por piso.
4. **Por piso:** escanear, evitar/desactivar ICE, acceder a archivos/control, moverse al siguiente piso.
5. **Objetivo:** robar datos, controlar sistemas, sabotear.
6. **Salida:** desconexión segura (en un nodo de salida) o forzada (riesgo de daño).

### Turnos
- Netrunning ocurre en paralelo al combate físico; los turnos se intercalan.
- Por turno en NET: moverse un piso, ejecutar un programa, escanear, etc.
- **Iniciativa en NET:** 1d10 + INT (o REF según reglas).

### Daño
- El daño en NET (por ICE) puede ser **stun** o **lethal**, aplicado al HP del netrunner (feedback neural).
- Cada turno en NET aumenta **trazabilidad**; a cierto umbral, el sistema bloquea o contraataca.

### Programas vs ICE
- Tirada de skill de programa vs defensa del ICE.
- Éxito: ICE desactivado/dañado.
- Fallo: el ICE actúa.

---

## 8. Lifepath

### Componentes
1. **Origen cultural/regional:** de dónde viene el personaje.
2. **Familia:** estructura familiar, eventos.
3. **Motivación:** por qué hace lo que hace (dinero, venganza, fama, justicia, etc.).
4. **Tragedia/Evento clave:** algo que marcó al personaje.
5. **Amigos y enemigos:** contactos y rivales (generados con tiradas).
6. **Romance:** estado sentimental y posibles parejas.

### Uso en juego
- Los amigos pueden dar favores/contactos.
- Los enemigos aparecen como complicaciones.
- La motivación guía decisiones y recompensas narrativas.
- El GM debe usar el lifepath para crear ganchos y misiones personalizadas.

---

## 9. Movimiento

- **Move Action:** MOVE × 2 m/yds (o MOVE casillas en grid).
- **Velocidad base:** MOVE × 3 m/turno (aprox).
- **Carga:** BODY × 10 kg sin penalización.

---

## 10. Curación

### First Aid
- **1d10 + INT + First Aid** vs DV 13.
- Éxito: cura 1d10 HP.
- Fallo: no cura, posible complicación.

### Paramedic / Medicine
- **1d10 + INT + Paramedic/Medicine** vs DV según gravedad.
- Puede curar heridas críticas y estabilizar personajes mortally wounded.

### Recuperación natural
- HP se recupera con descanso (típicamente 1d10 por día de descanso completo).
- Heridas críticas requieren cirugía o curación avanzada.

---

## 11. Creación de personaje (Complete Package / Calculated)

### Paso 1: Concepto
- Nombre, alias, edad, apariencia, concepto general.

### Paso 2: Rol
- Elegir uno de los 10 roles. Cada rol tiene una habilidad especial.

### Paso 3: Stats
- 62 puntos para distribuir entre los 10 stats (min 2, max 8).
- Calcular derivados: HP, Humanity, Iniciativa, Carga, Velocidad.

### Paso 4: Habilidades
- Puntos de skill = INT × 10 (base) + bonos de rol.
- Distribuir entre skills; ninguna puede superar 6 en creación (8 con "difficult skills" que cuestan 2 puntos por nivel).
- La habilidad especial del rol se compra con puntos de rol aparte.

### Paso 5: Lifepath
- Tirar o elegir en cada tabla (origen, familia, motivación, tragedia, amigos/enemigos, romance).

### Paso 6: Equipo inicial
- Armas, armadura, cyberware inicial según rol y dinero.
- Dinero inicial: típicamente 2000-5000 eb (depende del rol y método de creación).

### Paso 7: Humanity/EMP
- Calcular pérdida por cyberware.
- Humanity = EMP × 10 - HL total.

### Paso 8: Revisión final
- Mostrar ficha completa, pedir confirmación.

### Paso 9: Guardar
- Escribir en `memory/personaje.md` e `memory/inventario.md`.

---

## Fuentes oficiales

- **Manual básico gratuito (Easy Mode):** https://rtalsoriangames.com/cyberpunk/
- **Roll20 Compendium (reglas básicas):** https://roll20.net/compendium/cpunk
- **FAQ oficial:** https://rtalsoriangames.com/wp-content/uploads/2021/07/RTG-CPR-CoreBookFAQv1.3.pdf
- **DemiPlane Nexus (reglas):** https://app.demiplane.com/nexus/cyberpunkred
- **DriveThruRPG (manual completo):** https://www.drivethrurpg.com/browse/pub/13/R-Talsorian-Games-Inc/subcategory/71_33196/Cyberpunk-Red

---

*Este documento es un resumen educativo basado en las reglas de Cyberpunk RED. Para las reglas completas y exactas, consulta el manual oficial.*