# Tarea-1-Topicos-D
Este repositorio contiene implementaciones prácticas de algoritmos clásicos de Machine Learning utilizando Python y Jupyter Notebooks. El enfoque principal está en la aplicación de regresión lineal para la predicción de valores continuos y regresión logística para tareas de clasificación.
## Estructura del Repositorio

El proyecto se divide en dos cuadernos principales y un directorio para el almacenamiento de datos:
### 1. Regresión Lineal Simple (notebook_regresion_lineal.ipynb)

Este notebook explora los fundamentos de la Regresión Lineal Simple.

  Caso de uso: Predicción del coste económico de un incidente de seguridad en función del número de equipos afectados.

  Metodología: Se trabaja con un dataset sintético generado aleatoriamente (con semilla fija para asegurar la reproducibilidad).

  Flujo de trabajo: Incluye la generación de los datos, la visualización de su distribución, el escalado a unidades reales (euros y equipos), el entrenamiento del modelo y la ejecución de predicciones para nuevos incidentes.

### 2. Regresión Logística y Detección de Spam (notebook_regresion_logistica.ipynb)

Este notebook implementa un modelo de Regresión Logística orientado a la clasificación de texto.

  Caso de uso: Clasificación de correos electrónicos para determinar si son SPAM o HAM (correo legítimo).

  Metodología: Utiliza el método Bag of Words (a través de CountVectorizer) para convertir el texto de los correos en vectores numéricos procesables por el algoritmo.

  Flujo de trabajo: Abarca desde la carga y exploración inicial del dataset, la limpieza de datos (eliminación de nulos y duplicados), el preprocesamiento temporal, hasta el entrenamiento del clasificador.

  Evaluación: Incluye un análisis de rendimiento mediante la precisión (accuracy), la interpretación de la matriz de confusión y un análisis gráfico sobre cómo el tamaño del dataset impacta en el aprendizaje del modelo.

### 3. Directorio de Datos (data/)

se debe crear una carpeta llamada "data" en la raíz del proyecto destinada a almacenar los conjuntos de datos necesarios para la ejecución de los notebooks.

  processed_data.csv: Dataset preprocesado basado en el corpus público TREC 2007. Este archivo contiene las características utilizadas para el filtro de spam, incluyendo etiquetas binarias (1 para SPAM, 0 para HAM), asunto, remitente, destinatario y cuerpo del mensaje. Este archivo debe descargarse en el siguiente enlance: https://www.kaggle.com/datasets/imdeepmind/preprocessed-trec-2007-public-corpus-dataset
