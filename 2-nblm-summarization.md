---
layout: default
title: 2 - Resumir
nav_order: 7
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Resumir texto, audio y video

<img src="images/nblm-summarize-text2.gif" style="float:right;width:400px;padding:10px;" alt="Logo GenAI resumiendo texto">
En esta actividad, exploraremos cómo GenAI puede ayudarte a resumir rápidamente notas de reuniones, incluyendo tareas y acuerdos. También descubrirás cómo personalizar estos resúmenes ajustando el tono, el estilo y el nivel de lenguaje. ¿Alguna vez has necesitado crear un resumen en otro idioma para un colega o estudiante? Aquí verás cómo la IA puede traducir tu texto fácilmente.

> NOTA: Como todas las herramientas de IA generativa, NotebookLM a veces comete errores, aunque al proporcionarle datos de entrenamiento, probablemente cometa menos errores que herramientas de IA generalistas. Siempre verifica cualquier afirmación factual si no eres experto en el tema.

Si tienes preguntas o te atoras durante el ejercicio, por favor pide ayuda al instructor.

## Resumir un solo artículo científico con un propósito específico

En vez de resumir los tres artículos, vamos a indicarle a NotebookLM que resuma solo uno y le daremos un enfoque concreto, por ejemplo, para redactar materiales promocionales para un Makerspace universitario o un Centro de Innovación Digital.

1. Desmarca los artículos 2 y 3 en el área de fuentes a la izquierda de la página web.
   <img src="images/nblm-deselect-articles2.png" style="width:500px;padding:10px;border: 1px solid #555;" alt="NotebookLM deseleccionar artículos"><br>
2. En el área de chat escribe: `Crea un mensaje promocional para padres explicando cómo el Makerspace universitario (o Centro de Innovación Digital) puede ayudar a sus hijos a buscar prácticas profesionales y empleo tras graduarse.`
   - ¿El texto que responde NotebookLM te parece útil?
   - ¿Hay inexactitudes?
   - Si quieres cambiar algo, puedes darle instrucciones de seguimiento o editar el mensaje manualmente.
3. Supongamos que el mensaje es correcto pero demasiado largo. Pídele a NotebookLM que lo haga más corto:
   - En el chat escribe: `Acorta el mensaje promocional a 100 palabras.`
   - ¿Cómo queda? ¿Demasiado corto?
   - Prueba con: `Acorta el mensaje promocional a 150 palabras.`
   - ¿Ahora se ajusta mejor? Juega con la longitud, el tono y la audiencia según lo que necesites (por ejemplo, pide un mensaje para estudiantes de primer año).
4. ¿Se te ocurre otra forma de resumir el artículo para un propósito específico?
   - Por ejemplo, para un póster académico: `Dame 5 frases clave para crear un póster académico para una conferencia sobre Makerspaces.`
   - ¿El texto es útil? ¿Hay errores?
   - Puedes seguir ajustando el resumen con nuevas instrucciones.
5. Imagina que te invitan a hablar con estudiantes de primaria sobre tu investigación en insignias digitales (asumiendo que tú escribiste el artículo seleccionado en NotebookLM).
   - En el chat escribe: `Resume el artículo en un discurso de 10 minutos para estudiantes de 5º de primaria. Hazlo ameno y motivador. Incluye una historia corta sobre lo divertido que es un makerspace y cómo las insignias son útiles y geniales.`
   - ¿El texto es adecuado? ¿Hay errores?
   - Puedes ajustar el resultado con nuevas instrucciones si lo necesitas.

## Resumir notas de reuniones y crear tareas

Vamos a resumir la transcripción de una reunión ficticia de un "Comité Ejecutivo de Makerspace" en un nuevo cuaderno:

1. Crea un nuevo cuaderno:
   - Haz clic en el **logo de NotebookLM** en la parte superior derecha para volver a la pantalla principal.
   - Haz clic en el botón azul **Crear nuevo** a la izquierda. Ahora estás en un cuaderno nuevo.
     <img src="images/nblm-new-notebook3.gif" style="width:800px;padding:10px;border: 1px solid #555;" alt="Botón Crear nuevo NotebookLM"><br>
2. Agrega el PDF de las notas de la reunión:
   - Descarga la transcripción de la reunión para usarla como fuente de entrenamiento y toma nota de dónde la guarda tu navegador: [Transcripción de la reunión](images/nblm-meeting-notes.pdf){:target="\_blank"}
   - Sube el documento haciendo clic en el enlace azul **elegir archivo** en el centro de la página, navega hasta el archivo descargado, selecciónalo y ábrelo.
3. Pide a NotebookLM un resumen:
   - En el chat escribe: `Resume la transcripción de la reunión en viñetas.`
     - ¿El resumen es fiel a la reunión?
   - Si quieres más detalles, escribe: `Dame más detalles.`
4. Finalmente, genera una lista de tareas asignadas y no asignadas:
   - Escribe: `Crea una lista detallada de tareas en viñetas, indicando las asignadas a personas y las no asignadas.`
   - ¿La lista es completa? ¿Falta alguna tarea?

> NOTA: Siempre pide a alguien que asistió a la reunión que revise el resumen y las tareas generadas.

## Resúmenes y tareas traducidas

1. Traduzcamos el resumen de la reunión al portugués:
   - Escribe: `Crea un resumen detallado de la reunión en portugués.`
     - Si no hablas portugués, puede ser difícil evaluar el resultado, pero suele ser bastante preciso.
   - Escribe: `Crea una lista detallada de tareas en viñetas, indicando las asignadas a personas y las no asignadas en portugués.`
   - Prueba a traducir las notas a otro idioma que conozcas.
     - ¿La traducción es precisa?

## Prueba a resumir tus propias notas de clase o presentaciones

1. ¿Por qué no pruebas a resumir tus propias notas de clase?
   - Crea un nuevo cuaderno e importa notas de una o varias clases.
   - También puedes añadir presentaciones en PDF o Google Slides (NotebookLM solo puede leer estos formatos). Puedes convertir presentaciones de PowerPoint a Google Slides fácilmente (busca una guía en internet).

## Resumir videos de YouTube

- NotebookLM también puede resumir uno o varios videos de YouTube. ¡Pruébalo en un cuaderno nuevo!

[SIGUIENTE PASO: Estrategias de lluvia de ideas](3-nblm-brainstorming.md){: .btn .btn-blue }
