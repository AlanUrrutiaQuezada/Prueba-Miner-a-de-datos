# Prueba-Miner-a-de-datos
Desarrollo prueba de Minería de datos Alan Urrutia Quezada

https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=covid19_jhu_csse&page=dataset&project=majestic-lead-418020&ws=!1m4!1m3!3m2!1sbigquery-public-data!2scovid19_jhu_csse
Usada debido a que es un estudio realizado por una universidad de ciencia computacional e ingeniería y ya que nuestra carrera es de ingeniería lo vi útl (se esta utilizando la tabla casos confirmados, "confirmed_cases").

https://ukhsa-dashboard.data.gov.uk
Para el caso de la API ya que el anterior era un estudio americano opte por ver una comparación en otro continente.

A partir de la tabla confirmed_cases que se compone de diferentes paises y sus casos confirmados, se tomarán solo los casos de Chile.
La tabla contiene información innecesaria como la latitud, longitud y localización geométrica por lo que se busca eliminar estas columnas para poder ver la gráfica de casos en el tiempo.
Luego de consultarlo con el profesor, se traspuso la tabla y se eliminaron los datos innecesarios.
Se decidio cambiar la tabla de datos pues esta era mas dificil de manipular y requeria de mayores capacidades.
Los nbuevos datos son de "bigquery-public-data.covid19_open_data.covid19_open_data"
Con esta nueva tabla se pudo realizar todo de mejor forma hasta el momento de grafica
