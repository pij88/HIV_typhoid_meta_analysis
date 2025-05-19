# HIV & Typhoid / iNTS Systematic Review — Reproducible Code & Data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15463296.svg)](https://doi.org/10.5281/zenodo.15463296)

This repository hosts the **Quarto analysis, extracted datasets, and derived figures** that support the manuscript:

> **TITLE OF MANUSCRIPT**  
> Peter I. Johnston *et al.* (manuscript under review)  


---

## Repository structure

```text
.
├── analysis.qmd              ← Quarto document: full analysis pipeline
├── data/
│   ├── TF_data_final.csv      ← Extracted study-level data (typhoid)
│   └── NTS_SR_final.csv       ← Extracted study-level data (iNTS)
├── output/
│   ├── figures/               ← All figures produced on render
│   └── processed_data/        ← Any intermediate CSVs saved by the script
├── README.md
└── LICENSE
