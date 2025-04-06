# 🧠 Análisis de Sentimientos con Deep Learning en Reseñas de IMDb 🎬

Este proyecto aplica técnicas de Procesamiento de Lenguaje Natural (NLP) y Deep Learning para realizar un análisis de sentimientos sobre un conjunto de 50.000 reseñas de películas del sitio IMDb, clasificadas como positivas o negativas.

# 📌 Objetivos

Preprocesar texto para prepararlo para su uso en redes neuronales.

Visualizar patrones de lenguaje a través de nubes de palabras.

Implementar y entrenar modelos de Deep Learning (red neuronal simple y LSTM) para clasificación binaria de sentimientos.

# 🛠️ Tecnologías utilizadas

-Python (Google Colab)

-TensorFlow / Keras

-Matplotlib / WordCloud

-Dataset IMDb vía tensorflow.keras.datasets

# ⚙️ Fases del proyecto

Preprocesamiento del texto

Tokenización, padding, análisis exploratorio y visualización de palabras más frecuentes por sentimiento.

## Modelo básico

Red neuronal simple con capa de embedding y capa densa.

## Modelo avanzado

Red LSTM con embedding más profundo, regularización con Dropout y visualización de métricas de entrenamiento.

# 📊 Resultados

Se alcanzó una precisión de ~87% en el conjunto de prueba.

La red LSTM capturó mejor las relaciones contextuales en el texto, superando al modelo básico.

# 🔍 Conclusiones

Este proyecto demuestra cómo técnicas de NLP combinadas con redes neuronales pueden generar modelos efectivos para tareas de análisis de sentimientos, especialmente en conjuntos de datos grandes y complejos como IMDb.

