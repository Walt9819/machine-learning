# Machine learning
Recursos para la enseñanza y aprendizaje de machine learning en Python

# Índice
- [Códigos](#codes)
- [Datasets](#datasets)
  - Students Performance in Exams
  - Heart Failure Prediction - Clinical Records
  - Data Developer Salary in 2024
  - Breast Cancer Wisconsin Diagnostic Dataset

## Códigos {#codes}
- Introducción
  - Introducción a Machine Learning
  - Pre-procesamiento

- Aprendizaje supervisado
  - Regresión lineal
  - Regresión logística
  - K-vecinos más cercanos
  - Árboles de decisión
  - Máquina de soporte de vectores (Support Vector Machine)
  - Métodos de ensamble

- Aprendizaje no supervisado
  - K-medias
  - Jerarquías
  - Reducción de dimensionalidad (Principal Component Analysis)

## Datasets {#datasets}
El repositorio hace uso de cuatro conjuntos de datos abiertos:

### Rendimiento de alumnos en exámenes (Students Performance in Exams). Tomado de [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).
#### Descripción
Este conjunto de datos consiste en las calificaciones obtenidas por los estudiantes en varias asignaturas.

#### Valores
- Género
- Raza/etnicidad/grupo
- Nivel de estudios de los padres
- Lunch
- Preparación para el examen
- Calificación matemáticas
- Calificación lectura
- Calificación escritura

### Predicción de insuficiencia cardiaca (Heart Failure Prediction - Clinical Records). Tomado de [Kaggle](https://www.kaggle.com/datasets/aadarshvelu/heart-failure-prediction-clinical-records).
#### Descripción
Este conjunto de datos contiene los registros médicos de 5000 pacientes que sufrieron insuficiencia cardíaca, recopilados durante su período de seguimiento, donde cada perfil de paciente tiene 13 características clínicas.

#### Valores
-edad: edad del paciente (años)
- anemia: disminución de glóbulos rojos o hemoglobina (booleano)
- creatinina fosfocinasa (CPK): nivel de la enzima CPK en la sangre (mcg/L)
- diabetes: si el paciente tiene diabetes (booleano)
- fracción de eyección: porcentaje de sangre que sale del corazón en cada - contracción (porcentaje)
- hipertensión: si el paciente tiene hipertensión (booleano)
- plaquetas: plaquetas en la sangre (kiloplaquetas/mL)
- sexo: mujer u hombre (binario)
- creatinina sérica: nivel de creatinina sérica en la sangre (mg/dL)
- sodio sérico: nivel de sodio sérico en la sangre (mEq/L)
- fumador: si el paciente fuma o no (booleano)
- tiempo: período de seguimiento (días)
- evento de muerte: si el paciente murió durante el período de seguimiento (booleano)

### Salario de *Data Developer* en 2024 (Data Developer Salary in 2024). Tomado de [Kaggle](https://www.kaggle.com/datasets/zeesolver/data-eng-salary-2024).
#### Descripción
El conjunto de datos de 2024 sobre salarios y empleo de desarrolladores de datos proporciona información clave sobre salarios, títulos, experiencia, tipos de empleo, residencias, trabajo remoto, ubicaciones y tamaños de empresas, permitiendo analizar tendencias salariales y patrones de empleo en el sector.

#### Valores
- nivel_de_experiencia: Nivel de experiencia profesional (por ejemplo, junior, medio, senior).
- tipo_de_empleo: Tipo de contrato de trabajo (por ejemplo, tiempo completo, tiempo parcial, contrato).
- título_del_trabajo: El rol o título específico del empleado (por ejemplo, Ingeniero de Datos).
- salario: La compensación recibida, en la moneda original.
- moneda_del_salario: La moneda en la que se paga el salario.
- salario_en_usd: El salario convertido a dólares estadounidenses para comparación.
- residencia_del_empleado: El lugar donde reside el empleado.
- proporción_de_trabajo_remoto: Porcentaje de trabajo realizado de forma remota.
- ubicación_de_la_empresa: La ubicación geográfica de la empresa.
- tamaño_de_la_empresa: La escala de la empresa, a menudo basada en el número de empleados.


### Diagnóstico de cáncer de mama de Winsconsin (Breast Cancer Wisconsin Diagnostic Dataset). Tomado de [Kaggle](https://www.kaggle.com/datasets/utkarshx27/breast-cancer-wisconsin-diagnostic-dataset)
#### Descripción
Características de biopsias para la clasificación de 569 masas mamarias malignas (cáncer) y benignas (no cáncer).

#### Valores
- x.radius_mean: Promedio del radio de las células tumorales.
- x.texture_mean: Promedio de la textura de las células tumorales.
- x.perimeter_mean: Promedio del perímetro de las células tumorales.
- x.area_mean: Promedio del área de las células tumorales.
- x.smoothness_mean: Promedio de la suavidad de las células tumorales.
- x.compactness_mean: Promedio de la compacidad de las células tumorales.
- x.concavity_mean: Promedio de la concavidad de las células tumorales.
- x.concave_points_mean: Promedio del número de porciones cóncavas del contorno de las células tumorales.
- x.symmetry_mean: Promedio de la simetría de las células tumorales.
- x.fractal_dimension_mean: Promedio de la "aproximación de línea costera" de las células tumorales.
- x.radius_se: Error estándar del radio de las células tumorales.
- x.texture_se: Error estándar de la textura de las células tumorales.
- x.perimeter_se: Error estándar del perímetro de las células tumorales.
- x.area_se: Error estándar del área de las células tumorales.
- x.smoothness_se: Error estándar de la suavidad de las células tumorales.
- x.compactness_se: Error estándar de la compacidad de las células tumorales.
- x.concavity_se: Error estándar de la concavidad de las células tumorales.
- x.concave_points_se: Error estándar del número de porciones cóncavas del contorno de las células tumorales.
- x.symmetry_se: Error estándar de la simetría de las células tumorales.
- x.fractal_dimension_se: Error estándar de la "aproximación de línea costera" de las células tumorales.
- x.radius_worst: Peor (mayor) radio de las células tumorales.
- x.texture_worst: Peor (más severa) textura de las células tumorales.
- x.perimeter_worst: Peor (mayor) perímetro de las células tumorales.
- x.area_worst: Peor (mayor) área de las células tumorales.
- x.smoothness_worst: Peor (más severa) suavidad de las células tumorales.
- x.compactness_worst: Peor (más severa) compacidad de las células tumorales.
- x.concavity_worst: Peor (más severa) concavidad de las células tumorales.
- x.concave_points_worst: Peor (más severo) número de porciones cóncavas del contorno de las células tumorales.
- x.symmetry_worst: Peor (más severa) simetría de las células tumorales.
- x.fractal_dimension_worst: Peor (más severa) "aproximación de línea costera" de las células tumorales.
- y.target: Clasificación del tumor (maligno o benigno).

### Canciones más escuchadas en Spotify en 2024 (Most Streamed Spotify Songs 2024). Tomado de [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024).
#### Descripción
Este conjunto de datos presenta una compilación exhaustiva de las canciones más reproducidas en Spotify en 2024.

#### Valores
- Nombre de la canción: Nombre de la canción.
- Nombre del álbum: Nombre del álbum al que pertenece la canción.
- Artista: Nombre del artista(s) de la canción.
- Fecha de lanzamiento: Fecha en que se lanzó la canción.
- ISRC: Código Internacional de Grabación Estándar de la canción.
- Ranking histórico: Clasificación de la canción basada en su popularidad histórica.
- Puntuación de la canción: Puntuación asignada a la canción basada en varios factores.
- Reproducciones en Spotify: Número total de reproducciones en Spotify.
- Número de listas de reproducción de Spotify: Número de listas de reproducción de Spotify que incluyen la canción.
- Alcance en listas de reproducción de Spotify: Alcance de la canción en listas de reproducción de Spotify.
- Popularidad en Spotify: Puntuación de popularidad de la canción en Spotify.
- Visualizaciones en YouTube: Total de visualizaciones del video oficial de la canción en YouTube.
- Me gusta en YouTube: Total de "me gusta" en el video oficial de la canción en YouTube.
- Publicaciones en TikTok: Número de publicaciones en TikTok que presentan la canción.
- Me gusta en TikTok: Total de "me gusta" en publicaciones de TikTok que presentan la canción.
- Visualizaciones en TikTok: Total de visualizaciones en publicaciones de TikTok que presentan la canción.
- Alcance en listas de reproducción de YouTube: Alcance de la canción en listas de reproducción de YouTube.
- Número de listas de reproducción de Apple Music: Número de listas de reproducción de Apple Music que incluyen la canción.
- Reproducciones en radio: Número de veces que la canción ha sido reproducida en estaciones de radio.
- Reproducciones en SiriusXM: Número de veces que la canción ha sido reproducida en SiriusXM.
- Número de listas de reproducción de Deezer: Número de listas de reproducción de Deezer que incluyen la canción.
- Alcance en listas de reproducción de Deezer: Alcance de la canción en listas de reproducción de Deezer.
- Número de listas de reproducción de Amazon: Número de listas de reproducción de Amazon Music que incluyen la canción.
- Reproducciones en Pandora: Número total de reproducciones en Pandora.
- Estaciones de la canción en Pandora: Número de estaciones de Pandora que presentan la canción.
- Reproducciones en Soundcloud: Número total de reproducciones en Soundcloud.
- Conteos en Shazam: Número total de veces que la canción ha sido buscada en Shazam.
- Popularidad en TIDAL: Puntuación de popularidad de la canción en TIDAL.
- Canción explícita: Indica si la canción contiene contenido explícito.
