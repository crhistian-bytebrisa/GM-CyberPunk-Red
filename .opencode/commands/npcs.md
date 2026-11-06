---
description: Ver relaciones y actitud de NPCs hacia el personaje.
---

# /npcs

Muestra todos los NPCs registrados en `memory/npcs.md` con su personalidad, actitud hacia el PJ y relación.

## Formato de salida

Para cada NPC:
- **Nombre/Alias**
- **Personalidad base**
- **Actitud hacia el PJ** (valor y nivel)
- **Relación con el PJ** (favor, deuda, grudge, alianza, etc.)
- **Agenda propia**
- **Última interacción**

## Si el jugador pregunta por un NPC específico

Mostrar todos los detalles del NPC, incluyendo historial de interacciones.

## Actualización de actitud

Si el jugador pregunta "¿qué piensa [NPC] de mí?", consultar `memory/npcs.md` y responder según la actitud actual. Si la actitud cambió recientemente, mencionarlo.