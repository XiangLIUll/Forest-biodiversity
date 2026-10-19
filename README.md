# Mapping Tree-Species and Structural Diversity with Satellite Embeddings across Central European Temperate Forests

This repository contains the code used for the study **“Mapping Tree-Species and Structural Diversity with Satellite Embeddings across Central European Temperate Forests.”**

## Project description

We investigated the potential of **AlphaEarth Satellite Embeddings (ASE)** for mapping tree-species and structural diversity in temperate forests. Using field inventory data from **144,519 trees in 285 one-hectare forest plots across four regions in Germany**, we modelled six diversity indices and compared ASE with conventional predictors derived from **Sentinel-1, Sentinel-2, and environmental variables**.

Model performance was evaluated using **10-fold spatial block cross-validation** and **leave-one-region-out validation**. We also examined which ecological and remote-sensing information is retained in ASE and which factors affect prediction performance.

Overall, ASE provided a compact, analysis-ready predictor set with performance comparable to conventional multi-source approaches, while reducing the need for extensive preprocessing and manual feature engineering.

## Workflow

1. Prepare field inventory data and calculate diversity indices.
2. Extract ASE and conventional remote-sensing and environmental predictors.
3. Train models for six tree-species and structural diversity indices.
4. Evaluate performance using spatial block cross-validation and leave-one-region-out tests.
5. Analyse information retention and factors influencing model performance.

## Data availability

Field inventory data are subject to the access conditions of their respective data providers. See the [Biodiversity Exploratories Information System (BExIS)](https://www.bexis.uni-jena.de/) for relevant datasets. Satellite embeddings and remote-sensing products are available from their original providers.

## Citation

If you use this code, please cite the accompanying paper:

**Liu et al.** *Mapping Tree-Species and Structural Diversity with Satellite Embeddings across Central European Temperate Forests.* **[Journal and DOI to be added]**.
