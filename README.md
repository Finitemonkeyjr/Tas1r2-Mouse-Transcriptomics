# Tas1r2 Mouse Transcriptomics

This project explores the transcriptional role of the *Tas1r2* sweet taste receptor in metabolically active tissues using publicly available transcriptomic data from BXD mouse strains (GeneNetwork.org).

## Project Summary
As part of my MPH-Biomedical Informatics capstone, I investigated *Tas1r2* gene expression in brown adipose tissue, liver, and heart. The analysis included correlation testing, differential gene expression (DGE), and pathway enrichment to identify metabolic functions of interest.

## Tools & Methods
- R: `tidyverse`, `limma`, `enrichR`, `rstatix`
- Techniques: Pearson correlations, t-tests, DGE, GSEA, ORA
- Visualizations: heatmaps, volcano plots, enrichment bar charts
- Reproducibility: RMarkdown

## Repository Contents
- `Tas1r2_Analysis.Rmd` – Main analysis pipeline
- `ILE_Defense.pdf` – Final written report and presentation slides

## Data Disclaimer
Raw gene expression data is not included in this repository due to file volume. Data was obtained from GeneNetwork.org, and the RMarkdown files are annotated for clarity regarding expected inputs.

## Key Outputs
- Volcano plots of differentially expressed genes
- GSEA/ORA results showing pathway enrichment
- Summary tables of correlations and fold changes
