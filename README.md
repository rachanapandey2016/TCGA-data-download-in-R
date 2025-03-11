# TCGA-data-download-in-R  
---  
**Project Overview**  
---  
This repository provides a comprehensive guide on how to download, preprocess, and analyze data from Genomic Data Commons(GDC) portal using the TCGAbiolinks package in R. The script covers retrieving transcriptome profiling (RNA-Seq), DNA methylation, and mutation data, as well as visualizing the results using maftools and pheatmap.  

**TCGAbiolinks Package**  
---   
TCGAbiolinks is an R/Bioconductor package for integrative analysis with GDC data. The aim of TCGAbiolinks is to:  
- Facilitate the GDC open-access data retrieval.
- Prepare the data using the appropriate pre-processing strategies.
- Provide the means to carry out different standard analyses.
- Enable easy reproduction of earlier research results.

In more detail, the package provides multiple methods for analysis, such as differential expression analysis and identifying differentially methylated regions. It also includes various visualization methods, such as survival plots, volcano plots, and starburst plots, making it easier to develop complete analysis pipelines. TCGAbiolinks is an R/Bioconductor package specifically designed for integrative analysis with GDC data.
For official documentation, visit: https://bioconductor.org/packages/release/bioc/html/TCGAbiolinks.html Reference Manual: https://bioconductor.org/packages/release/bioc/manuals/TCGAbiolinks/man/TCGAbiolinks.pdf

**Genomic Data Commons**  
---  
Launched by National Cancer Institute (NCI) in 2016, GDC provides repository of standardized cancer genomic data sets and computational platform for cancer researchers who need to understand cancer, its clinical progression, and response to therapy. For more information visit the official GDC link: https://gdc.cancer.gov/about-gdc/gdc-overview

**Required R Packages**  
- `TCGAbiolinks` – Query and download TCGA data  
- `tidyverse` – Data manipulation  
- `maftools` – Mutation annotation format visualization
- `pheatmap` – Heatmap visualization
- `SummarizedExperiment` – Data structure for genomics data
- `sesame` – DNA methylation analysis



