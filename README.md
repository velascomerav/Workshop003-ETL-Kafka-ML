
# Workshop 003 – ETL Pipeline using Apache Kafka + Machine Learning

## Descripción del proyecto

Desarrollo de un pipeline ETL utilizando Apache Kafka para consumir, transformar e integrar datos de cinco archivos correspondientes al World Happiness Report entre 2015 y 2019.

El proyecto incluye análisis exploratorio de datos (EDA), preparación de variables, entrenamiento de modelos de Machine Learning, evaluación de resultados y almacenamiento en SQLite.

## Tecnologías utilizadas

- Python 3.11
- Apache Kafka
- Confluent Kafka
- Pandas y NumPy
- Matplotlib y Seaborn
- Scikit-learn
- SQLite
- Visual Studio Code
- Jupyter Notebook

## Resultados

Se procesaron 782 registros y se entrenaron dos modelos predictivos.

| Modelo | MAE | MSE | RMSE | R² |
|---|---:|---:|---:|---:|
| Regresión lineal | 0.4699 | 0.3521 | 0.5934 | 0.7193 |
| Random Forest | 0.3998 | 0.2811 | 0.5302 | 0.7759 |

Random Forest obtuvo el mejor rendimiento en el conjunto de prueba.

## Archivos del proyecto

- `Workshop003.ipynb`: implementación del pipeline y análisis.
- `workshop003.db`: base de datos SQLite.
- `Documento workshop 003.pdf`: documentación técnica y evidencias de ejecución.

## Autores

Valentina Velasco Mera  
Daniel Felipe Romero Bernal

## Curso

Ingeniería de Datos e Inteligencia Artificial  
ETL (G01) – 2026
