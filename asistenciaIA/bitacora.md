# Bitácora del trabajo de los agentes

Una fila por trabajo. Las más recientes, abajo. Si no sabes algo: «pendiente».
**Revisión humana** = tú has leído y comprobado el resultado (no solo lo ha ejecutado el agente).
Esta bitácora **hace de declaración de uso de IA** del módulo.

| Fecha | Agente y modelo | Qué pedí | Qué acepté o cambié | Dónde quedó | Revisión humana |
|---|---|---|---|---|---|
| 2026-11-24 | `Claude Code` · `Sonnet 5.5 (medio)` | «Redacta la tabla de obligaciones con enlace a cada norma, el glosario y el hueco del SOTA» | Abrí y leí yo cada norma para poner `leído`, revisé los enlaces y decidí el guion de 6 fases con despliegue | `docs/01-analisis.md` (apartados 5, 7 y 8) y `docs/01b-sota.md` (apartado 5) | sí |
| 2026-11-24 | `documentador` con `opencode/deepseek-v4.1-flash-free` | «Valida la estructura de la semana 1» (skill `validar-estructura-semanal`), dos veces: la segunda tras corregir los ficheros | Acepté el resultado con su `fichero:línea` (primera pasada: mínimo no cumplía; segunda: mínimo y completo cumplen). Los arreglos los hice yo a mano: enlace en `docs/01b-sota.md:28` y fechas 2026-11-18 en `docs/01-analisis.md:7-15`. No cambié nada de lo que propuso el agente | `docs/01b-sota.md` y `docs/01-analisis.md` (validados, sin cambios del agente); esta fila en `asistenciaIA/bitacora.md` | sí |