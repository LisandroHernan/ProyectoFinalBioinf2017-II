# Lisandro Hernandez Anaya #

En el presente repositorio se incluyen datos, scripts utilizados para analizar datos de secuencias Sanger obtenidas de las algas pardas *Padina* y *Dictyota*, 

En el repositorio se incluyen los siguientes directorios

**data**

Se encuentran subdirectorios llamados:

datain: En este se encuentran las matrices de datos para los marcadores COI--MatCOI y psbA--MatpsbA por separado que incluye tanto datos obtenidos en el proyecto de investigación como en los trabajos realizados por Díaz-Martínez (2016) y Lozano (2016). Las cuales son secuencias ensambladas y listas para ser alineadas.

dataout: El subdirectorio incluye matrices con las secuencias alineadas, se incluye las matrices de distancia obtenida para los análisis posteriores.
		 

**meta**

En este directorio se encuentra una tabla en la cual se encuentran las localidades de recolecta, condiciones ambientales, etc, que será para graficar un mapa en el cual se indiquen el sitio de recolecta para cada especie.

**bin**


Los scripts que se han utilizado y que se utilizaran para obtener todos los resultados se encuentran aquí

Blast (aun no consigo correrlo), este script contiene como instalar el software en un contenedor de Docker y correrlo con las secuencias en formato fasta, secuencias obtenidas en el proyecto de investigación
Seq, contiene como descargar las secuencias de trabajos publicados como el de Díaz-Martínez (2016) y pegarlas a un archivo que ya se tiene con las secuencias del estudio.
Align este script presenta como alinear las matriz de secuencias del presente estudio junto con las secuencias de Díaz-Martínez

NeiJoi en este script se describirá como se debe realizar el análisis de Neighbor-Joining (NJ) para muestras con secuencias Sanger

MapRec, sirve para realizar un mapa el cual presentara los sitios de recolecta por especie.


**figures**
Se guardará el gráfico obtenido del análisis de Neighbor joining 
Aquí se encontrará el mapa obtenido para ubicar los puntos de recolecta de las muestras bajo estudio

**archive**

En este directorio se encuentran incluidas las matrices en formato fasta de cada región psbA y COI, y conjuntadas, las cuales solo incluyen las secuencias
de los datos obtenidos en el presente proyecto de investigación.También se encuentran un archivo en formato fasta de la las secuencias del género *Padina* obtenidas del Genbank generadas en el trabajo de Díaz-Martínez et al. (2016) y de *Dictyota* del trabajo de Lozano (2016) entre otras secuencias otenidas de Genbank.

