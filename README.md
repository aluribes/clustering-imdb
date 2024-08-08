# Clustering no supervisado
## Algoritmo K-Means
### Top 1000 películas según el IMDb

El objetivo de este proyecto es desarrollar un programa en Python que determine los clústeres en los datos de las 1000 películas más populares de la historia según IMDb. Utilizando técnicas de clustering no supervisado, específicamente el algoritmo K-means, el programa identificará grupos de películas que comparten características similares.

### Datos
La base de datos utilizada contiene información detallada sobre las 1000 películas más populares según IMDb. Las variables incluidas en el análisis son:

- **year:** Año de lanzamiento de la película.
- **runtime:** Duración de la película en minutos.
- **rating:** Calificación promedio de la película en IMDb.
- **metascore:** Puntaje en Metacritic.
- **votes:** Número de votos recibidos por la película en IMDb.
- **gross_in_millions:** Ingresos brutos generados por la película en millones de dólares.
- **genre_*:** Variables binarias indicando los géneros a los que pertenece cada película.

### Metodología
#### Preprocesamiento de Datos

Carga del archivo CSV y limpieza de los datos.

Normalización de las variables seleccionadas para el clustering.

#### Selección de Variables

Análisis exploratorio de datos para identificar las tres variables que mejor segmentan los datos. En este caso, se seleccionaron las variables year, runtime y rating.

#### Aplicación del Algoritmo K-means

Implementación del algoritmo K-means para realizar el clustering no supervisado.

Determinación del número óptimo de clústeres utilizando el método del codo y el análisis de la silueta.

#### Visualización y Análisis

Visualización de los clústeres identificados.

Análisis descriptivo de cada clúster para interpretar las características de las películas agrupadas.
