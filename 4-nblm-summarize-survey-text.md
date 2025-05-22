---
layout: default
title: 4 - Resumir respuestas de encuestas
nav_order: 8
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Resumir respuestas abiertas de encuestas

<img src="images/4-survey-logo.jpeg" style="float:right;width:300px;padding:10px;" alt="Decorativo">
En esta actividad, exploraremos cómo GenAI puede ayudarte a resumir respuestas abiertas de encuestas, para identificar rápidamente los temas clave mencionados por los participantes. Si tienes varias preguntas, deberás subir las respuestas de cada una en documentos separados. También veremos cómo personalizar los resúmenes ajustando el tono, el estilo y el nivel de lenguaje.

> NOTA: Como todas las herramientas de IA generativa, NotebookLM a veces comete errores, aunque al proporcionarle datos de entrenamiento, probablemente cometa menos errores que herramientas de IA generalistas. Siempre verifica cualquier afirmación factual al analizar respuestas de encuestas.

Si tienes preguntas o te atoras durante el ejercicio, por favor pide ayuda al instructor.

**Esquema:**

- Resumir comentarios de una sola pregunta abierta.
- Usar diferentes estrategias de prompt para personalizar el resumen: personas, ejemplos, tono, nivel de vocabulario y voz.
- Explorar la utilidad de las citas de NotebookLM, especialmente cómo llevan a los pasajes del documento que respaldan el resumen. Esto es muy útil para la verificación.

## Primeros pasos

Volvamos al cuaderno con los tres artículos científicos y agreguemos un video de YouTube para tener cuatro fuentes de información:

1. Descarga los siguientes dos documentos, cada uno con respuestas a una pregunta de encuesta, para usarlos como datos de entrenamiento. Cuando trabajes con tus propios datos, exporta las respuestas de cada pregunta en documentos separados (TXT o PDF). Toma nota de dónde guarda tu navegador los archivos:
   - [Respuestas Pregunta 1](images/survey-question-1.pdf){:target="\_blank"}
   - [Respuestas Pregunta 2](images/survey-question-2.pdf){:target="\_blank"}
2. Crea un nuevo cuaderno haciendo clic en el botón azul **Crear nuevo** a la izquierda.
   <img src="images/nblm-create-new.png" style="width:600px;padding:10px;border: 1px solid #555;" alt="Botón Crear nuevo NotebookLM"><br>
3. Sube los dos documentos descargados haciendo clic en el enlace azul **elegir archivo** en el centro de la página. Puedes seleccionarlos juntos o agregarlos uno por uno.<br>
   <img src="images/nblm-add-surveys3.gif" style="width:800px;padding:10px;border: 1px solid #555;" alt="Agregar documentos de encuesta"><br>
4. ¡Listo! Ahora puedes explorar cómo resumir las respuestas de la encuesta.

## Exploración inicial de las respuestas a la Pregunta 1

1. Limitemos el primer resumen a las respuestas de la Pregunta 1:
   - Desmarca el archivo **survey-question-2.pdf** haciendo clic en la casilla a la derecha del nombre.<br>
     <img src="images/nblm-deselect-q-2.png" style="width:250px;padding:20px;border: 1px solid #555;" alt="Botón Crear nuevo NotebookLM"><br>
   - Ahora solo harás preguntas sobre las respuestas a la _Pregunta 1_.
2. Pide a NotebookLM que resuma las respuestas escribiendo en el chat: `Analiza las siguientes respuestas abiertas de participantes en un taller universitario. Resume los comentarios clave identificando temas recurrentes, sugerencias de mejora y aspectos positivos destacados. Señala ideas accionables y patrones en las opiniones. Presenta los hallazgos de forma clara, categorizando en fortalezas, áreas de mejora y comentarios adicionales. El resumen debe ser conciso y fácil de entender.`

- **Reflexión**: ¿Los temas y sugerencias parecen razonables según los comentarios del PDF?
- **Reflexión**: Si se destacan ciertos instructores, ¿es porque enseñan la mayoría de los talleres o hay otros igual de expertos que no aparecen? (Esto sería algo a investigar si fuera tu proyecto de investigación).

3. NotebookLM proporciona citas enlazables para las afirmaciones o interpretaciones que hace. Comprueba si estas citas ayudan a validar lo que dice:

- Haz clic en el primer enlace de cita (un **1** en un círculo gris).
- Aparecerá la guía de fuentes a la derecha. Lee el pasaje resaltado y verifica si respalda la afirmación.<br>
  <img src="images/nblm-citation-check.png" style="width:800px;padding:10px;border: 1px solid #555;" alt="Verificación de cita"><br>
