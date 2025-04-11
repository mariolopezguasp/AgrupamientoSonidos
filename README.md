# 🔊 Agrupamiento de sonidos con Machine Learning

Este proyecto realiza un análisis no supervisado para agrupar distintos sonidos `.wav` según sus características acústicas. Utiliza transformaciones de señal, reducción de dimensionalidad y técnicas de clustering para categorizar sonidos sin etiquetas previas.

## 🎯 Objetivo

Agrupar sonidos en clusters representativos a partir de sus propiedades frecuenciales y temporales. El enfoque es útil en tareas como segmentación de audio, clasificación no supervisada o análisis exploratorio de señales sonoras.

## 🧠 Técnicas utilizadas

- **Transformada de Fourier (FFT)** para extraer características frecuenciales de cada sonido.
- **Normalización y estandarización** de los datos.
- **PCA (Análisis de Componentes Principales)** para reducir la dimensionalidad y facilitar la visualización.
- **K-Means** para realizar el agrupamiento.
- Visualización en 2D de los clusters resultantes.

## 📈 Resultados
El modelo logra separar sonidos de distinta naturaleza en clusters diferenciados. Gracias al uso de FFT y PCA, se puede visualizar y analizar la distribución de los sonidos en un espacio reducido, lo que facilita la interpretación de los patrones acústicos.
