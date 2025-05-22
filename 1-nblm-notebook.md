---
layout: default
title: 1 - Un asistente GenAI personalizado
nav_order: 6
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Primeros pasos con la _Guía del cuaderno_ de NotebookLM

<img src="images/5-notebooklm-logo.png" style="float:right;width:350px;padding:10px;" alt="Logo NotebookLM">
"Sube archivos PDF, sitios web, videos de YouTube, archivos de audio, Google Docs o Google Slides, y NotebookLM los resumirá y hará conexiones interesantes entre los temas. Con todas tus fuentes cargadas, NotebookLM se convierte en un experto personalizado en la información que más te importa. NotebookLM proporciona citas claras para su trabajo, mostrándote las citas exactas de tus fuentes. NotebookLM no utiliza tus datos personales, incluidas tus fuentes, consultas y respuestas del modelo para entrenamiento." ([NotebookLM](https://notebooklm.google/){:target="_blank"}, 2024)

> NOTA: Como todas las herramientas de IA generativa, NotebookLM a veces comete errores, aunque al proporcionarle datos de entrenamiento, probablemente cometa menos errores que herramientas de IA generalistas. Siempre verifica cualquier afirmación factual si no eres experto en el tema.

Si tienes preguntas o te atoras durante el ejercicio, por favor pide ayuda al instructor.

## Iniciar sesión en NotebookLM

- Si aún no lo has hecho, navega al sitio web de [NotebookLM](https://notebooklm.google/){:target="\_blank"}.
- Haz clic en el botón negro **Probar NotebookLM** y luego inicia sesión con una cuenta de Google o Gmail.
  > NOTA: Si no tienes una cuenta de Google o Gmail, haz clic en el enlace **Crear cuenta** para crear una antes de iniciar sesión. Si tienes problemas para iniciar sesión, pide ayuda al instructor.

<img src="images/5-notebooklm-try.png" style="width:800px;padding:10px;border: 1px solid #555;" alt="Botón Probar NotebookLM"><br>

## Crear un cuaderno y agregar documentos

Antes de comenzar a probar, necesitamos crear un nuevo cuaderno y agregarle algunos documentos y medios para que tenga fuentes con las que entrenar y trabajar.

1. Descarga los siguientes tres documentos para usarlos como datos de entrenamiento en esta actividad y toma nota de dónde los guarda tu navegador (normalmente en Descargas o Escritorio):
   - [Documento 1](images/badge-article.pdf){:target="\_blank"}
   - [Documento 2](images/badge-article-2.pdf){:target="\_blank"}
   - [Documento 3](images/badge-article-3.pdf){:target="\_blank"}
2. Crea un nuevo cuaderno haciendo clic en el botón azul **Crear**.
   <img src="images/nblm-create.png" style="width:600px;padding:10px;border: 1px solid #555;" alt="Botón Crear NotebookLM"><br>
3. Sube los tres documentos descargados haciendo clic en el enlace azul **elegir archivo** en el centro de la página.
   <img src="images/nblm-add-docs.gif" style="width:800px;padding:10px;border: 1px solid #555;" alt="Agregar documentos"><br>
4. ¡Listo! Ahora puedes explorar la Guía del cuaderno.

## Explorando la Guía del cuaderno

1. Cada artículo tendrá un resumen al hacer clic en él en el panel izquierdo de fuentes.
   - Para los 3 artículos será visible (ver ejemplo en la imagen), la frase comienza con: Tres fuentes exploran el uso de insignias digitales en educación y desarrollo profesional... Un experto en credenciales informales (o insignias) ha revisado el resumen y es preciso respecto a la información de los tres artículos.
     <img src="images/nblm-summary.png" style="width:600px;padding:10px;border: 1px solid #555;" alt="Resumen"><br>
     > **NOTA: Debes verificar siempre la exactitud de los hechos y afirmaciones de NotebookLM (y cualquier herramienta GenAI), ya que a veces cometen errores o alucinan.
     > Nota: Hay varias pequeñas alucinaciones en la Guía del cuaderno. La guía NO proporciona citas fácilmente verificables, lo que dificulta comprobar sus afirmaciones.**
2. **Resumen de pódcast**:

- Para crear un resumen en formato pódcast, solo haz clic en el botón azul **Generar** **-O-** puedes hacer clic en **Personalizar** para dar más contexto antes de generar el pódcast. Por ejemplo: "La audiencia de este pódcast son padres que envían a su hijo a la universidad por primera vez y les preocupa el futuro laboral de su hijo tras graduarse."
- Suele tardar entre dos y cinco minutos en generarse, y los pódcast suelen durar entre 10 y 18 minutos según la información a resumir.<br>
  <img src="images/nblm-generate-podcast.png" style="width:400px;padding:10px;border: 1px solid #555;" alt="Botón Generar Pódcast NotebookLM"><br>
- Una vez generado, puedes escucharlo haciendo clic en el botón azul claro de reproducir.
- Para descargar el pódcast y compartirlo, haz clic en los **tres puntos verticales** a la derecha del botón de reproducir y luego en **Descargar**.
- Si no quieres esperar, puedes escuchar la versión creada para el DSC: [Audio resumen del pódcast](images/nblm-podcast-summary.mp3){:target="\_blank"} (12 min).
  > - **Reflexión**: ¿Qué opinas de la calidad del pódcast generado?
  > - **Reflexión**: ¿En qué situaciones crees que sería útil este tipo de resumen en pódcast?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de resumen generado por GenAI?

3. **Documento informativo (Briefing Document)**:

- Los documentos informativos permiten entender rápidamente el contenido de los documentos en tu cuaderno. **NOTA**: NotebookLM no proporciona citas en línea en este tipo de documento, lo que dificulta verificar afirmaciones.
- Para crear uno, haz clic en el botón **Documento informativo**. Tarda 30-60 segundos en generarse (se titulará "Insignias digitales: visión general").<br>
  <img src="images/nblm-briefing-doc-button2.png" style="width:400px;padding:10px;border: 1px solid #555;" alt="Botón Documento informativo"><br>
  > - **Reflexión**: ¿Qué opinas de la calidad del documento informativo?
  > - **Reflexión**: ¿En qué situaciones te sería útil este tipo de resumen?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de resumen generado por GenAI?

4. **Guía de estudio (Study Guide)**:

- Las guías de estudio son útiles para poner a prueba tus conocimientos con preguntas de respuesta corta generadas por GenAI (con respuestas incluidas para autoevaluación).
- También incluyen preguntas de ensayo (sin respuesta) y un glosario de términos potencialmente útil.
- Para crear una guía de estudio, haz clic en el botón **Guía de estudio**. Tarda 30-60 segundos en generarse.<br>
  <img src="images/nblm-study-guide-button2.png" style="width:400px;padding:10px;border: 1px solid #555;" alt="Botón Guía de estudio"><br>
  > - **Reflexión**: ¿Qué opinas de la calidad de las preguntas y respuestas de la guía de estudio?
  > - **Reflexión**: ¿En qué situaciones te sería útil este tipo de guía?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de guía generada por GenAI?

5. **Línea de tiempo (Timeline)**:

- El resumen de línea de tiempo lista los eventos principales de todos los documentos en orden cronológico. Es útil cuando trabajas con varios documentos, ya que NotebookLM los organiza por fecha con un breve resumen.
- Para crear una línea de tiempo, haz clic en el botón **Línea de tiempo**. Tarda 30-60 segundos en generarse.<br>
  <img src="images/nblm-timeline-button2.png" style="width:400px;padding:10px;border: 1px solid #555;" alt="Botón Línea de tiempo"><br>
  > - **Reflexión**: ¿Qué opinas de la calidad de las fechas y resúmenes de la línea de tiempo? ¿Falta algo?
  > - **Reflexión**: ¿En qué situaciones te sería útil una línea de tiempo?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de línea de tiempo generada por GenAI?

6. **Preguntas frecuentes (FAQ)**:

- Esta función crea un resumen para cada documento en tu cuaderno. Puede ayudarte a identificar en qué documento se encuentra cierta información o concepto.
- Para crear un FAQ, haz clic en el botón **Preguntas frecuentes**. Tarda 30-60 segundos en generarse.<br>
  <img src="images/nblm-faq-button2.png" style="width:400px;padding:10px;border: 1px solid #555;" alt="Botón Preguntas frecuentes"><br>
  > - **Reflexión**: ¿Qué opinas de la calidad de las preguntas frecuentes?
  > - **Reflexión**: ¿Crees que el FAQ puede ser útil para estudiar o repasar?
  > - **Reflexión**: ¿Ves posibles inconvenientes o problemas con este tipo de FAQ generadas por GenAI?

Nota: ya no existe la función o botón de **tabla de contenidos**.

## Chateando con tu cuaderno

En las siguientes actividades, experimentaremos con técnicas de chat interactivas para explorar qué más puede hacer NotebookLM por ti.

[SIGUIENTE PASO: Resumen de texto/audio/video](2-nblm-summarization.md){: .btn .btn-blue }
