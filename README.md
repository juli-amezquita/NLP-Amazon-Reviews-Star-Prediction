# NLP-Amazon-Reviews-Star-Prediction
Natural Language Processing in Spanish. Classify a review based on its text. 

Dataset: [The Multilingual Amazon Reviews Corpus](https://registry.opendata.aws/amazon-reviews-ml/)

Este proyecto con fines académicos, está enfocado en las diferentes técnicas y aplicaciones del procesamiento de lenguaje natural, para lo cual se utilizará el dataset de "The Multilingual Amazon Reviews Corpus". Esta base de datos incluye las opiniones (reviews) en español, así como las respectivas puntuaciones que dan los usuarios y clientes respecto a los productos que fueron adquiridos a través de la plataforma. El dataset se puede descargar del siguiente [link](https://drive.google.com/uc?export=download&id=11XnXB7Ubgf3t6gotXGlM4FCwPOMHhDLX). 

***El Objetivo principal de este proyecto será implementar un modelo que permita, a partir de la opinión de un cliente, predecir la cantidad de estrellas con las que finalmente será calificado el producto o servicio.***

Para desarrollar este objetivo se construirá un modelo de clasificación de aprendizaje supervisado y para ello se seguirán los siguientes pasos:

1. Instalación e importación de las librerías a utilizar.
1. Análisis exploratorio de datos.
1. Limpieza, transformación y procesamiento de datos haciendo uso de librerías especializadas para el procesamiento de textos, incluyendo la eliminación de stopwords, limpieza y lematización de textos, entre otras.
1. Elaboración del modelo, para ello de realizará lo siguiente:
   * Train test split
   * Implementación de un modelo base o de benchmark para comparar los resultados.
   * Aplicación de métodos de vectorización como TFIDF y BOW
   * Elección de una métrica apropiada de evaluación.
   * Ejecución de varios modelos.
   * Optimización de hiperparámetros.
   * Análisis, comparación de resultados y elección del mejor modelo.
1. Finalmente, se re-planteará el problema de Machine Learning en un problema binario, es decir, se asignarán únicamente las etiquetas Positiva y Negativa a cada crítica para ver cómo se comporta la predicción.
1. Conclusiones Generales.

#### ***Este proyecto se escribió en un Jupyter Notebook y puede visualizarse haciendo click [aquí](https://nbviewer.jupyter.org/github/juli-amezquita/NLP-Amazon-Reviews-Star-Prediction/blob/main/1_NLP%20Amazon%20Reviews%20Espan%CC%83ol.ipynb).***
