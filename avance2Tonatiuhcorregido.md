**Avance 2** 
***Tonatiuh Ramírez Reyes***

*****

A la fecha 26 de abril cambié de set de datos porque los anteriores no tenían la información suficiente para realizar pre-procesamiento, es decir, información necesaria para hacer el control de calidad de los datos crudos (fastqc) uno de los pasos que más me interesan realizar. Otra cuestión importante de mencionar es que los datos referidos eran de gran tamaño para realizar procesamiento de datos de manera eficiente (ya que mis recursos computacionales son limitados).
 
Debido a lo anterior tomé la decisión de cambiar de análisis de datos a un set fastq de menor peso y que incluya barcodes para hacer análisis de datos desde el pre hasta el post-procesamiento de la siguiente referencia:

**Publicación:**

Gibbs HL, Sovic M, Amazonas D, Chalkidis H, Salazar-Valenzuela D, Moura-Da-Silva AM (2017) Recent lineage diversification in a venomous snake through dispersal across the Amazon River. Biological Journal of the Linnean Society 123(3): 651-665. https://doi.org/10.1093/biolinnean/blx158

**Repositorio:**

Gibbs HL, Sovic M, Amazonas D, Chalkidis H, Salazar-Valenzuela D, Moura-Da-Silva AM (2017) Data from: Recent lineage diversification in a venomous snake through dispersal across the Amazon River. Dryad Digital Repository. https://doi.org/10.5061/dryad.36sv8

De este repositorio elegí algunas carpetas para realizar análisis de datos desde fastq crudos para elaborar la mayor parte del procesamiento de datos en bioinformática que me interesaría aplicar cuando reciba mis datos del proyecto.

Al momento de elaborar este informe de avance 2, tuve la afortunada oportunidad de asistir al workshop de iPyrad impartido por Deren Eaton, en este curso, aprendí a instalar y ejecutar de manera exitosa (al menos por el momento) el programa iPyrad, con el cual voy a realizar los ensambles de loci de novo. Voy a obtener reportes de calidad de las secuencias fastq con ayuda de fastqc en Docker. Posteriormente analizaré los datos con ayuda de otros programas, una vez obtenga los archivos necesarios en los formatos adecuados (output files).
El programa Stacks no lo pude correr, a pesar de que lo instalé con relativo éxito, por lo tanto, utilizaré iPyrad para el ensamble de loci de novo, debido a que es muy fácil de usar y de interpretar.

