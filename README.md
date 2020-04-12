# sMETASeq
sMETASeq
This tutorial shows how to run sMETASeq using Galaxy (https://usegalaxy.org/)

## Purpose :

sMETASeq is an analysis pipeline to detect microbes, including virus, bacteria and other pathogens, from small RNA-seq data. The pipeline will also include steps to generate host small RNA expression profiles. The microbes are detected using the kraken database and the host small RNAs are detected using miRBase and RNACentral, for miRNAs and other small RNAs, respectively. 

Additional resources:

Sneak peek of the paper: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3525549

##  sMETASeq Galaxy pipeline 

## Requirements

1) Create Galaxy account and login: https://usegalaxy.org/login

2) Download references files and unzip the files:
  - RNACentral: ftp://ftp.ebi.ac.uk/pub/databases/RNAcentral/releases/14.0/genome_coordinates/gff3/homo_sapiens.GRCh38.gff3.gz
	- miRBase: ftp://mirbase.org/pub/mirbase/CURRENT/genomes/hsa.gff3
	
3) Data files you are analyzing have to be in fastq.gz format
4) In Galaxy, load Fastq files and the two reference files using >Get Data  and >Upload file from your computer 
