# AGENTS.md — Protocolo de consulta de reglas vigentes

Este repositorio es la fuente versionada de las instrucciones de trabajo de Azu. Antes de ejecutar una tarea que use estas reglas:

1. Leer `README.md` de la rama predeterminada `gpt-main` desde GitHub; no usar una copia antigua si la conexión está disponible.
2. Identificar las instrucciones pertinentes a la tarea y aplicarlas, respetando las instrucciones de mayor prioridad de la plataforma y las solicitudes actuales de Azu.
3. Para tareas de La Unión Mudanzas o desarrollo, consultar también `launionmudanzas/plataforma-logistica`, especialmente `CLAUDE.md` y `docs/ESTADO_REAL_DEL_PROYECTO.md`, y comprobar si hay cambios posteriores al último corte.
4. Distinguir hechos comprobados, información reportada, propuestas, acciones ejecutadas y pendientes. Nunca afirmar que un cambio quedó guardado en una app o computadora sin evidencia.
5. No duplicar instrucciones, tarifas ni catálogos existentes; no inventar datos ni cambiar reglas ratificadas. Antes de escribir, revisar fuente, versión y consecuencias.
6. Si GitHub no está accesible, declarar esa limitación y trabajar con el contexto verificable disponible, sin fingir actualización.
7. No publicar secretos, contactos, precios internos ni datos de clientes en repositorios públicos.

## Alcance técnico
Este archivo proporciona instrucciones a agentes que lean este repositorio. **No activa por sí mismo** un disparador automático en todos los chats de ChatGPT, ni sincroniza la base de datos local. Para un GPT personalizado, incluir en sus instrucciones la obligación de consultar este repositorio al comenzar tareas relevantes; el conector GitHub debe estar habilitado para ese GPT.
