# Wine Quality Prediction

Este proyecto utiliza Machine Learning para predecir la calidad del vino a partir de sus características fisicoquímicas. Se ha implementado un modelo de regresión basado en Random Forest para estimar la calidad del vino en una escala del 1 al 10.

## 📌 Características del Proyecto

- Uso de **RandomForestRegressor** para modelar la calidad del vino.
- Evaluación del rendimiento del modelo en conjunto de entrenamiento y prueba.
- Generación de métricas y visualización de importancia de características y residuales.
- Implementación en Python utilizando bibliotecas como **pandas, scikit-learn, seaborn y matplotlib**.

## 📂 Estructura del Proyecto

```
📁 Wine Quality Prediction
│-- 📄 wine_quality.csv  # Dataset de calidad del vino
│-- 📄 train.py  # Código principal para entrenar y evaluar el modelo
│-- 📄 metrics.txt  # Métricas de rendimiento del modelo
│-- 📄 feature_importance.png  # Gráfico de importancia de características
│-- 📄 residuals.png  # Gráfico de residuales
│-- 📄 README.md  # Documentación del proyecto
```

## 📊 Dataset

El dataset utilizado proviene de **wine_quality.csv**, que contiene información sobre las propiedades químicas del vino y su calidad. La variable objetivo es `quality`, una puntuación numérica.

## 🔧 Instalación y Uso

1. Clona este repositorio:
   ```bash
   https://github.com/0dallas/wine.git
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el script principal:
   ```bash
   python train.py
   ```

## 📈 Resultados

El modelo genera dos gráficos clave:

- **feature_importance.png**: Muestra las características más relevantes para la predicción.
- **residuals.png**: Visualiza la relación entre los valores reales y los predichos.

Además, los resultados del modelo se guardan en `metrics.txt` con el porcentaje de varianza explicada en los conjuntos de entrenamiento y prueba.
