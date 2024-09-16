# APT Detection Datasets: Analysis and Experiments

This repository contains Jupyter notebooks and supplementary materials used in the analysis and experimentation for the paper "Best practices for constructing APT datasets: recommendations for effective machine-learning-based research." The work focuses on exploring and evaluating Advanced Persistent Threat (APT) datasets to establish guidelines for effective machine-learning-based research.

## Directory Structure

```
├── Analysis
│   ├── DAPT2020_analysis.ipynb
│   ├── SCVIC_EDA.ipynb
│   ├── SCVIC_hotmap.ipynb
│   ├── SCVIC_sequences_analysis.ipynb
│   └── Unraveled_EDA.ipynb
├── Experiments
│   ├── SCVIC_Chains_integrity.ipynb
│   └── SCVIC_DAPT_cross_validation.ipynb
└── README.md
```

### Analysis
This folder contains exploratory data analysis (EDA) notebooks focused on various APT datasets:
- **DAPT2020_analysis.ipynb:** Analysis of the DAPT 2020 dataset.
- **SCVIC_EDA.ipynb:** Exploratory data analysis of the SCVIC dataset.
- **SCVIC_hotmap.ipynb:** Hotmap visualizations and analysis for SCVIC dataset patterns.
- **SCVIC_sequences_analysis.ipynb:** Sequence analysis of event chains in the SCVIC dataset.
- **Unraveled_EDA.ipynb:** EDA for the Unraveled dataset.

### Experiments
This folder contains experiments designed to test dataset integrity and cross-validation methodologies:
- **SCVIC_Chains_integrity.ipynb:** Integrity checking of APT sequence chains in the SCVIC dataset, examining the relationship between sequence integrity and detection effectiveness.
- **SCVIC_DAPT_cross_validation.ipynb:** Cross-validation experiments between SCVIC and DAPT datasets to assess model performance and generalization.


