# Amazon ML Challenge 2026 - Business Entity Resolution

Team repository for building an end-to-end Machine Learning pipeline for cross-source entity resolution.

## Pipeline Workflow
1. **01_preprocessing.ipynb** — Data loading and robust text normalization (Name, Address, Country).
2. **02_blocking.ipynb** — Fast candidate generation and shortlisting (`candidate_pairs.tsv`). *(In Progress)*
3. **03_feature_engineering.ipynb** — Pairwise string similarity features and metric extraction. *(Upcoming)*
4. **04_modeling_and_submission.ipynb** — LightGBM/XGBoost classification, $F_{0.5}$ threshold tuning, and final predictions (`matching_results.tsv`). *(Upcoming)*

## Workspace Setup
* Data files and outputs are managed collaboratively via a shared Google Drive workspace.
* Code and notebooks are version-controlled here on GitHub.
