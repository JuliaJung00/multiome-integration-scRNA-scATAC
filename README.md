# multiome-integration-scRNA-scATAC

## Overview
This project integrates single-cell RNA-seq and ATAC-seq data to identify cell states and regulatory programs.

## Data
10x Genomics PBMC multiome dataset
https://www.10xgenomics.com/datasets/pbmc-from-a-healthy-donor-no-cell-sorting-10-k-1-standard-2-0-0

## Methods
- RNA preprocessing (Scanpy)
- ATAC preprocessing (TF-IDF + LSI)
- Multimodal integration (Muon)
- Clustering and UMAP visualization

## Results
- Identified major immune cell types
- Joint embedding of RNA and ATAC modalities

## Future Work
- Apply to disease dataset (Parkinson’s disease)
