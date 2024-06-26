#Informe Solemne 1

En este proyecto el objetivo principal es el ánalisis de datos sobre el covid-19. Como primer objetivo lo que se hace para este análisis, es utilizar un conjunto de datos público relacionado con COVID-19 disponible en BigQuery. Se identificó un conjunto de datos que contiene información detallada sobre los casos de COVID-19, incluyendo la fecha, el país, el número de casos confirmados, recuperados y fallecidos.

Aunque se tenía acceso a datos adicionales a través de API públicas relacionadas con la vacunación contra COVID-19, estos datos no fueron utilizados en el análisis debido a la simplicidad y suficiencia de los datos disponibles en BigQuery para los propósitos de este informe, ya que tuvimos problemas con el trabajo de columnas con los datos que nos entregaban las API´s

Además con los datos extraídos se realizaron consultas SQL en BigQuery para explorar las características del conjunto de datos seleccionado, como la evolución temporal de los casos, la distribución geográfica de los casos, entre otros.

Luego se hizo limpieza y transformación de datos. Los datos obtenidos de BigQuery se cargaron en DataFrames de Pandas para facilitar su manipulación y análisis. Se realizaron tareas de limpieza básicas, como la eliminación de valores nulos o duplicados, para asegurar la integridad de los datos.

Luego de tener los datos ya ordenados y limpios, se procede a la visualización de dichos datos, siendo asi que se crearon diversas visualizaciones utilizando Matplotlib para proporcionar una representación gráfica de los datos. Las visualizaciones incluyeron gráficos de líneas para mostrar la evolución temporal de los casos, gráficos de barras para comparar la distribución geográfica de los casos, entre otros.

Finalizando con el ánalisis final y la interpretación que se le da a los gráficos realizados. Se llevó a cabo un análisis exhaustivo de los datos, resaltando los hallazgos más relevantes observados en el conjunto de datos de COVID-19. Se identificaron patrones temporales en la evolución de casos, así como variaciones geográficas en la incidencia de casos.

A pesar de la simplicidad de los datos utilizados, se pudo obtener información valiosa sobre la propagación del virus y su impacto en diferentes regiones, tales como la cantidad de muertes que hubo en un interválo de tiempo en especifico en una país en especifico en este caso Canada, y como en la s3egunda consulta la cantidad de casos confirmados también en un intervalo de tiempo en Nueva Zelanda.
Finalmente se hace la entrega del informe a través de github creando un repositorio en colaboración, además se realizaron commits regulares con mensajes descriptivos a medida que avanzaba el proyecto.