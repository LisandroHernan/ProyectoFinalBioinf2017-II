# Lisandro Hernandez Anaya #

En el presente repositorio se incluyen datos, scripts utilizados para analizar datos de secuencias Sanger obtenidas de las algas pardas *Padina* y *Dictyota*, 

En el repositorio se incluyen los siguientes directorios

**data**

Se encuentran subdirectorios llamados:

Seqin: En este se encuentran las matrices de datos para los marcadores **DictyotalesCOI** y ** DictyotalespsbA** por separado que incluye tanto datos obtenidos en el proyecto de investigación como en los trabajos realizados por Díaz-Martínez (2016) y Lozano (2016). Las cuales son secuencias ensambladas y listas para ser alineadas.

dataout: El subdirectorio incluye matrices con las secuencias alineadas, llamados **DictyotalesCOIAling.clustal** y **DictyotalespsbAAling.clustal**, el alineamiento se obtuvo con el software **clustalw**.
		 

**meta**

En este directorio se encuentra un archivo csv con el nombre de **Dictyotales2**, tabla en la cual se encuentran las localidades de recolecta, etc, que será para graficar un mapa en el cual se indiquen el sitio de recolecta para cada especie.

Aquí mismo se encuentran dos archivos con el GI de NCBI de cada una de las secuencias utilizadas en el presente análisis AccesoCOI, AccesospsbA

**bin**


Los scripts que se han utilizaron  para obtener todos los resultados se encuentran aquí


ScriptDeseq, contiene como descargar las secuencias de trabajos publicados como el de Díaz-Martínez (2016) y otras de NCBI así como pegarlas a un archivo que ya se tiene con las secuencias del estudio para cada gen (COI y psbA).

ScriptAlign este script presenta como alinear las matriz de secuencias del presente estudio junto con las secuencias de Díaz-Martínez y otras descargadas de NCBI con el software clustalw desde la terminal.

ScriptCOI_MxdisNJ en este script detalla como se debe cargar el archivo de alineamiento, generar una matriz de distancia con la libreria seqinr y realizar el análisis de Neighbor-Joining (NJ) para muestras con secuencias Sanger  con la librería ape para el gen COI.

ScriptpsbA_MxdisNJ en este script detalla como se debe cargar el archivo de alineamiento, generar una matriz de distancia con la libreria seqinr y realizar el análisis de Neighbor-Joining (NJ) para muestras con secuencias Sanger  con la librería ape para el gen psbA.

ScriptMapaAlgas, sirve para realizar un mapa el cual presentara los sitios de recolecta por especie.


**figures**
Se guardará el gráfico obtenido del análisis de Neighbor joining 
Aquí se encontrará el mapa obtenido para ubicar los puntos de recolecta de las muestras bajo estudio

**archive**

En este directorio se encuentran incluidas las matrices en formato fasta de cada región psbA y COI, y conjuntadas, las cuales solo incluyen las secuencias
de los datos obtenidos en el presente proyecto de investigación.También se encuentran un archivo en formato fasta de la las secuencias del género *Padina* obtenidas del Genbank generadas en el trabajo de Díaz-Martínez et al. (2016) y de *Dictyota* del trabajo de Lozano (2016) entre otras secuencias otenidas de Genbank.

