
# Clasificador de Spam en SMS

Este proyecto implementa un modelo de clasificación de mensajes SMS para distinguir entre ham (mensaje normal) y spam (mensaje publicitario o fraudulento).
Fue desarrollado en Python como práctica de NLP básico y Machine Learning supervisado.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![scikit-learn](https://img.shields.io/badge/ScikitLearn-ML-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📑 Contenido
- Introducción
- Dataset
- Tecnologías utilizadas
- Flujo del proyecto
- Resultados

## 🧠 Introducción

Este proyecto permite entrenar un modelo capaz de identificar mensajes SMS fraudulentos o publicitarios.  
Es ideal para estudiantes que buscan practicar:
- Limpieza básica de texto
- Vectorización con TF-IDF
- Entrenamiento con Naive Bayes
- Evaluación de resultados
- Uso de modelos guardados (.joblib)

## 📂 Dataset

Se utiliza el dataset **SMS Spam Collection**, disponible en UCI/Kaggle.  
Incluye más de **5500 mensajes** etiquetados como:

- **ham** → mensaje normal  
- **spam** → mensaje fraudulento/publicitario  

Archivo utilizado:

https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download

## 🛠 Tecnologías utilizadas

- Python
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Joblib  
- Jupyter Notebook  

## 🔍 Flujo del proyecto

### 1️⃣ Exploración (EDA)
- Distribución ham/spam  
- Análisis de longitud  
- Visualizaciones

### 2️⃣ Preprocesamiento de texto
- Minúsculas  
- Eliminación de URLs, números y signos  
- Limpieza básica

### 3️⃣ Modelo
- TF-IDF (ngram_range = 1,2)
- Multinomial Naive Bayes

### 4️⃣ Evaluación
- Accuracy ~ **97%**
- Precision / Recall / F1-score
- Matriz de confusión
- Ejemplos de predicciones

## 📊 Resultados principales

- Accuracy: **~97%**
- Muy buen rendimiento en clase *ham*
- Buen desempeño general en clase *spam*
- Modelo liviano y rápido

Ejemplo de predicción:

> WIN a FREE prize now!!!
Predicción: spam

> Hola, llegás en 10 min?
Predicción: ham

