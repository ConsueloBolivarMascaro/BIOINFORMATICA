# Laboratorio 04 - Filogenética Molecular



##### **1.** ¿Qué ofrece o para qué sirve el portal Phylogeny.fr? 

El portal *Phylogeny.fr*  es una conexión de muchos programas diferntes de sitios web en uno solo, entre ellos se encuentra BLAST del NCBI.

 Ofrece servicios para realizar filogenética con distintos parámetros como también mezclar diferentes programas de alineamiento y tratamiento de datos.

La página web reconstruye , analiza y conecta relaciones filogenéticas entre secuencias moleculares en programas bioinformáticos para reconstruir un árbol filogenético grande a partir de un conjunto de secuencias  además de permitir visualizarlas.

##### **2.** Nombra y explica brevemente los 3 modos en los que se puede ejecutar el pipeline de Phylogeny.fr. 

Multiple Alignment: [MUSCLE](http://www.phylogeny.fr/one_task.cgi?task_type=muscle) Es un programa para crear múltiples alineamientos de secuencias de aminoácidos o nucleótidos. Se proporciona una variedad de opciones que le brindan la opción de 
optimizar la precisión, la velocidad o algún compromiso entre los dos. Los parámetros predeterminados son los que brindan la mejor precisión promedio en nuestras pruebas. Utilizando
las versiones actuales en el momento de la escritura, mis pruebas  muestran que MUSCLE puede lograr una mejor precisión promedio y una mejor velocidad que CLUSTALW o T-Coffee, dependiendo de las opciones elegidas.

Phylogeny: [PhyML](http://www.phylogeny.fr/one_task.cgi?task_type=phyml) es un software de filogenia basado en el principio de máxima verosimilitud. Las
primeras versiones de PhyML utilizaban un algoritmo rápido para realizar Intercambios de vecinos más cercanos (NNI), con el fin de mejorar una topología de árbol de inicio razonable

Tree viewers: [TreeDyn](http://www.phylogeny.fr/one_task.cgi?task_type=treedyn) ofrece vincular etiquetas de hoja únicas a listas de pares de anotaciones de variables / valores (metainformación), independientemente de las topologías de árbol, que son totalmente compatibles con el formato newick básico. Estas relaciones son utilizadas por operadores gráficos dinámicos, métodos de visualización de información como Proyección, Localización, Etiquetado, Reflexión que permiten una interacción desde anotaciones a árboles, desde árboles a anotaciones y desde árboles a árboles a través de anotaciones.

[One Click](http://www.phylogeny.fr/simple_phylogeny.cgi): Se pegan un conjunto de secuencias y  el software toma decisiones por mi (cada paso está optimizado para los datos)

[Advanced](http://www.phylogeny.fr/advanced.cgi): Establece manualmente los parámetros para los diversos pasos

[A la Carte](http://www.phylogeny.fr/alacarte.cgi):  Se puede crear nuestro propio flujo de trabajo de filogenia usando más programas disponibles

##### **3.** Menciona qué tipos de análsis se pueden realizar en el portal de acuerdo a la documentación. (*Online Programs*) 

- Buscar secuencias homologas con BLAST
- Convierte formatos de secuencias
- Refinar alineamientos
- Realiza análisis filogenéticos 
- Realizar alineamientos multiples

##### **4.** Incluye en tu informe una captura de pantalla de  las dos filogenias que inferiste. Recuerda que tu nombre completo debe  aparecer en la imagen de cada filogenia (*Name of the analysis*).

##### ![](https://raw.githubusercontent.com/ConsueloBolivarMascaro/BIOINFORMATICA/master/imagen%202%20lab%204.png) 

![](https://raw.githubusercontent.com/ConsueloBolivarMascaro/BIOINFORMATICA/master/imagen%201%20lab%204.png)

##### **5.** ¿A qué se refiere el paso de *Alignment curation* y para qué sirve? 

Esta opcion elimina regiones dificil de alinear por repetidas sustitucionesvolviendola no homologable entre si para poder hacer el analisis filogenetico mas facil ,quedando más ordenado de acuerdo  solo a la comparacion de homologia de secuencias. 

##### **6.** ¿Cuál es la diferencia entre BioNJ y Neighbor? 

Su diferencia de radica en la diferencias de grupos filogeneticos (taxas) que ellos puedan analizar, BioNJ es la version mejorada de Neighbor.

BioNJ: 5000 taxa 

Neighbor: 500 taxa 

##### **7.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste (sin *Alignment curation*). Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia (*Name of the analysis*). 

![](https://raw.githubusercontent.com/ConsueloBolivarMascaro/BIOINFORMATICA/master/imagen%203%20lab%204.png)

![](https://raw.githubusercontent.com/ConsueloBolivarMascaro/BIOINFORMATICA/master/imagen%204%20lab%204.png)

##### 8.¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias? 

 El curamiento lleva a un alineamiento de todas las secuencias que comparten un ancestro en común, sin èl puede desencadenar diferentes consecuencias como el  largo de las ramas , cambio de conseso y la forma del árbol filogenético, llegando incluso a emperejar secuencias directamente cuando en realidad están muy lejos entre si los cuales aparecen emparentados directamente en la filogenia curada en cambio  en la no curada el  aparecen directamente emparentado  con otros mamiferos.

##### **9.** Describe las diferencias entre las filogenias que  has estimado (4 en total): cantidad de grupos monofiléticos, relaciones  que potencialmente cambiaron, etc. 

El mayor cambio es el largo de los  brazos,  luego el número de grupos monofiléticos, en la filogenia,  los cambios mas evidentes es la relaciòn  entre los organismos de la misma especie como : 

- Curado son : Bison biso con Bos indicus

                         Ondobenus rosmarus con Neomonachus Schauinslandi

                          

- Sin curar son : Ondobenus rosmarus con Neomonachus Schauinslandi

                             Orycteropus after con Galeptus variegatus



  Los cuales pertenecen a la misma especie cuando las secuencias estan curadas estos aparecen juntos, pero al quitar la curación esta relacion directa  desaparece.

 Tambièn cabe mencionar para ambos casos (ProbCons, GBlocks, MrBayes, y  TreeDyn) y(ClustalW, "Remove positions with gaps", TNT, y TreeDyn) los  arboles son sin raíz. 