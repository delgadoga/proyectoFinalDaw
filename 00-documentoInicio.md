# 00 · Documento de inicio del proyecto

> **Plantilla.** Se rellena **hoy, en la sesión de Inicio (6-nov-2026)** y se afina hasta el **12-nov**, donde el tutor aprueba la propuesta. Es breve: una página. Si algo no lo sabes todavía, escribe «pendiente» y por qué. Borra las notas en cursiva al rellenar.
>
> **No escribas datos personales sensibles** (teléfono, dirección, DNI) ni tu correo personal.

## 1. Datos del alumno/a

| | |
|---|---|
| **Nombre y apellidos** | Gabriela Luz Delgado|
| **Usuario de GitHub** | delgadoga | 
| **Repositorio del proyecto** | *https://github.com/delgadoga/proyectoFinalDaw* |
| **Ciclo y curso** | DAW, 2.º · curso 2026-27 |
| **Fecha** | 2026-11-06 |

## 2. Nombre del proyecto


CMapp. Gestor de contenido y clientes para community managers

## 3. Qué quiero hacer


CM APP es una aplicación web pensada para community managers y pequeñas agencias que gestionan las redes sociales de varios clientes. Reúne en un solo lugar la gestión de cuentas, el calendario de contenido, la aprobación del contenido por parte del cliente y los presupuestos.

Para usarse en primer lugar el community manager da de alta a sus clientes y carga el contrato o presupuesto y el calendario de publicaciones (imágenes, fecha, hora y copy). El cliente se registra, revisa el contrato y lo aprueba o solicita cambios. Una vez aprobado puede acceder a lo planificado y aprueba (por partes o completo), pide cambios o rechaza una idea o publicación, y queda registrado. 


## 4. Qué problema o necesidad resuelve

1. **Planificación:** los calendarios en herramientas genéricas como Notion o Trello sirven como gestor para el CM pero no para el cliente al cual se le debe crear una presentación nueva en PDF con el resumen de las publicaciones, esto es un doble trabajo. Debemos brindarle al cliente en una sola aplicación intuitiva la herramienta necesaria para controlar y aprobar el contenido antes de ser publicado y que sea desde el mismo lugar donde el CM organiza el trabajo.  

2. **Aprobación:** muchos clientes no revisan ni aprueban nada antes de la publicación, y no hay un registro claro de qué se acordó. 

3. **Presupuestos:** se calculan a ojo, sin valores de referencia actualizados y con una cantidad de contenido que no es fija. 

4. **Organización:** archivos, prompts copys y estados (grabado, editado, publicado) dispersos, lo que hace perder tiempo y control. 

## 5. Para quién

Community managers freelance y agencias pequeñas que llevan varias cuentas (el caso de partida es 3). El cliente final es el segundo tipo de usuario: accede a la aplicación para revisar y aprobar el trabajo.

## 6. Funcionalidades principales


| # | Funcionalidad | ¿Imprescindible? (sí / no) |
|---|---|---|
| 1 | Dos tipos de usuario: community manager y cliente (el cliente se registra). | Si
| 2 | Gestión de cuentas y clientes. | Si
| 3 | Calendario de contenido con imágenes, fecha y hora de publicación y copy.| Si
| 4 | Flujo de aprobación: el cliente aprueba (por partes o completo), pide cambios o rechaza una idea o publicación| Si
| 5 | Presupuestos claros que el cliente puede aceptar desde la aplicación.| Si
| 6 | Generación de copys con una API de inteligencia artificial. | No
| 7 | Panel (dashboard) con estadísticas de las cuentas y envío mensual de ideas para el mes siguiente. | No
| 8 | Acceso a las carpetas de Drive con el material que aporta el cliente.| No
| 9 | Programación automática de las publicaciones tras la aprobación.| No


## 7. Tecnologías previstas

| Tecnología | Para qué | Nivel actual (nada / algo / bien) |
|---|---|---|
| Mysql|Base de Datos: cuentas, clientes, piezas de contenido, calendario y presupuestos | algo |
| JavaScript | Interactividad, calendario, previsualizaciones y estados de aprobación | algo |
| Markdown | Documentación | algo |
| Tailwind / Css | Estilos y diseño Responsive | nada/algo |
| Laravel|Framework: login con roles, validaciones, enlaces firmados de aprobación| nada|
|PHP| Lógica de la app, clientes, presupuestos y aprobaciones| nada |


## 8. Dónde se integra con los módulos de 2.º

- [x] Desarrollo web en entorno cliente (0612)
- [x] Desarrollo web en entorno servidor (0613)
- [x] Despliegue de aplicaciones web (0614)
- [x] Diseño de interfaces web (0615)

## 9. Datos y empresas

No es de una empresa, pero usaría esta herramienta como parte de mi trabajo como autónoma.
Puedo usar datos ficticios a modo ejemplo.

## 10. Riesgos y dudas iniciales

- **Tecnología:** Laravel y PHP son nuevos para mí, no tengo conocimientos y no se si tendré tiempo de aprender a usarlos correctamente. 
- **Alcance:** hay cinco funcionalidades imprescindibles. Si el tiempo aprieta, priorizaría calendario y flujo de aprobación, y dejaría los presupuestos en su versión más simple.
- **Tiempo:** Tengo poco tiempo ya que debo hacer el proyecto final, mientras dedico 6 horas diarias a clases, mas traslados, mas 5 horas diarias en mi trabajo como autónoma. y los fines de semana adelanto tareas, estudio para exámenes etc.
- **Duda:** no sé si la programación automática de publicaciones es viable con las APIs de las redes (por eso queda como ampliación).

## 11. Qué espero aprender


Quiero aprender a construir una aplicación completa que me sirva tanto como primer proyecto para mi portfolio y como tener una herramienta útil que pueda usar en mi trabajo como CM.

---

## Aprobación del tutor

| Criterio mínimo | Cumple |
|---|---|
| Necesidad real y documentada | ☐ |
| Alcance abordable en el tiempo disponible | ☐ |
| Integra contenidos de al menos tres módulos de 2.º | ☐ |
| No usa datos personales reales | ☐ |

**Estado:** ☐ Aprobada · ☐ Aprobada con cambios · ☐ Necesita rehacerse

**Fecha:** 

**Comentarios del tutor:**
