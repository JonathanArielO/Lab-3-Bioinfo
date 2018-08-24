# Laboratorio 03 - Ensamblaje de genomas y predicción de genes
## Parte 1: El artículo genoma
##### 1. ¿Cuántos Sequencing Projects y Analysis Projects hay depositados en GOLD? ¿Cuál es la diferencia entre ambos?
Existen 215.124 Sequencing Projects y 174.491 Analysis Projects en JGI-GOLD. Los Analysis Projects son los procesos informáticos de los Sequencing Projects, estos últimos corresponden a los organismos que son objetos de secuenciación. 
##### 2. ¿Cuál es el dominio más representado en la base de datos, archea, bacteria, eukaryote, o virus?
El dominio más representado en la JGI-GOLD son las bacterias.
##### 3. ¿Cuáles son los phyla más representados entre los proyectos de genomas bacterianos en la base de datos?
La mayoría de los proyectos bacteriales corresponden a proteobacterias, con un 37,3% de predominancia.
##### 4. ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD?
La mayoría de los proyectos a partir de bacterias son de tipo médico, con 58,9% de relevancia.
##### 5. ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma)
[(Pan paniscus)](https://www.ncbi.nlm.nih.gov/genome/?term=Pan+paniscus)
##### 6. Explica, qué es el N50, L50, y NG50.
EL N50 es la longitud de secuencia más corta tomando en cuenta la mitad del genoma, el que puede considerarse base los contigs de mayor longitud; L50 se define como la menor cantidad de contigs que al sumarse sus longitudes produce el N50; y la estadística NG50 es igual a N50, excepto que toma como referencia el tamaño del genoma, lo cual permite compararlo con otros sin tantos problemas.
##### 7. ¿Cuál es el propósito de calcular estas estadísticas?
Para analizar la calidad del trabajo de ensmblaje. Mientras mayor sea el N50 será más confiable, ya que disminuye la imprecisión de los datos.
##### 8. ¿Cuántos contigs conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma?
El genoma está compuesto por 121.356 contigs, con 66.676 N50 y 11.048 L50.
##### 9. ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?
La longitud del genoma de Bonobo es de 3286,64 Mb y tiene un 42,3185% de contenido GC.
##### 10. ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?
Se secuenció en 454 GS FLX/ 454 GS FLX Titanium, con el método Celera Assembler v. 5.4.3.
## Parte 2: Predicción de genes
##### 11. Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [start] y término [stop])?
![](https://github.com/JonathanArielO/Lab-3-Bioinfo/blob/master/ORF1.png)

Se encontraron 7 ORFs mediante ORFfinder, 3 en la hebra positiva y 4 en la negativa, con los siguientes tamaños: 
    - ORF1: 909nt
    - ORF2: 78nt
    - ORF3: 99nt
    - ORF4: 441nt
    - ORF5: 405nt
    - ORF6: 84nt
    - ORF7: 144nt
entre estas ORF6 se sobrepone a ORF4, debido a que se encuentran en la misma hebra.
##### 12. ¿Qué tipo de programa es ORFfinder, Ab initio o por homología?

##### 13. ¿A qué organismo pertenece la secuencia en cuestión?

##### 14. ¿Qué gen(s) está(n) codificados en la secuencia?

##### 15. Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)?
