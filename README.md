# Predicción de Gravedad de Accidentes de Tráfico en Maryland, EE.UU.

Este proyecto se enfoca en predecir la gravedad de los accidentes de tráfico en el condado de Montgomery, Maryland, utilizando datos disponibles en data.gov.

## Descripción del Proyecto

- **Origen de los Datos:** Los datos fueron obtenidos de data.gov y corresponden a los accidentes de tráfico registrados en el condado de Montgomery, Maryland.
  
- **Procesamiento de Datos:**
  - Se realizó una limpieza de datos que incluyó la integración de datos, eliminación de variables irrelevantes y redundantes, manejo de valores nulos y atípicos.
  - Se llevó a cabo un análisis exploratorio de datos (EDA) para comprender mejor las características del conjunto de datos.
  - Se exploraron las correlaciones entre las variables para identificar patrones significativos.

## Entrenamiento y Evaluación de Modelos

- **División de Datos:**
  - Los datos se dividieron en un conjunto de entrenamiento (70%) y un conjunto de prueba (30%).
  - Se aplicó un balanceo de datos en el conjunto de entrenamiento (70%) para mejorar el rendimiento de los modelos.

- **Modelos Utilizados:**
  - Se entrenaron siete modelos diferentes: Árbol de Clasificación, KNN, Red Neuronal, Máquina de Soporte Vectorial (SVM), Random Forest, XGBoost y Votación Suave.
  
- **Evaluación de Modelos:**
  - Los modelos se evaluaron utilizando técnicas de validación cruzada para garantizar la generalización y se compararon en el conjunto de prueba no balanceado.
  - Se realizó un análisis estadístico para determinar el modelo con el mejor rendimiento.

- **Optimización de Hiperparámetros:**
  - Se utilizó GridSearch para la optimización de hiperparámetros en el modelo seleccionado.

## Despliegue

- El despliegue del proyecto se realizó utilizando Streamlit, proporcionando una interfaz interactiva para visualizar y utilizar el modelo entrenado.

## Problemas Conocidos

- **Errores en el Notebook:** Debido a un error, la sección de código posterior a la matriz de correlaciones en el notebook de limpieza de datos no pudo ser incluida en el commit. Esta sección incluía un análisis detallado de las correlaciones y el código para guardar los datos limpios en un archivo CSV.

- **Gráficas de Análisis Exploratorio:** Las gráficas generadas durante el análisis exploratorio están disponibles en el archivo HTML adjunto en el repositorio.
