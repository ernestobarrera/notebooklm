---
layout: default
title: 3 - Lluvia de ideas para preguntas de investigación
nav_order: 8
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Lluvia de ideas e ideación para preguntas de investigación

<img src="images/nblm-brain-storm.jpeg" style="float:right;width:400px;padding:10px;" alt="Visualización lluvia de ideas">
En esta actividad, exploraremos cómo GenAI puede ayudarte a identificar vacíos en la literatura y generar preguntas de investigación a partir de un grupo de artículos científicos y un video.

> NOTA: Como todas las herramientas de IA generativa, NotebookLM a veces comete errores, aunque al proporcionarle datos de entrenamiento, probablemente cometa menos errores que herramientas de IA generalistas. Siempre verifica cualquier afirmación factual si no eres experto en el tema.

Si tienes preguntas o te atoras durante el ejercicio, por favor pide ayuda al instructor.

## Primeros pasos

Volvamos al cuaderno con los tres artículos científicos que ya creamos y agreguemos un video de YouTube para que NotebookLM tenga cuatro fuentes de información:

1. Haz clic en el **logo de NotebookLM** en la parte superior derecha para salir del cuaderno actual y volver a la pantalla principal.
2. Haz clic en el cuaderno **El ecosistema de insignias digitales en bibliotecas**.
3. Haz clic en el botón **Agregar fuente** sobre la lista de artículos.<br>
   <img src="images/nblm-new-source2.png" style="width:300px;padding:10px;" alt="Agregar nueva fuente NotebookLM"><br>
4. Haz clic en el botón **YouTube** en la parte inferior central.<br>
   <img src="images/nblm-new-youtube.png" style="width:300px;padding:10px;" alt="Agregar video de YouTube"><br>
5. Pega la siguiente dirección web en el cuadro de texto: `https://www.youtube.com/watch?v=zdJM7gJAJiw`<br>
   <img src="images/nblm-youtube-url.png" style="width:600px;padding:10px;" alt="Agregar URL de YouTube"><br>

## Exploración inicial

1. Crea una lista de posibles limitaciones o vacíos en los artículos y el video escribiendo en el chat: `¿Cuáles son las limitaciones o vacíos más importantes mencionados en estos estudios?`
   > - **Reflexión**: ¿Las limitaciones y vacíos parecen razonables?
2. Identifica hallazgos sorprendentes o contraintuitivos escribiendo: `Extrae 2-3 hallazgos sorprendentes o contraintuitivos de estos artículos.`

- **Reflexión**: ¿Los hallazgos están respaldados por citas?

3. Identifica hallazgos o interpretaciones contradictorias escribiendo: `Identifica hallazgos o interpretaciones contradictorias entre estos estudios.`

- **Reflexión**: ¿Las contradicciones están respaldadas por citas?

4. Identifica temas comunes o preguntas de investigación compartidas escribiendo: `¿Qué temas o preguntas de investigación comunes surgen al analizar estos artículos juntos?`

- **Reflexión**: ¿Los temas y preguntas parecen razonables según lo que has leído?

## Generación de preguntas de investigación

1. Crea una lista de posibles preguntas de investigación escribiendo: `Con base en las limitaciones y vacíos de los tres artículos, propone 3-4 preguntas de investigación que puedan abordarlos.`
   > - **Reflexión**: ¿Las preguntas propuestas son razonables?
2. Sugiere preguntas interdisciplinarias escribiendo: `Sugiere preguntas de investigación interdisciplinarias que combinen enfoques metodológicos de todas las fuentes.`
   > - **Reflexión**: ¿Estas preguntas te parecen más o menos interesantes que las anteriores?
3. Pide áreas o tecnologías emergentes escribiendo: `¿Qué áreas o tecnologías emergentes podrían aportar nuevas perspectivas sobre los temas tratados en todas las fuentes?`
   > - **Reflexión**: ¿Alguna tecnología o área sugerida te parece interesante para investigar?

## Refinamiento y evaluación

1. Elige 3 de las mejores preguntas generadas y evalúalas con el siguiente prompt (reemplaza Pregunta A, B y C por tus preguntas):
   `Evalúa estas preguntas de investigación según originalidad, viabilidad e impacto potencial:`
   `  - Pregunta A`
   `  - Pregunta B`
   `  - Pregunta C`
   > - **Reflexión**: ¿Qué opinas de las críticas a cada pregunta?
   > - **Reflexión**: ¿Alguna crítica cambia tu evaluación sobre la calidad de las preguntas?
2. Pide enfoques metodológicos para cada pregunta:

- `Sugiere enfoques metodológicos para abordar la pregunta de investigación: PREGUNTA A`
- `Sugiere enfoques metodológicos para abordar la pregunta de investigación: PREGUNTA B`
- `Sugiere enfoques metodológicos para abordar la pregunta de investigación: PREGUNTA C`

3. Identifica posibles retos o limitaciones para cada pregunta:

- `¿Qué retos o limitaciones podrían surgir al abordar la pregunta: PREGUNTA A?`
- `¿Qué retos o limitaciones podrían surgir al abordar la pregunta: PREGUNTA B?`
- `¿Qué retos o limitaciones podrían surgir al abordar la pregunta: PREGUNTA C?`

## OPCIONAL: Realiza la actividad con tu propio tema

Si tienes un tema de investigación propio y artículos relacionados, puedes realizar esta actividad desde el principio en un cuaderno nuevo. Si tienes dudas, pide apoyo al instructor.

> ## Recomendaciones para el taller:
>
> - Usa prompts claros y específicos
> - Itera y refina tus preguntas
> - Considera múltiples perspectivas
> - Mantente abierto a ideas inesperadas

[SIGUIENTE PASO: Resumir respuestas abiertas de encuestas](4-nblm-summarize-survey-text.md){: .btn .btn-blue }
