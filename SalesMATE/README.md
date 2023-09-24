# HackMty2023

## Intro
------------
App en Python que te permite hablar con multiples PDFs, puedes preguntarle cosas sobre ellos y te contestará lo más relevantes. Es importante notar que la app solo responderá preguntas en base al PDF.

## Como funciona
------------

1. Carga PDFs: La aplicacion lee multiples documentos PDF y extrae su contenido como texto.

2. Text Chunking: El texto extraido se separa en pedazos más pequeños para procesarlos efectivamente. 

3. Language Model: La aplicación utiliza un modelo de lenguaje que genera representaciones de vectores (embeddings).

4. Similarity Matching: Cuando se le hace una pregunta se comprara con los PDFs subidos.
   
6. Response Generation: Los chunks seleccionados se pasan al modelo y genera una respuesta relevante.


## Instalación
----------------------------

1. Clonar el repositorio

2. Instala los requerimientos con el comando:
   ```
   pip install -r requirements.txt
   ```

3. Obten un Key de API y agrégalo a `.env`.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```
