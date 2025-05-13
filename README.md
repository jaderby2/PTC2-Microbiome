# PTC2-Microbiome Repository

## Project: Snail Hemolymph Microbiome Differs Between Genotypes in a Genomic Region Associated with Resistance to Parasite Infection

This repository contains all raw data, code, and processed objected used to reproduce the analyses and figures in this manuscript. 



## Table of Contents

1. Project Overview
2. Code
3. Data
4. Documents
5. License



## Project Overview

This project analyses the hemolymph and tank water microbiome of BS90 _Biomphalaria glabrata_ snails using 16S rDNA sequencing data. Data was processed in R following the DADA2 and microViz pipelines. Downstread analyses and figure generation was conducted in R. The goal of this project was to assess differences in microbial abundance and presence between resistant and susceptible inbred snail lines fixed at a genomic marker, the _PTC2_, that has additional roles in snail susceptibility to schistosome infection. 

## Code

* All data processing and filtering are documented in the "code/Sequence_processing.rmd" directory. 
* All figures, tables, and data generated are documented in the "code/Figure_generation.rmd" directory. 

## Data

* Raw microbial sequences (FASTQ files) stored in the "data/Raw_sequences/" directory.
* Data objects generated for the taxon level analysis figures are stored in the "data/Taxon_level/" directory. 
* The meta data file used to generate the phyloseq object is stored as "data/Metadata.xlsx".
* The completed phyloseq object is stored as "data/ps.rds". 
* "data/Supplemental Data S1.xlsx" contains the data used to generate Supplemental Figure S1. The data shows the number of shared snails in which each taxon is present at the Family and Genus levels. 
* "data/Supplemental Data S2.xlsx" contains the Amplicon sequence variant (ASV) taxonomy and abundance data grouped by sample type. 
* The assigned taxa using the Silva reference data base is stored as "data/taxa.rds".
* The Silva reference data base used is sotred as "data/silva_nr99_v138.1_train_set.fa".

## Documents

* Figures for the main text are stored in the "docs/Figures/" directory. 
* The table for the main text is stored in the "docs/Table/" directory.
* The supplemental figures are stored in the "docs/Supplemental_figures/" directory. 

## License

This project is released under the MIT License for code.
