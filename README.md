# Práctica Álgebra IA4

Este repositorio contiene el notebook **ALG-PRACTICA_MEugeniaAlvarez.ipynb**, correspondiente a una práctica del Módulo de Matemáticas 101. El objetivo es aplicar conceptos de regresión lineal utilizando tanto el método de mínimos cuadrados como descenso por gradiente, sobre el dataset Auto MPG.

## Contenido

- **Exploración de datos:**  
  Análisis exploratorio del dataset Auto MPG descargado desde la UC Irvine Machine Learning Repository.

- **Visualización:**  
  Diagramas de dispersión entre el consumo de combustible (mpg) y distintas variables como peso, aceleración y caballos de fuerza.

- **Regresión lineal con mínimos cuadrados:**  
  Implementación propia (usando numpy) de la solución analítica de regresión lineal, aplicada a la predicción de consumo (mpg) en función del peso del vehículo.

- **Comparación con scikit-learn:**  
  Comparación entre la regresión lineal implementada y la de la librería scikit-learn.

- **Descenso del gradiente:**  
  Implementación y aplicación del descenso del gradiente para optimizar los coeficientes de la regresión lineal y comparación de resultados.

## Requisitos

- Python 3.8 o superior
- numpy
- pandas
- matplotlib
- ucimlrepo
- scikit-learn

Instala las dependencias ejecutando:

```bash
pip install numpy pandas matplotlib ucimlrepo scikit-learn
