# Análisis y Modelado del Dataset Titanic

Este proyecto utiliza el dataset Titanic para predecir la supervivencia de los pasajeros aplicando técnicas de análisis de datos y machine learning. Incluye pasos detallados desde la exploración inicial hasta la evaluación del modelo.

## Descripción del Proyecto

El objetivo principal es predecir la variable `Survived` (0: No sobrevivió, 1: Sobrevivió) utilizando características como la clase del ticket, el género, la edad, y el puerto de embarque. El modelo entrenado es una **Regresión Logística** evaluada con métricas como precisión, recall y F1-score.

## Características del Proyecto

1. **Análisis Exploratorio**:
   - Visualizaciones de la distribución de variables.
   - Identificación de valores faltantes y tendencias.

2. **Preprocesamiento**:
   - Limpieza de datos (valores faltantes y columnas irrelevantes).
   - Codificación de variables categóricas.
   - División en conjuntos de entrenamiento y prueba.

3. **Modelado**:
   - Entrenamiento del modelo con **Regresión Logística**.
   - Evaluación con métricas detalladas.

4. **Visualización**:
   - Gráficos de distribución y una matriz de confusión.

## Tecnologías Utilizadas

- **Python**
- **Bibliotecas**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Estructura del Proyecto

- `Titanic-Dataset.csv`: Dataset utilizado.
- `titanic_analysis.ipynb`: Notebook con el análisis y el modelo.
- `README.md`: Descripción del proyecto.

## Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/titanic-analysis.git
   cd titanic-analysis
