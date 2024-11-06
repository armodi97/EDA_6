
# Proyecto de Análisis de Ventas de Videojuegos

Este proyecto realiza un análisis de datos históricos sobre ventas de videojuegos. El objetivo es explorar y comprender las tendencias en el mercado de videojuegos, utilizando herramientas de manipulación de datos y análisis estadístico.

## Descripción del Proyecto

El conjunto de datos `games.csv` contiene información sobre las ventas de videojuegos a lo largo de los años. En este análisis, se aplican técnicas de estadística y visualización para identificar patrones de ventas, tendencias por género y plataforma, y otros insights importantes.

## Estructura del Análisis

1. **Introducción y Preparación de los Datos**
   - Se cargan y exploran los datos del archivo `games.csv`.
   - Se realiza una verificación de la estructura de los datos para identificar columnas, tipos de datos y valores faltantes.

2. **Análisis Exploratorio de Datos (EDA)**
   - Se examinan las principales características de los datos, como las ventas por año, género y plataforma.
   - Se crean visualizaciones interactivas con `plotly` para observar la evolución de las ventas en diferentes segmentos.

3. **Análisis Estadístico**
   - Se emplean herramientas de `scipy` y `statsmodels` para realizar pruebas estadísticas y evaluar la significancia de ciertos patrones en los datos.
   - Se utiliza el modelo de suavización exponencial de `ExponentialSmoothing` para estudiar tendencias de ventas a lo largo del tiempo.

4. **Conclusiones**
   - El análisis finaliza con un resumen de los patrones encontrados en el mercado de videojuegos, incluyendo los géneros y plataformas más populares y la evolución de las ventas en distintos períodos.

## Requisitos

- **Python 3.7+**
- Librerías: `pandas`, `numpy`, `plotly`, `statsmodels`, `scipy`

## Cómo Ejecutar el Proyecto

1. Clona el repositorio.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el notebook `Project_6.ipynb` para reproducir el análisis y las visualizaciones.
