# allergic-rhinitis-transcriptomics
Exploratory transcriptomic analysis of allergic rhinitis using public microarray data

# Pathway-level immune dysregulation and molecular heterogeneity in allergic rhinitis

This repository contains code and figures for an exploratory transcriptomic analysis of allergic rhinitis based on publicly available microarray data.

## Overview
The analysis focuses on:
- Differential expression between allergic rhinitis and healthy controls
- Pathway-level immune and epithelial signaling patterns
- Assessment of molecular heterogeneity via within-group expression variance

Asthma samples present in the original dataset were excluded to avoid confounding due to shared but distinct inflammatory mechanisms.

## Data
All gene expression data were obtained from the NCBI Gene Expression Omnibus (GEO).  
Only de-identified, publicly available data were used.

## Analysis
The analysis was performed in Python using pandas, NumPy, SciPy, and matplotlib.  
See `analysis.ipynb` for the complete workflow.

## Figures
Figures in the `figures/` directory correspond directly to those presented in the accompanying bioRxiv preprint.

## Disclaimer
This work is exploratory and hypothesis-generating.  
It is not intended to inform clinical decision-making or guide patient care.
