# Laboratorio 03 - Ensamblaje de genomas y predicción de genes



### Parte 1: El artículo genoma

**1.** ¿Cuántos *Sequencing Projects* y *Analysis Projects* hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? 

| Sequencing Projects   | [215.124](https://gold.jgi.doe.gov/projects)          |
| --------------------- | ----------------------------------------------------- |
| **Analysis Projects** | [174.491](https://gold.jgi.doe.gov/analysis_projects) |

Su diferencia se basa en que *Sequencing Projects*  es 



##### **2.** ¿Cuál es el dominio más representado en la base de datos, *archea*, *bacteria*, *eukaryote*, o *virus*? 

R: Bacterias

##### **3.** ¿Cuáles son los *phyla* más representados entre los proyectos de genomas bacterianos en la base de datos? 

R: Proteobacteria 

##### **4.** ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) 

R: Medicina

##### **5.** ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) 



- [The bonobo genome compared with the chimpanzee and human genomes](https://www.nature.com/articles/nature11128)   En la pagina Nature

-  [The bonobo genome compared with the chimpanzee and human genomes.]([https://www.ncbi.nlm.nih.gov/pubmed/22722832)   En la pagina NCBI



##### **6.** Explica, qué es el N50, L50, y NG50.  [L50,and related statistics](https://en.wikipedia.org/wiki/N50)

L50 : Dado un conjunto de contigs, cada uno con su propia longitud, el conteo L50 se define como el menor número de contigs cuya suma de longitud produce N50.

N50: Dado un conjunto de contigs, cada uno con su propia longitud, la longitud N50 se define como la longitud de secuencia más corta al 50% del genoma.

NG50: La estadística NG50 es igual a N50, excepto que es el 50% del tamaño del genoma conocido o estimado que debe ser de la longitud NG50 o más. Esto permite comparaciones significativas entre diferentes conjuntos. En el caso típico en que el tamaño del conjunto no es más que el tamaño del genoma, la estadística NG50 no será más que la estadística N50.



##### **7.** ¿Cuál es el propósito de calcular estas estadísticas? 

R: En biología computacional, N50 y L50 son estadísticas de un conjunto de longitudes de contig o andamio. El N50 es similar a una media o mediana de longitudes, pero tiene un mayor peso dado a los contigs más largos. Se usa ampliamente en el ensamblaje del genoma, especialmente en referencia a las longitudes del cóntigo dentro de un ensamblaje en borrador. L50 es el número de contigs cuya longitud sumada es N50. También están las estadísticas relacionadas N90, NG50 y D50.

 El propocito es conocer y tener medidas de comparación para cuando se esten ralizando proyectos en paralelos del mismo organismo como la confianza del experimento realizado para conocer las secuencias y ensamblar un genoma a partir de predicciones



##### **8.** ¿Cuántos *contigs* conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los *contigs*) 

| Number of contigs | 121,356    |
| ----------------- | ---------- |
| **Contig N50**    | **66,676** |
| **Contig L50**    | **11,048** |



##### **9.** ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

Total length (Mb): 3286.64 

GC%: 42.3185 



##### **10.** ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma? 

Genome coverage: 26x

Sequencing technology:  454 GS FLX; 454 GS FLX Titanium





### Parte 2: Predicción de genes



##### **11.** Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [*start*] y término [*stop*])? 

R: Se encontraron 7 ORFs.

 El ORF7 se sobrepone con el ORF1, el ORF2 se sobrepone con el ORF4,El ORF6 se sobrepone con el ORF4, El ORF3 se sobrepone con el ORF5.

Largo ORF1: 302 aa (+) hebra codificante

 Largo ORF2: 25 aa (+) hebra codificante 

Largo ORF3: 32 aa (+) hebra codificante 

Largo ORF4: 146 aa (-) hebra no codificante 

Largo ORF5: 134 aa (-) hebra no codificante 

Largo ORF6: 27 aa (-) hebra no codificante

Largo ORF7: 47 aa (-) hebra no codificante

 

| [Label](https://www.ncbi.nlm.nih.gov/orffinder/#) | [Strand](https://www.ncbi.nlm.nih.gov/orffinder/#) | [Frame](https://www.ncbi.nlm.nih.gov/orffinder/#) | [Start](https://www.ncbi.nlm.nih.gov/orffinder/#) | [Stop](https://www.ncbi.nlm.nih.gov/orffinder/#) | [Length (nt \| aa)](https://www.ncbi.nlm.nih.gov/orffinder/#) |
| ------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------ |
| ORF1                                              | +                                                  | 1                                                 | <1                                                | 909                                              | 909 \| 302                                                   |
| ORF4                                              | -                                                  | 1                                                 | 1388                                              | 948                                              | 441 \| 146                                                   |
| ORF5                                              | -                                                  | 2                                                 | 1795                                              | 1391                                             | 405 \| 134                                                   |
| ORF7                                              | -                                                  | 2                                                 | 598                                               | 455                                              | 144 \| 47                                                    |
| ORF3                                              | +                                                  | 2                                                 | 1433                                              | 1531                                             | 99 \| 32                                                     |
| ORF6                                              | -                                                  | 2                                                 | 1048                                              | 965                                              | 84 \| 27                                                     |
| ORF2                                              | +                                                  | 2                                                 | 1304                                              | 1381                                             | 78 \| 25                                                     |

Información extraída de : [Open Reading Frame Viewer ](https://www.ncbi.nlm.nih.gov/orffinder/)



##### **12.** ¿Qué tipo de programa es ORFfinder, *Ab initio* o por homología? 

 El buscador ORF busca marcos de lectura abiertos (ORF) en la secuencia de ADN ingresados. El programa devuelve el rango de cada ORF, junto con su traducción de proteínas. 

ORFfinder es un programa  *ab initio* ya que solo consideran la secuencia junto con las coincidencias en los parametros determinados como busqueda de codones de inicio y regiones regulatorias conservadas para predecir los diferentes marcos de lectura.



##### **13.** ¿A qué organismo pertenece la secuencia en cuestión?

 Corresponde al organismo llamado "Haemophilus influenzae" 

![](https://github.com/ConsueloBolivarMascaro/BIOINFORMATICA/blob/master/imagen%201%20lab%203.png?raw=true)



##### **14.** ¿Qué gen(s) está(n) codificados en la secuencia?

ORF1: Codifica para el gen de la proteína accesoria de formaito deshidrogenasa FdhE

ORF4: Codifica para el gen ribosomal-proteína-alanina N-acetiltransferasa

ORF5: Codifica para DNA polimerasa III subunidad PSI

##### **15.** Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? 

Los más correctos en mi opinión y según lo enconcontrado en la página web son ORF 1, ORF 4 y ORF 5 ya que presentan más a.a que el resto ( ORF 2 ORF 3 ORF6 y ORF7) y su longitud es mucho mas grande que el de los demás , pudiendo almacenar mas información.

