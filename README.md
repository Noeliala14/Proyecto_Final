
# Proyecto_Final

# Análisis y Dashboard de Calificaciones de Películas
Resumen del Proyecto
Este repositorio contiene un análisis  y un dashboard interactivo del conjunto de datos de películas y calificaciones de MovieLens. 

Requisitos 
# 1. Transformación y Limpieza de los Datos

El análisis se basó en los archivos de datos de ratings.csv y movies.csv .

Se unieron los conjuntos de datos en un solo DataFrame .

Se crearon nuevas columnas para enriquecer el análisis,puesto que se requeria 20 columnas minimo .

* Calificacion_Alta: Variable binaria (1 o 0) para identificar las calificaciones mayores a 3.5.

* Epoca y Decada: Se categorizaron las películas según su año de estreno para analizar las tendencias históricas.

Manejo de valores duplicados y nulos: Se gestionaron los valores faltantes para mantener la integridad de los datos.

# 2. Uso de Python y Pandas
Utilizó la librería Pandas para procesar un conjunto de datos grande (más de 233,000 filas) de manera eficiente.

Use la función pd.get_dummies para convertir la columna de genres en 20 columnas binarias (una para cada género). Esto tuve que hacerlo para cumplir con el requisito de tener un número específico de columnas y para permitir un análisis detallado por género.

# 3. Análisis Descriptivo y Estadístico

Se calculó y visualizó la distribución de las calificaciones, revelando un fuerte sesgo positivo de los usuarios, con la mayoría de los votos concentrándose en las calificaciones más altas.

Análisis de géneros: Se identificaron los géneros más populares en términos de número de votos.

Matriz de correlación: Se realizó un análisis de correlación para explorar la relación entre variables como la duración de la película, el año de estreno y la calificación.

# 4. Dashboard y Herramienta de Visualización
Herramienta: El dashboard se creó en Microsoft Power BI. Se optó por esta herramienta debido a sus capacidades para manejar grandes volúmenes de datos sin los problemas de rendimiento de Excel

Se incluyeron tarjetas de resumen en la parte superior del dashboard que muestran:

Total de películas: 233,213 mil.

Total de votos: 9 millones.

Usuarios únicos: 610.
  # Visualizaciones principales:

Distribución de Votos por Calificación: Un gráfico de barras que muestra la frecuencia de cada calificación, revelando un sesgo positivo en los datos.

Top 5 Películas: Un gráfico de barras que lista las 5 películas con la mayor cantidad de votos, destacando la popularidad de  Pulp Fiction y Fight Club.

Hashtags más Populares: Un cuadro de palabras para mostrar de forma intuitiva las etiquetas más usadas por los usuarios, como "sci-fi" y "suspense".
