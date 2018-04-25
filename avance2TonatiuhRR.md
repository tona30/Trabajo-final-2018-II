**Avance 2** 
***Tonatiuh Ramírez Reyes***

*****

A la fecha 26 de abril cambie de set de datos porque los anteriores no tenian la informacion suficiente para realizar pre-procesamiento, es decir, informacion necesaria para hacer el control de calidad de los datos crudos (fastqc) uno de los pasos que mas me interesan realizar. Otra cuestion importante de mencionar es que los datos referidos eran de gran tamaño para realizar procesamiento de datos de manera eficiente (ya que mis recursos computacionales son limitados).
 
Debido a lo anterior tome la decision de cambiar de analisis de datos a un set fastq de menor peso y que incluya barcodes para hacer analisis de datos desde el pre hasta el post-procesamiento de la siguiente referencia:

**Publicacion:**
Gibbs HL, Sovic M, Amazonas D, Chalkidis H, Salazar-Valenzuela D, Moura-Da-Silva AM (2017) Recent lineage diversification in a venomous snake through dispersal across the Amazon River. Biological Journal of the Linnean Society 123(3): 651-665. https://doi.org/10.1093/biolinnean/blx158

**Repositorio:**

Gibbs HL, Sovic M, Amazonas D, Chalkidis H, Salazar-Valenzuela D, Moura-Da-Silva AM (2017) Data from: Recent lineage diversification in a venomous snake through dispersal across the Amazon River. Dryad Digital Repository. https://doi.org/10.5061/dryad.36sv8

De este repositorio elegi algunas carpetas para realizar analisis de datos desde fastq crudos para elaborar la mayor parte del procesamiento de datos en bioinformatica que me interesaria aplicar cuando reciba mis datos del proyecto.

Al momento de elaborar este informe de avance 2, tuve la afortunada oportunidad de asistir al workshop de iPyrad impartido por Deren Eaton, en este curso, aprendí a instalar y ejecutar de manera exitosa (al menos por el momento) el programa iPyrad, con el cual voy a realziar los ensambles de loci de novo. Voy a obtener reportes de calidad de las secuencias fastq con ayuda de fastqc en Docker. Posteriormente analizare los datos con ayuda de otros programas, una vez obtenga los archivos necesarios en los formatos adecuados.
El programa Stacks no lo pude correr, a pesar de que lo instale con exito, asi que utilizare iPyrad debido a que es muy facil de usar y de interpretar.



