### Resumen de "Prompt Engineering Avanzado"

**Objetivos**: Aprender a diseñar prompts estructurados para optimizar respuestas de LLMs (GPT-4/5, Claude, etc.), comprendiendo su funcionamiento interno, diferenciando roles (system, user, assistant), identificando ruido, creando plantillas reutilizables, iterando respuestas y aplicando técnicas avanzadas como Chain-of-Thought (CoT), ReAct, Self-Consistency y JSON enforced, además de documentar prompts como activos.

**Índice Rápido**: Cubre fundamentos, tipos de prompts, anatomía, ruido, frameworks, técnicas avanzadas, laboratorios comparativos, evaluación, gestión de memoria, bibliotecas de prompts, buenas prácticas y checklist.

**Fundamentos**: Al llamar a un LLM, el texto se tokeniza, se ajusta al límite de contexto, genera tokens secuenciales con atención, aplica filtros y retorna resultados. "Se olvidó" por exceso de contexto, cambios sin refuerzos o ruido semántico.

**Roles de Mensaje**: System (marco, políticas), User (tarea), Assistant (respuesta), Tool (herramientas). Mantener System breve y versionado.

**Tipos de Prompt**: Simple, contextualizado, few-shot, estructurado, CoT, parametrizado, multi-turn, ReAct, evaluador, auto-reflexivo, JSON, guardrails.

**Anatomía**: Incluye rol, objetivo, entrada, formato, criterios, proceso, restricciones, ejemplos y verificación.

**Fuentes de Ruido**: Ambigüedad, idiomas mixtos, contradicciones, ejemplos irrelevantes. Mitigación con limpieza y delimitadores.

**Frameworks**: Plantilla genérica con rol, objetivo, datos, formato JSON, restricciones y proceso. Ejemplos: RTF, CRISPE.

**Técnicas Avanzadas**: CoT, Self-Consistency, ReAct, Tree-of-Thought, auto-reflexión, guardrails, tool augmentation (con ejercicios).

**Laboratorios**: Comparativas (resumen, código, matemáticas) con evidencia en tablas.

**Prompt Libraries**: Uso de PromptHub, GitHub Awesome Prompting, OpenAI Examples.

**Buenas Prácticas**: Versionado con Git, tests automáticos, placeholders.

**Checklist**: Verificar rol, objetivo, formato, criterios, etc. (10 ítems).

**Referencias**: Vaswani (2017), Brown (2020), Wei (2022), Yao (2022), etc.