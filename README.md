# Taller IA

Juan Pablo Poveda Cañon

## Description

Lang Chain, Pinecone y OpenAI ofrece oportunidades para abordar una variedad de desafíos. Desde la generación de contenido creativo hasta el análisis de datos complejos, estas tecnologías pueden unirse para resolver desafíos específicos en diferentes campos, impulsando la innovación y la eficiencia en el proceso.

## Ejecución

1. Instalamos los requerimientos
   
`pip install -r requirements.txt`

![Screenshot 2024-04-16 152900](https://github.com/juancanon1725/TallerAI_AREP/assets/98672541/426f8ecb-3ab9-4512-8dae-f4ddf22b0bff)

2. Se genera una llave de Pinecone.

![APIkeys](https://github.com/juancanon1725/TallerAI_AREP/assets/98672541/2d731223-b7d0-420c-a608-651cc4052141)

3. Se le asigna una llave de OpenAI.
   
![keysproject](https://github.com/juancanon1725/TallerAI_AREP/assets/98672541/e2d31cd5-e24c-480a-a7bc-b5f1ccbfb41e)

4. Se realiza la compilación y la ejecución del programa python central con la llave de OpenAI.

`python RAPpinecone`

![Screenshot 2024-04-16 152744](https://github.com/juancanon1725/TallerAI_AREP/assets/98672541/a2f4a3e0-98d6-46a0-89f3-78231bc28b0e)

5. Se debe cargar un documento de texto en un archivo llamado "Conocimiento.txt".

6. En seguida, se realiza una búsqueda de similitud en los documentos almacenados en Pinecone utilizando un query dado la pregunta especifica establecida: ("Por que el conejo acabó quedándose solo").

7. Nos brinda un index parecido al siguiente.

![indexes](https://github.com/juancanon1725/TallerAI_AREP/assets/98672541/6bd3f6e5-e27d-42b5-ab09-e92a7ff384c1)

## Conceptos

* *RAG* (Retrieval-Augmented Generation) es una técnica utilizada para mejorar el conocimiento de los modelos de lenguaje mediante la incorporación de datos adicionales.
  
* *OpenAI* proporciona una gama de modelos con diferentes niveles de capacidad, diseñados para adaptarse a diversas tareas y requisitos específicos.
  
* *Pinecone* es una base de datos vectorial con una amplia funcionalidad. En términos simples, una base de datos vectorial es un tipo de base de datos diseñada específicamente para almacenar y recuperar vectores, que son representaciones numéricas de datos en un espacio multidimensional. 

## Arquitectura

La arquitectura representa las capacidades de Lang Chain, OpenAI y Pinecone para procesar texto, generar embeddings y realizar búsquedas de similitud en documentos de texto.

