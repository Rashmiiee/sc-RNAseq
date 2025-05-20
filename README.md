🧬 sc-RNAseq Analysis of Human Pancreatic Islets


A reproducible single-cell RNA-seq (scRNA-seq) analysis pipeline applied to human pancreatic islet cells. This pipeline performs end-to-end processing from raw count matrices to batch-corrected, annotated cellular clusters, using standard tools like Scanpy and Harmony.

📊 Overview
Dataset: GSE84133 (10X Genomics scRNA-seq of human pancreatic islets)

Sample count: 4 donors (GSM2230757–60)

Total cells after QC: 8,499

Goal: Clean, normalize, and cluster cells into biologically meaningful populations with robust visualization

🛠️ Pipeline Summary
Step	Tool(s)
Data download	wget
Quality control	Scanpy
Normalization & log1p	Scanpy
Dimensionality reduction	PCA, UMAP
Batch correction	Harmony
Clustering	Leiden algorithm
Cell type annotation	Canonical markers

🖥️ Technologies Used
🐍 Python (≥3.8)

🧪 Scanpy

📊 Harmony

📈 Plotly & Seaborn for interactive and static visualization
