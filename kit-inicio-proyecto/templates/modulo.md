# Plantilla de especificación por área

Crear una especificación en `docs/plan-maestro`, enlazarla en su índice y agregar tareas con la plantilla común.

```markdown
# Nombre del área

## Propósito y fuentes

Problema, actores, fuentes y decisiones confirmadas; propuestas y dudas identificadas como tales.

## Lenguaje y fronteras

Referenciar el contexto propietario, agregados y contratos definidos en arquitectura; describir aquí solo su relación con los requisitos de esta área. No duplicar su definición ni derivar módulos de una pantalla.

## Reglas y recorridos

Invariantes, permisos, errores e integraciones. Concurrencia, idempotencia y operación cuando correspondan al proceso.

## Estado observado y límites

En proyectos existentes: contraste fechado de implementación, pruebas, faltantes y decisiones, con enlaces a su evidencia principal. No mantener aquí un segundo estado vigente de tareas ni atribuir aceptación a la sola presencia de código.

## Tareas

Insertar bloques de la plantilla de tarea con IDs estables y dependencias explícitas.
```
