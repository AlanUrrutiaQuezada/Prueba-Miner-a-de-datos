# Prueba-Miner-a-de-datos
Desarrollo prueba de Minería de datos Alan Urrutia Quezada

https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=covid19_jhu_csse&page=dataset&project=majestic-lead-418020&ws=!1m4!1m3!3m2!1sbigquery-public-data!2scovid19_jhu_csse
Usada debido a que es un estudio realizado por una universidad de ciencia computacional e ingeniería y ya que nuestra carrera es de ingeniería lo vi útl (se esta utilizando la tabla casos confirmados, "confirmed_cases").


A partir de la tabla confirmed_cases que se compone de diferentes paises y sus casos confirmados, se tomarán solo los casos de Chile.
La tabla contiene información innecesaria como la latitud, longitud y localización geométrica por lo que se busca eliminar estas columnas para poder ver la gráfica de casos en el tiempo.
Luego de consultarlo con el profesor, se traspuso la tabla y se eliminaron los datos innecesarios.
Se decide cambiar la tabla de datos pues esta era mas dificil de manipular y requeria de mayores capacidades.
Los nuevos datos son de "bigquery-public-data.covid19_open_data.covid19_open_data".
Con esta nueva tabla se pudo realizar todo de mejor forma hasta el momento de grafica.
Al observar la tabla se muestra un peak de casos entre enero del 2022 y mayo de 2022, el cuál fué de casi 40000 casos.
Con el peak encontrado se busca información acerca de los casos de el año 2022 y se puede observar concoradancia.
Luego de trabajar con los casos confirmados se procede a estudiar la cantidad de defunciones.

<img src=output.png>
<img src=output2.png>
<img src=https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/COVID-19-Chile-log.svg/langes-500px-COVID-19-Chile-log.svg.png>.

Al observar esta gráfica se muestra un peak cercano a las mismas fechas que para los casos nuevos, el cuál fué cercano a las 12000 defunciones. 
Luego de hacer una comparación entre las gráficas creadas y con las encontradas en internet se puede observar que los lapsos de tiempo y el comportamiento de las gráficas concuerdan pero no así sus valores.
