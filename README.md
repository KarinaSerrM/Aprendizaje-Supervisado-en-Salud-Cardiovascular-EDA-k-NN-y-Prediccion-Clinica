# Aprendizaje Supervisado en Salud Cardiovascular: EDA, k-NN y Predicción Clínica

Este repositorio documenta el desarrollo de un modelo predictivo para evaluar el riesgo de ataque cardíaco, combinando análisis exploratorio automatizado con algoritmos supervisados en Python.

## Objetivo del proyecto

Analizar datos clínicos para entrenar un modelo de clasificación que permita predecir la probabilidad de un ataque cardíaco en función de factores como edad, presión arterial, colesterol y resultados de pruebas médicas.

## Flujo de trabajo

### 1. Exploración de datos (EDA)
- Carga del dataset `Heart Attack.csv`
- Descripción detallada de cada variable clínica
- Generación automática de un informe EDA con `ydata-profiling`
- Visualización estructurada para comprender patrones y relaciones

### 2. Preprocesamiento
- Codificación de variables categóricas con `LabelEncoder`
- Separación entre variables independientes (`X`) y variable objetivo (`y`)
- Verificación del formato para modelos supervisados

### 3. Modelado k-NN
- Entrenamiento del clasificador k-NN con `n_neighbors=6`
- Simulación de una nueva observación para realizar predicción
- Evaluación del resultado del modelo

## Herramientas utilizadas

- Python 3.11  
- Pandas  
- NumPy  
- Scikit-learn  
- ydata-profiling  
- Matplotlib / Seaborn  

## Conclusiones

- El enfoque k-NN permite realizar predicciones clínicas de forma rápida y efectiva.
- La combinación de EDA automatizado y preprocesamiento mejora la comprensión de los datos.
- Las decisiones clínicas pueden ser reforzadas con modelos supervisados entrenados sobre datos confiables.
