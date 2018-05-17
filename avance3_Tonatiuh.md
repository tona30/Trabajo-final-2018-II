**Avance 3 proyecto final**
***Tonatiuh Ramírez Reyes***

*****

En este último avance menciono la manera en la que estoy organizando mi proyecto final del curso de bioinformática y anexo el link al avance del README que documenta los análisis realizados en este proyecto.
Mi proyecto bioinformático contiene datos crudos, datos procesados, scripts y documentación.
El directorio `/data` se encuentra en el escritorio y recopila todas las carpetas que contiene mi proyecto. 
`/bin` contiene los scripts que permiten trabajar los análisis del dataset.
`/rawfastq` contiene los datos fastq crudos por separado. Los archivos fastq que seleccioné fueron 5 carpetas fastq del repositorio mencionado en el avance 2, las cuales fueron RAD26, RAD28, RAD50B, RAD55, RAD69.
`/batcat` contiene los datos concatenados para realizar todos el pre y postprocesamiento, así como el archivo barcodes para demultiplexear el dataset. Los barcodes se agruparon en un solo archivo (.txt) para trabajar un solo dataset conctaneado de cada carpeta RAD y poder ensamblar loci *de novo* en iPyrad. 

Se visualizaron los archivos fastqc para determinar la calidad de los *reads*, los cuales constatan buena calidad de los mismos. Se elaboró el ensamble *de novo* del dataset con ayuda del programa iPyrad, se le indicó al archivo de parametros los datos adecuados para el dataset.
Los scripts con los que estoy trabajando realizan análisis "sencillos", es decir, no forman una pipeline completa, ya que en esta etapa de aprendizaje prefiero visualizar paso por paso los resultados de cada script, además algunos programas no los he podido correr de manera satisfactoria desde la linea de comandos, particularmente tuve problemas con Structure y BEAST2, los cuales están instalados, pero en algun punto no los he podido correr. 
A pesar de lo anterior, pude instalar Admixture y correrlo de forma adecuada (en lugar de Structure), mientras que el árbol de especies con SNP's lo tuve que realizar con el módulo de SNAPP en windows pues éste era un punto que me interesaba mucho realizar y aunque no lo logré desde la terminal, lo pude correr en la version de BEAST2 para windows.
A partir de los resultados en Admixture elaboré las gráficas correspondientes en **Rstudio** para visualizar la estructura genética de los individuos. El link del Readme es: 

https://github.com/tona30/Trabajo-final-2018-II/blob/master/READMEproj.md 