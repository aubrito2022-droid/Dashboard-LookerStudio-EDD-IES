# Dashboard-LookerStudio-EDD-IES
Dashboard de Evaluación de Desempeño Docente – Looker Studio
1. Objetivo del panel

Este panel de analítica tiene como objetivo apoyar el seguimiento y control del proceso de Evaluación de Desempeño Docente, a partir de las respuestas de estudiantes de una Institución de Educación Superior.

El dashboard busca responder principalmente las siguientes preguntas:
¿Cuál es el nivel de avance del proceso de evaluación (respuestas recibidas vs. esperadas)?
¿Cómo se distribuyen los resultados por dimensión del instrumento?
¿Qué desempeño presentan los distintos ítems evaluados por los estudiantes?
¿Existen patrones relevantes que puedan apoyar la toma de decisiones académicas?

El foco del panel es facilitar una lectura clara y accionable de los resultados, orientada a equipos académicos y directivos no técnicos.

2. Fuentes de datos utilizadas

Los datos utilizados provienen de la Encuesta de Evaluación de Desempeño Docente aplicada a estudiantes, y consideran, entre otros, los siguientes campos:

Identificador del docente
Carrera / programa
Asignatura
Dimensión evaluada
Ítem del instrumento
Puntaje o escala de evaluación
Fecha de respuesta
Para efectos de este repositorio, los datos han sido anonimizados y utilizados únicamente con fines demostrativos.

3. Proceso de limpieza y transformación de datos

El proceso de preparación de los datos se realizó en tres etapas principales:
Revisión y depuración inicial
Eliminación de registros incompletos o duplicados
Validación de escalas de respuesta
Normalización de nombres de dimensiones e ítems
Transformación
Estandarización de formatos (fechas, textos)
Creación de campos calculados para análisis:
Conteo de respuestas
Porcentaje de avance del proceso
Promedios por dimensión e ítem
Preparación para visualización
Estructuración del dataset final para su consumo en Looker Studio
Separación entre datos crudos y datos procesados

4. Decisiones de diseño del panel

Las principales decisiones de diseño del dashboard fueron:
Enfoque progresivo: primero mostrar el avance del proceso (participación), y luego los resultados de desempeño.
Uso de visualizaciones simples (tarjetas, barras y tablas), priorizando claridad por sobre complejidad.
Agrupación por dimensiones para facilitar la lectura global del instrumento antes de bajar al nivel de ítem.
Lenguaje claro y etiquetas comprensibles, pensando en usuarios no técnicos.
Interactividad básica mediante filtros por carrera, asignatura o período, permitiendo distintos niveles de análisis.
El dashboard fue diseñado como una herramienta de apoyo a la gestión académica y no como un reporte técnico.

5. Dashboard
El panel fue desarrollado en Looker Studio.
El enlace al dashboard puede encontrarse en el archivo: https://lookerstudio.google.com/reporting/afad61e0-0a73-4ecb-9b39-df8b1e38ddf3
