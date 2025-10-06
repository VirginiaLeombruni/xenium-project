# Cellular Classification in Breast Cancer Spatial Transcriptomics Data

This repository contains the analysis of spatial transcriptomics breast cancer data using the [10x Genomics Xenium](https://www.10xgenomics.com/products/xenium) platform. The project focuses on classifying epithelial cells as Normal or Malignant, with special attention to cells labeled as *Unknown*.

## Project Structure

1. **Molecular_Data_Analysis_I.ipynb** – Preprocessing and exploratory analysis of molecular data.
2. **Molecular_Data_Analysis_II.ipynb** – Application of gene signatures for epithelial cell classification.
3. **Neighbor_Analysis.ipynb** – Evaluation of the influence of neighboring cells on *Unknown* cells.
4. **Histological_Features_Analysis.ipynb** – Analysis of histological features to support classification.
5. **Integrative_Features_Analysis.ipynb** – Integration of molecular and histological features to improve classification performance.

- `requirements.txt` – List of Python packages and versions needed for reproducibility.

## Installation

Install the required packages with:

```bash
pip install -r requirements.txt
