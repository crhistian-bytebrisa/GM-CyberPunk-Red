# Personalidad y relaciones de NPCs — Cyberpunk Red

## Concepto

Cada NPC tiene una **personalidad base** (quién es) y una **actitud hacia el personaje del jugador** (cómo te trata). La personalidad base es estática; la actitud cambia con las interacciones.

## Personalidad base

Rasgos que definen al NPC. Elegir 2-3:

| Rasgo | Descripción |
|---|---|
| **Leal** | Cumple su palabra; protege a los suyos. |
| **Traicionero** | Vende a cualquiera por el precio justo. |
| **Honesto** | Dice la verdad incluso cuando duele. |
| **Mentiroso** | Miente por hábito o interés. |
| **Valiente** | No huye del peligro. |
| **Cobarde** | Evita el riesgo; huye si puede. |
| **Ambicioso** | Busca poder/riqueza a cualquier costo. |
| **Conformista** | Satisfecho con su posición; no busca más. |
| **Empático** | Se preocupa por otros; ayuda sin pedir nada. |
| **Frío** | Indiferente al sufrimiento ajeno. |
| **Impulsivo** | Actúa sin pensar; reactivo. |
| **Calculador** | Piensa antes de actuar; estratégico. |
| **Codicioso** | Quiere más dinero/siendo siempre. |
| **Generoso** | Comparte recursos; da sin esperar. |
| **Orgulloso** | No acepta insultos; exige respeto. |
| **Humilde** | Acepta su lugar; no busca destacar. |

## Actitud hacia el PJ (escala -10 a +10)

| Rango | Nivel | Comportamiento |
|---|---|---|
| -10 a -8 | Enemigo mortal | Te ataca a vista; busca tu muerte. |
| -7 a -5 | Hostil | Te ignora, sabotea, o ataca si puede. |
| -4 a -2 | Desconfiado | Te ayuda mínimamente; exige pago por todo. |
| -1 a +1 | Neutral | Trato profesional; sin preferencias. |
| +2 a +4 | Amistoso | Te ayuda si es conveniente; charla amable. |
| +5 a +7 | Leal | Te ayuda sin pedir nada; te avisa de peligros. |
| +8 a +10 | Devoto | Te protege con su vida; te da recursos gratis. |

## Relación con el PJ

Registrar en `memory/npcs.md`:

- **Favor que le debe el PJ:** El NPC le hizo un favor al PJ (le salvó la vida, le dio equipo, le dio información). El PJ "debe" algo.
- **Deuda que tiene el NPC con el PJ:** El PJ le hizo un favor al NPC. El NPC "debe" algo.
- **Grudge (rencores):** El NPC tiene un rencor contra el PJ por algo que hizo.
- **Alianza:** Trabajan juntos en misiones o negocios.
- **Secreto compartido:** Ambos saben algo que nadie más sabe.
- **Rivalidad:** Competencia amistosa o hostil.
- **Dependencia:** El NPC depende del PJ (económicamente, emocionalmente, etc.).

## Derivados (cambios de actitud)

La personalidad base NO cambia, pero la actitud hacia el PJ SÍ.

### Eventos que cambian la actitud

| Evento | Cambio de actitud |
|---|---|
| Salvar la vida del NPC | +3 a +5 |
| Matar a un aliado del NPC | -4 a -6 |
| Cumplir una promesa | +1 a +2 |
| Romper una promesa | -2 a -3 |
| Dar regalo valioso | +1 a +2 |
| Robar al NPC | -3 a -4 |
| Ayudar en misión | +1 a +2 |
| Fallar misión que afecta al NPC | -1 a -2 |
| Insultar al NPC | -1 a -2 |
| Mostrar respeto | +1 |
| Traicionar al NPC | -5 a -8 |
| Ser traicionado por el NPC | -8 a -10 |

### Límites

- La actitud no puede superar +10 ni bajar de -10.
- Cambios de actitud se aplican **por evento**, no acumulativos por sesión.
- El GM puede ajustar según el contexto (ej: un NPC traicionero puede ser más susceptible a cambios negativos).

### Interacción con otros NPCs

- El NPC puede tener **actitudes diferentes** hacia diferentes PJs (si hay múltiples jugadores).
- El NPC puede tener **actitudes diferentes** hacia facciones (ej: hostil a Militech, amable a Nomads).
- Registrar actitud por PJ y por facción si es relevante.

## Aplicación en juego

### Cuando el PJ interactúa con un NPC

1. Consultar `memory/npcs.md` para la personalidad y actitud actuales.
2. Interpretar al NPC según su personalidad base y actitud.
3. Si el PJ hace algo que afecta la relación, aplicar cambio de actitud.
4. Actualizar `memory/npcs.md` con el nuevo valor.

### Cuando el NPC actúa por su cuenta

- El NPC tiene agenda propia; no existe solo para el PJ.
- Su personalidad base guía sus decisiones (ej: un NPC ambicioso traiciona si es conveniente).
- Su actitud hacia el PJ afecta cómo trata al PJ, pero no cómo actúa con otros.

### Ejemplo

**NPC:** "Razor" (Fixer)
- Personalidad base: Calculador, Codicioso, Leal (a sus propios intereses)
- Actitud inicial hacia el PJ: +2 (Amistoso)
- Relación: El PJ le hizo un favor (le dio información sobre una corp). Deuda: 1 favor.
- Evento: El PJ cumple una misión para Razor → +2 actitud (+4 total)
- Evento: El PJ roba a Razor → -4 actitud (0 total)
- Resultado: Razor ahora es neutral; puede traicionar al PJ si le conviene.

## Tracking en memoria

Registrar en `memory/npcs.md`:

```
## [Nombre] "Alias"
- **Personalidad base:** [2-3 rasgos]
- **Actitud hacia el PJ:** [valor] ([nivel])
- **Relación con el PJ:** [detalles]
- **Historial de interacciones:** [eventos que cambiaron la actitud]
- **Agenda propia:** [qué quiere el NPC independientemente del PJ]
```

## Reglas para el GM

- No cambiar la personalidad base; solo la actitud.
- Aplicar cambios de actitud de forma consistente.
- Los NPCs tienen memoria; recuerdan favores, deudas y traiciones.
- Si la actitud baja a -5 o menos, el NPC puede volverse enemigo.
- Si la actitud sube a +8 o más, el NPC puede volverse aliado devoto.
- Registrar todos los cambios en `memory/npcs.md` y `memory/bitacora.md`.