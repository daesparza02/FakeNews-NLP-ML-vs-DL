# Detección de Fake News con NLP y Deep Learning

Práctica 4 para la asignatura de Inteligencia Artificial II. El objetivo de este proyecto es clasificar noticias como Reales o Falsas utilizando técnicas de Procesamiento del Lenguaje Natural (PLN) y comparando modelos de Machine Learning clásico frente a Deep Learning.

**Autores:** David Esparza, Jorge Arboleya y Cristina Gómez.

## Contenido del Proyecto

El notebook incluye un flujo de trabajo completo de Data Science:

* **Preprocesamiento de Texto:**
  * Limpieza de datos (minúsculas, eliminación de puntuación).
  * Eliminación de Stopwords (NLTK).
  * Normalización y Tokenización.
* **Representación de Datos:**
  * Bolsa de Palabras (Bag of Words).
  * TF-IDF.
  * Word Embeddings (GloVe).
* **Modelos Comparados:**
  * Naive Bayes Multinomial (Ajuste de alpha).
  * Support Vector Machines (SVM) (LinearSVC).
  * k-Nearest Neighbors (kNN).
* **Redes Neuronales (Keras):**
  * Sin embeddings pre-entrenados.
  * Con embeddings congelados (GloVe).
  * Con embeddings sin congelar (Fine-tuning).

## Requisitos

Para ejecutar este cuaderno necesitas instalar las siguientes librerías:

```bash
pip install -r requirements.txt
