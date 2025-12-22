# Gene-Expression-Analysis-and-Interpretation
Assigment 2 Biological Principals &amp; Celullar Organization, MSc AI for Medicine and Medical Research, UCD 2025/2026

Overview

This repository contains an R-based analysis project of investigation on transcriptomic differences between HER2-amplified and non-amplified breast tumours using RNA sequencing, copy number alteration and clinical data from the TCGA BRCA PanCancer Atlas cohort.

This project combines differential expression analysis, pathway enrichment and survival analysis to characterise molecular and prognostic features associated with HER2 amplification.

Objectives

The main objective is to identify differentially expressed genes between HER2-amplified and non-amplified breast tumours. 
Secondary objectives are to characterise biological pathways associated with HER2-driven transcriptional programs, assess global transcriptomic variation using PCA and hierarchical clustering and develop a prognostic gene-expression-based risk model using LASSO-regularised Cox regression.

Data source

The analysis uses publlicly available >TCHA BRCA PanCancer Atlas (2018) data.
The datasets used were RNA-seq expression, copy number alteration (CNA) data, and Clinical patient metadata.
The datasets were matched using standardised TCGA patient barcodes.

Methods

1.- Data preprocessing and sample matching.
2.- Differential expression analysis with DESeq2.
3.- Pathway enrichment analysis.
4.- Variance stabilising transformation and PCA.
5- Heatmap visualisation of top differentially expressed genes.
6.- Survival analysis using LASSO-regularised Cox proportional hazards models.
7.- Kaplan-Meier risk stratification.

Findings

* Strong overexpression of ERBB2 amplicon-associated genes
* Enrichment of cell-cycñe and mitotic pathways in HER2-amplified tumours.
* Suppresion of immune-related pathways in HER2-amplified tumours.
* Identification of a small gene set with prognostic relevance that stratifies patient survival.

Software Requirement

This project was done with R version 4.5.1.
The packages used were:
* DESeq2
* clusterProfiler
* enrichplot
* ReactomePA
* org.Hs.eg.db
* survival
* glmnet
* pheatmap.

°The installation of BioConductor is necesarry for the installation of these packages.