- Haz clic en el segundo enlace de cita (**2** en círculo gris). ¿El pasaje respalda la afirmación?
- Puedes revisar más citas si lo deseas.

4. Cierra la **guía de fuentes** haciendo clic en el icono en la esquina superior derecha del área de la guía (ver imagen).
   <img src="images/nblm-close-source-guide.png" style="float:right;width:250px;padding:10px;border: 1px solid #555;" alt="Cerrar guía de fuentes">
5. Ahora revisa las respuestas a la Pregunta 2:

- Marca la casilla de **survey-question-2.pdf** y desmarca **survey-question-1.pdf**.
  <img src="images/nblm-deselect-q-1.png" style="float:right;width:250px;padding:10px;border: 1px solid #555;" alt="Desmarcar documento 1 y marcar documento 2">
- Pide a NotebookLM que resuma las respuestas de la Pregunta 2 escribiendo: `Analiza las siguientes respuestas abiertas de participantes en un taller universitario. Resume los comentarios clave identificando temas recurrentes, sugerencias de mejora y aspectos positivos destacados. Señala ideas accionables y patrones en las opiniones. Presenta los hallazgos de forma clara, categorizando en fortalezas, áreas de mejora y comentarios adicionales. El resumen debe ser conciso y fácil de entender.`
- El resumen será más corto, ya que hubo menos respuestas.
- Revisa las citas para ver si son razonables.
- Puedes pedir: `Amplía la sección de Ideas Accionables.`
  > - **Reflexión**: ¿Qué opinas de la calidad de los resúmenes?
  > - **Reflexión**: ¿Esto podría ayudarte en tu flujo de trabajo de investigación? ¿Vale la pena mejorar tus habilidades de prompt para aprovechar NotebookLM?
  > - **Reflexión**: ¿Qué riesgos ves en depender demasiado de resúmenes generados por GenAI para tu investigación?

## Herramientas de Studio

1. Prepárate para explorar las herramientas Studio de NotebookLM:
   - Haz clic en la casilla **Seleccionar todas las fuentes** abajo a la derecha.
   - Si el panel **Studio** no está abierto, haz clic en el icono de expandir Studio. Ahora deberías ver el panel a la derecha.
     <img src="images/nblm-studio-tools.png" style="width:800px;padding:10px;border: 1px solid #555;" alt="Herramientas Studio"><br>
2. **Resumen de pódcast**:

- Para crear un resumen en pódcast, haz clic en el botón azul **Generar** (ver imagen). Suele tardar entre dos y cinco minutos y dura entre 10 y 18 minutos según la información.<br>
- Puedes escucharlo haciendo clic en el botón azul claro de reproducir.
- Para descargarlo, haz clic en los **tres puntos verticales** a la derecha y luego en **Descargar**.
- Si no quieres esperar, puedes escuchar la versión creada para el DSC: [Audio resumen del pódcast](images/nblm-podcast-summary.mp3){:target="\_blank"} (12 min).
  > - **Reflexión**: ¿Qué opinas de la calidad del pódcast generado?
  > - **Reflexión**: ¿En qué situaciones crees que sería útil este tipo de resumen en pódcast?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de resumen generado por GenAI?

3. **Documento informativo**:<img src="images/nblm-studio-notes.png" style="float:right;width:300px;padding:20px;border: 1px solid #555;" alt="Notas Studio">

- Los documentos informativos permiten resumir y entender rápidamente el contenido de los comentarios de la encuesta. **NOTA**: NotebookLM no proporciona citas en línea en este tipo de documento, lo que dificulta verificar afirmaciones.
  - Para crear uno, haz clic en el botón **Documento informativo** a la derecha. Tarda 30-60 segundos en generarse.<br>
  - Cuando termine, haz clic en el enlace del documento generado y revisa el resumen.
    > - **Reflexión**: ¿Qué opinas de la calidad del resumen?
    > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de resumen generado por GenAI?

4. **FAQ**: Probablemente no sea muy útil para evaluar respuestas abiertas, pero puedes probarlo y avisar al instructor si encuentras algo útil.
5. **Guía de estudio**: Tampoco suele ser útil en este contexto, pero puedes probar el botón **Guía de estudio** y comentar al instructor si encuentras algo relevante.
6. **Línea de tiempo**: Si no hay fechas en los comentarios, NotebookLM no podrá generar una línea de tiempo. ¡Pruébalo y observa qué sucede!

[SIGUIENTE PASO: Crear presentaciones](5-nblm-presentations.md){: .btn .btn-blue }
