# Repositorio: Análisis de Calidad de Datos con PySpark y PyDeequ

## Descripción
Este repositorio contiene un caso de uso práctico implementado en un Jupyter Notebook que demuestra cómo evaluar y garantizar la calidad de datos utilizando PySpark y PyDeequ. El ejemplo trabaja con un archivo CSV como fuente de datos, aplicando diversas métricas y verificaciones para asegurar la integridad, completitud y consistencia de los datos.

## Características principales
- **Evaluación automatizada de calidad de datos** utilizando el framework PyDeequ (inspirado en Deequ de AWS)
- **Procesamiento distribuido** con PySpark para manejar conjuntos de datos grandes
- **Análisis completo** que incluye:
  - Perfilado de datos (Data Profiling)
  - Verificación de constraints (restricciones de calidad)
  - Métricas computadas (completitud, unicidad, etc.)
  - Análisis de anomalías
- **Visualización clara** de resultados y métricas
- **Ejemplo reproducible** con un dataset de muestra en formato CSV

## Tecnologías utilizadas
- Python 3.x
- PySpark (para procesamiento distribuido)
- PyDeequ (para métricas de calidad de datos)
- Jupyter Notebook (para documentación interactiva)


## Caso de uso
El notebook implementa un flujo completo de trabajo:
1. Carga de datos desde archivo CSV
2. Análisis exploratorio inicial
3. Definición de métricas de calidad
4. Ejecución de verificaciones
5. Interpretación de resultados
6. Generación de reportes

Ideal para ingenieros de datos, científicos de datos y analistas que necesitan implementar controles de calidad de datos en sus pipelines.
