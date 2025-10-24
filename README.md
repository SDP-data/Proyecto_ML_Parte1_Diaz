# Proyecto_ML_Parte1_Diaz
Análisis exploratorio e insights con Machine Learning - Primera entrega del curso Data Science II (Coderhouse)

# Análisis y modelado de tiempos en competencias Hyrox

## Descripción
Este proyecto analiza datos de competencias Hyrox, calculando métricas derivadas por estación, generando clusters de rendimiento y entrenando modelos de Machine Learning (Random Forest) para predecir el tiempo total de los atletas.  
El objetivo es obtener insights accionables sobre desempeño y fatiga de los participantes.

## Estructura de archivos
- `Proyecto_ML_Parte1_Díaz.ipynb` : Notebook con análisis exploratorio, limpieza de datos, creación de features, clustering y modelado.
- `Hyrox_procesado_SDP.csv` : Dataset original (procesado).
- `hyrox_enriquecido_opt.csv` : Dataset procesado y enriquecido listo para modelado.
- `Presentación PDF - DSII primera parte SDP.pdf`: Presentación con breve descripción del trabajo.
- `README.md` : Este archivo.

## Requisitos
Para ejecutar el notebook se necesitan las siguientes librerías de Python:
pandas
numpy
scikit-learn
plotly

## Cómo ejecutar
1. Abrir `Proyecto_ML_Parte1_Díaz.ipynb` en [Google Colab](https://colab.research.google.com/).
2. Subir el archivo `Hyrox_procesado_SDP.csv`.
3. Ejecutar todas las celdas en orden.

## Resultados principales
- El modelo enriquecido (features derivadas + cluster) reduce el MAE y mejora el R² respecto al modelo base.
- Clusters obtienen patrones de rendimiento, y features derivadas como `fatigue_slope` y `pct_last_3_stations` son útiles para la predicción.
- Las métricas indican que la inclusión de features adicionales y limpieza reduce errores y hace el modelo más estable y generalizable.

## Autor
Sebastián Díaz
