Contains data and scripts for the final project **"Recent lineage diversification in a venomous snake"** . This project is a re-analysis from part of original datset. In this project I started with 5 unzipped fastq files, which were: RAD26, RAD28, RAD50B, RAD55 and RAD69.

### `/bin/`

The scripts in `/bin` should be run in the order they are numbered. Each script is commented to be able to reproduce the analyzes carried out.

Scripts content:

* `1.compile.sh` This script compiles the fastq files that were downloaded separately and makes one only called catbatrox.fastq

* `2.quality.sh` This script check the quality of reads and the data in general.

* `3.assemble.sh` This is not a script, it contains instructions for making the assembly in iPyrad.

* `4.parametersvcf.sh`  This script calculate population parameters from vcf files.

* `5.plinkfiles.sh` Contains commands and instructions to transform files and run admixture.

* `6.admixture` Calculate P, Q and error with cross-validation for K values (n=1-13).

* `7.graphics.R`Contains script to make graphics in R, two graphics can be realized, to choose K value and plot of Q values. 

* `8.snapp.txt` This is not a script, it contains instructions for making species tree in SNAPP module of BEAST2.

These scripts use the data in `rawfastq` , `batcat` .

### `/rawfastq`

Contains 5 unzipped raw fastq files obtained from the original dataset downloaded from the dryad. The whole project starts with this dataset.


### `/batcat` 

Contains the startup files `catbatrox.fastq` and `barcodesbat.txt`. Also include the params file `params-batroxcat.txt`, the iPyrad input file .  

### `/vcfbatcat` 

Includes output files calculated in vcftools, heterozygosity values, allele frequencies, pi values and .ped and .map files to export to plink.

### `/plink` 

Contains `.ped` and `.map` files

### `/admixture` 

contains `P` , `Q`  and `log$K.out` files with values for *K* values (1-13).

### `/rgraphics`

contains `.csv` table with log error values for each K (1-13) and `plink` file to graphics Q values.


##
**Notes**
Species tree was implemented on SNAPP in windows version of BEAST2. 
