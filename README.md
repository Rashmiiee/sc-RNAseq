🧬 sc-RNAseq Analysis of Human Pancreatic Islets
This repository contains a single-cell RNA-seq (scRNA-seq) analysis pipeline applied to human pancreatic islets using publicly available data (GSE84133). The analysis includes comprehensive preprocessing, quality control, normalization, dimensionality reduction, clustering, batch correction, and cell type annotation.

🚀 Highlights
Dataset: GSE84133 (10X Genomics platform)

QC & Filtering: Performed on mitochondrial content, gene/cell thresholds

Normalization & Log-transform: Counts per cell normalized to 10,000; log1p applied

Dimensionality Reduction: PCA and UMAP for visualization

Batch Correction: Performed using Harmony

Clustering: Leiden algorithm used to identify clusters

Annotation: Based on canonical pancreas marker genes

🔧 Key Tools
Scanpy, AnnData, Pandas, HarmonyPy, Plotly, Seaborn

Source data fetched via wget from GEO

