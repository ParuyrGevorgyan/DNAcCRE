# DNAcCRE: GRCh38 sequence analysis for cCRE clasification
### Multiple neural network-based models for classifying regulatory elements in the human DNA.

* To install the DNA sequence Data use: </br>
for i in {1..22} X Y; do wget https://hgdownload.soe.ucsc.edu/goldenPath/hg38/chromosomes/chr$i.fa.gz; done </br> 
for file in *.gz; do gunzip -c "$file" > chr_seq/$(basename "$file" .gz); done
* Annotations data from: https://genome.ucsc.edu/cgi-bin/hgIntegrator

![alt text](https://github.com/ParuyrGevorgyan/DNAcCRE/blob/main/img/DataIntegrator.png?raw=true)

Choose the fields necessary, the file format and download the data:

![alt text](https://github.com/ParuyrGevorgyan/DNAcCRE/blob/main/img/DataIntegratorFIELDS.png?raw=true)
