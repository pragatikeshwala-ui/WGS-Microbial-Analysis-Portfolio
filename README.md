## WGS Microbial Analysis — MSc Thesis Project

**Topic:** [Metagenomic Insights into Skin Microbiome Diversity and Forensic Potential]
**Tools used:** UseGalaxy, Fastp,Bowtie2, SPAdes, 
               Kraken2/bracken, MEGAHIT, ABySS, RStudio 

## What I did:
1. Received raw WGS reads (FASTQ format)
2. Quality checked and trimming using fastp
3. remove the host contamination using Bowtie2
4. classified microbial reads using kraken2 and bracken
5. Assembled microbial genome using SPAdes,MEGAHIT,ABySS
6. Classified microbial reads again with kraken2/bracken
7. Alpha beta diversity and taxonomic classification analysis in RStudio using different packages

## Results:
- [ in this whole alaysis the classified and unclassified reads were examine under same condition and each of the assembly tool and pre classified reads gave very different values of diversity and taxonomic classification, pre assembly reads can be more  reliable for forensic relevence rather than assembled one assembly removed the low abundance taxa which is more useful for forensic use and the ABySS is more accurate and very close to the pre assembly reads so it is more useful for forensic purpose menwhile SPAdes gave the highest diversity rate, there is alos different body sites and different age group comparision gave very significant results.]

## Files:
- thesis.pdf — Full thesis document
- results/ — Analysis output tables
