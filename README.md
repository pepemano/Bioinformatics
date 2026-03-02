# Transcriptomics Workflow DEMO
**Author:** Jose Alvarez  
**Date:** [March 2nd, 2026]

---

## Overview

This repository contains a simulated multi-omics workflow integrating:

- Differential gene expression analysis 
- Mutation stratification (e.g. TP53, CTNNB1)
- Copy Number Variation (CNV) Analysis 
- Kaplan–Meier survival modeling 

All datasets are randomly generated for demonstration purposes.
The pipeline is fully reproducible.

---

## Dataset

Mock datasets are generated internally within the notebook. No external files are required. This approach demonstrates reproducibility, analysis workflow, and figure generation.

## Results

Click file -> transcriptomics_analysis_DEMO.ipynb

---

## Requirements

Python 3.9+  

Packages:  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- lifelines  

Install with:

```bash
pip install pandas numpy matplotlib seaborn lifelines
