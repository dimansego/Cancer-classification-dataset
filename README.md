# Multi-Omics Cancer Dataset (Top Features Version)

## Overview

This dataset is a curated subset of the MLOmics benchmark database for cancer machine learning research. It contains four cancer types with Top-feature selected multi-omics data, prepared for machine learning and bioinformatics tasks such as cancer subtype classification, clustering, and multi-omics integration.

The dataset includes four omics modalities for each cancer type:

- mRNA expression
- miRNA expression
- DNA Methylation (Methy)
- Copy Number Variation (CNV)

Only the **Top** feature version is included in this dataset.

Top features are identified through ANOVA statistical testing according to p-values, selecting the most significant features among samples. This approach helps:
- reduce noisy and irrelevant features,
- unify feature dimensions across datasets,
- improve computational efficiency,
- and potentially improve machine learning performance.

---

# Included Cancer Types

This dataset contains the following four cancer datasets:

| Cancer Type | Abbreviation | Description |
|---|---|---|
| Breast Invasive Carcinoma | BRCA | Breast cancer dataset |
| Colon Adenocarcinoma | COAD | Colon cancer dataset |
| Glioblastoma Multiforme | GBM | Brain tumor dataset |
| Ovarian Serous Cystadenocarcinoma | OV | Ovarian cancer dataset |

---

# Dataset Structure

```text
dataset/
├── BRCA/
│   ├── BRCA_mRNA_top.csv
│   ├── BRCA_miRNA_top.csv
│   ├── BRCA_Methy_top.csv
│   ├── BRCA_CNV_top.csv
│   └── BRCA_label.csv
│
├── COAD/
│   ├── COAD_mRNA_top.csv
│   ├── COAD_miRNA_top.csv
│   ├── COAD_Methy_top.csv
│   ├── COAD_CNV_top.csv
│   └── COAD_label.csv
│
├── GBM/
│   ├── GBM_mRNA_top.csv
│   ├── GBM_miRNA_top.csv
│   ├── GBM_Methy_top.csv
│   ├── GBM_CNV_top.csv
│   └── GBM_label.csv
│
└── OV/
    ├── OV_mRNA_top.csv
    ├── OV_miRNA_top.csv
    ├── OV_Methy_top.csv
    ├── OV_CNV_top.csv
    └── OV_label.csv
