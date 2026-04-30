# Coral Reef Bleaching Analysis

**Course:** CSCI XXXX - Data Science  
**Date:** Spring 2026  

## Overview
This project analyzes a global coral reef dataset (1980–2020) to investigate the relationship between environmental conditions and coral bleaching. Principal Component Analysis (PCA) was used to identify dominant environmental patterns, and clustering methods were applied to explore potential reef groupings.

## Key Ideas
- Environmental variability is high-dimensional and not dominated by a single factor  
- Clustering does not strongly separate reefs by bleaching levels  
- Bleaching is moderately associated with specific environmental gradients, particularly thermal stress  
- Aggregating data at the reef level improves the ability to explain bleaching patterns  

## Methods
- Data cleaning and preprocessing (handling missing values, feature selection)  
- PCA for dimensionality reduction  
- K-means clustering  
- Correlation and regression analysis  

## Dataset
Bleaching and environmental data for global coral reef sites (BCO-DMO)  
https://doi.org/10.26008/1912/bco-dmo.773466.2  

## Structure
- `AnalysisA.ipynb` — Full dataset analysis  
- `AnalysisB.ipynb` — Aggregated reef-level analysis  
- `data/` — Cleaned datasets  

## Author
Gaeryth Ebert
