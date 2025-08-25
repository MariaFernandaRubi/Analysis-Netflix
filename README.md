# Analysis-Netflix
Limpieza, transformación, análisis de datos y visualización de Contenido de Netflix con Python

## 📖 Objetivo
El objetivo de este proyecto es **limpiar, transformar y visualizar datos de películas y series de Netflix**, con el fin de explorar y comparar información relevante como directores, reparto y duración de los títulos.  
No se realizaron cálculos predictivos ni modelos estadísticos, sino un **análisis exploratorio y comparativo** a partir de la calidad del dataset.

## 🛠️ Herramientas y Tecnologías
- **Python (Jupyter Notebook):** Para realizar la limpieza y el análisis.  
- **pandas:** Para manipulación y transformación de datos.  
- **matplotlib:** Para gráficos básicos.  
- **seaborn:** Para visualizaciones estadísticas y comparativas.
- **Power Query:** Data cleaning (removing nulls, filtering erroneous rows, ensuring consistency).
- **Power BI:** Visualization and analysis of the cleaned dataset.

## 📊 Dataset
- **Fuente:** netflix_titles.csv 
- **Estructura:** Contiene información sobre:
- ID del programa
- Tipo
- Título
- Director
- Reparto
- País
- Fecha de publicación
- Año de estreno
- Clasificación
- Duración
- Publicado en
- Descripción

## 🔎 Proceso
1. **Limpieza de Datos**  
   - Reemplazo de valores nulos en diferentes columnas (ej. director, reparto).  
   - Búsqueda de coincidencias en otras columnas para completar valores faltantes.  
   - Eliminación de columnas no necesarias para el análisis.  

2. **Transformación de Datos**  
   - Estandarización de formatos (ej. duración, tipo de contenido).  
   - Creación de subconjuntos para análisis comparativo entre películas y series.  

3. **Visualización**  
   - Gráficas comparativas entre películas y series.  
   - Distribución de la duración de películas.  
   - Análisis de directores y reparto más frecuentes.  

## 📈 Resultados
- Categorías más comunes en películas y series por tipo
- Tendencias anuales de estrenos de películas y series
- Los 10 mejores directores de Netflix
- Los 10 mejores actores de Netflix
- Duración de las películas
- Los 10 principales países con contenido de Netflix

## 📂 Estructura del repositorio
- Conjunto de datos sin procesar -> netflix_titles.csv
- Conjunto de datos depurados -> clean_netflix.csv
- Jupyter Notebook con código Python -> Netflix_DataAnalysis.ipynb
- Panel de Power BI -> Netflix_Dashboard.pbix / Netflix_Dashboard PDF.pdf
- Presentación de información de datos -> Pt Analysis Netflix.pdf
