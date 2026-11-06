---
name: mission-design
description: Design Cyberpunk Red missions (hook, objectives, obstacles, rewards, consequences) and register them.
---

# Diseño de misiones

## Estructura de una misión

- **Título** (corto, callejero).
- **Dador:** quién la ofrece (NPC/facción).
- **Gancho:** por qué el jugador se entera.
- **Objetivo principal:** qué debe lograr.
- **Objetivos secundarios:** opcionales con bonus.
- **Localización:** dónde ocurre.
- **Obstáculos:** combate, sigilo, social, netrunning, trampas.
- **PNJs involucrados:** aliados/enemigos.
- **Recompensa:** eb, rep, equipo, info, contactos.
- **Consecuencias:** qué pasa si falla/éxito, impacto en facciones.
- **Ganchos futuros:** semillas para próximas misiones.

## Procedimiento

1. Preguntar al jugador qué tipo de misión quiere (acción, sigilo, social, investigación, netrun) y nivel de peligro.
2. Proponer 2-3 conceptos; el jugador elige.
3. Desarrollar la elegida con la estructura.
4. Confirmar y registrar en `memory/misiones.md` (estado: activa).
5. Generar NPCs/lugares necesarios y registrarlos.

## Reglas

- Escalar dificultad al nivel del personaje.
- Siempre incluir al menos una complicación inesperada.
- Recompensas acordes al riesgo (ver `rules/economia.md`).
- No cerrar todos los hilos; dejar ganchos.
