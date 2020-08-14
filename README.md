## Data analysis for _in prep_ manuscript
Analysis of single-celled microbial eukaryotes at Gorda Ridge hydrothermal vent field.

### Set up environment

* R environment information, link to conda installation instructions

### Data structure
All input raw data can be found at _ZENDO LINK_ and ```data-input/```. Contents and descriptions:
* ```Grazing-analysis-R-SKH.ipynb``` - R notebook that imports raw cell count information from grazing experiments, performs qc, calculations, and generates figures.
* ```gordaridge-analysis-SKH.ipynb``` - R notebook with all code to import ASV tables, quality control/decontaminate sequence counts, sort and curate ASV assignments, run statistical analyses, and generate all figures and tables.
* MAKE DIRECTORY WITH CODE FROM SNAKEMAKE TAG SEQ ANALYSIS

## Description of computational methods
Brief description of approaches used in Hu et al. 

### 1. Grazing experiment calculations

### 2. Amplicon analysis

### 3. 18S and 16S tag-sequencing analysis

### 4. Ordination

### 5. Correlations

In R, imported all correlations (no filtering). Subset only euk-prok interactions and spearman correlations > abs(0.4).

First, after subsetting only euk-prok:
euk-prok prok-euk 
56316664 56316664 

After subsetting by significance:
euk-prok prok-euk 
10168404 10168404

### Graphical comic abstract
![vent-comic](figs/GR-comic-protistsession.jpg)


> Last updated S. Hu August 2020
