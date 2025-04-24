# The contribution of small RNAs to the evolution of separate sexes and sex chromosomes in the plant _Silene latifolia_

#### This repository contains all the necessary code for the paper published in the Journal of Evolutionary Biology
[!doi](https://www.doi.org/)
#### Eddy Mendoza-Galindo, Aline Muyle, CEFE Montpellier

Correspondence: aline.muyle[at]cefe.cnrs.fr

Open for academic and research purposes only, 2025

Person who wrote the code: Eddy Mendoza-Galindo

Study summary:
Dioecy is a breeding system with separate females and males, where sex can be determined by sex chromosomes (for instance XY males and XX females). Dioecy is generally associated with the evolution of sexual dimorphism. In this study, we tested whether small RNAs (sRNAs) play a role in sexual dimorphism and sex chromosome evolution in Silene latifolia. We generated new data for female and male sRNAs and DNA methylation. We showed that sRNAs are most of the time female-biased in S. latifolia, suggesting the presence of the Y chromosome globally impacts the epigenome by diluting sRNAs genome-wide in males. We found limited evidence for the regulation of sex-biased genes by sRNAs, but we nonetheless identified a male-biased transcription factor that may potentially be regulated by sex-biased RNA-directed DNA methylation. This transcription factor might contribute to male traits, through the regulation of key factors in sex-determination and phenotypic sexual dimorphism. Finally, we compared female and male sRNA mapping along the S. latifolia sex chromosomes. We found that X and Y genes are targeted by significantly more sRNAs in males compared to females and PAR genes. Our results suggest that Y genes silencing following Y degeneration leads to the formation of sRNAs that can interact with both X and Y genes in males due to X-Y sequence homology. Our work calls for future investigation of the impact of these sRNAs generated from the Y chromosome on X gene expression in males. 

Code version 1.0

Overview of files and their contents:

-----------------------
notebook_bash.ipynb
-----------------------

This Python notebook contains all command line code lines necessary to perform the analysis from scratch. It contains the sRNA-seq and RNA-seq data processing, alignments and quantification, genomic analyses, and other miscellaneous scripts. Please adjust your paths accordingly. Software versions are indicated in the main text of the paper.

-----------------------
notebook_R.Rmd
-----------------------

This R Markdown notebook contains all the necessary R code to perform the statistical analyses and create visualisations. Package versions are shown in the last part of the notebook [sessionInfo()], otherwise indicated in the main text of the paper.


