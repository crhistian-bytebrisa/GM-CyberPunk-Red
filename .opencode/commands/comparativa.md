---
description: Guarda un snapshot comparativo del personaje antes/después de una misión en comparativas/[personaje]/[mision].md.
---

# /comparativa {mision}

Crear la carpeta `comparativas/[nombre_personaje]/` si no existe. Guardar un archivo `[mision].md` con:

## Formato del archivo

```markdown
# Comparativa — [Misión] — [Nombre del personaje]

## Antes de la misión
- HP: [hp]
- eb: [eb]
- Humanity: [humanity]
- Heat: NCPD [n] / Corp [n] / Gangs [n]
- Cyberware: [lista]
- Skills clave: [lista de skills relevantes con niveles]
- Equipo: [lista]

## Después de la misión
- HP: [hp]
- eb: [eb]
- Humanity: [humanity]
- Heat: NCPD [n] / Corp [n] / Gangs [n]
- Cyberware: [lista]
- Skills clave: [lista de skills relevantes con niveles]
- Equipo: [lista]

## Qué cambió
- [Lista de cambios significativos: HP, eb, Humanity, heat, cyberware, skills, equipo, contactos, etc.]
- [Solo lo que cambió. Lo demás es irrelevante.]
```

## Procedimiento
1. Leer `memory/personaje.md`, `memory/inventario.md`, `memory/mundo.md`.
2. Si no hay personaje, ofrecer `/crear-personaje` y detener.
3. Preguntar al jugador si quiere registrar el estado "antes" o "después" de la misión.
4. Si es "antes": guardar el snapshot inicial en `comparativas/[nombre]/[mision]_antes.md` (o en el mismo archivo con sección "Antes").
5. Si es "después": completar la sección "Después" y "Qué cambió" en el archivo de la misión.
6. Si el archivo no existe, crearlo con la sección "Antes" primero.

## Reglas
- No cargar muchos datos. Solo lo que cambió es relevante.
- Una carpeta por personaje: `comparativas/[nombre_personaje]/`.
- Un archivo por misión: `[mision].md`.
- Si el personaje no tiene carpeta, crearla.