# 🧬 sc-RNAseq Analysis of Human Pancreatic Islets

This repository contains a single-cell RNA-seq (scRNA-seq) analysis pipeline applied to human pancreatic islets using publicly available data (GSE84133). The analysis includes preprocessing, quality control, normalization, dimensionality reduction, clustering, batch correction, and cell type annotation.

## 🔹 Highlights

- **Dataset**: GSE84133 (10X Genomics platform)
- **QC & Filtering**: On mitochondrial content, gene/cell thresholds
- **Normalization & Log-transform**: Counts normalized to 10,000 per cell and log1p-transformed
- **Dimensionality Reduction**: PCA and UMAP
- **Batch Correction**: Harmony
- **Clustering**: Leiden algorithm
- **Annotation**: Canonical pancreas markers

## 🔧 Tools

- `Scanpy`, `AnnData`, `Pandas`, `HarmonyPy`
- `Plotly`, `Seaborn`
- Data fetched via `wget` from [GEO](https://www.ncbi.nlm.nih.gov/geo/)


