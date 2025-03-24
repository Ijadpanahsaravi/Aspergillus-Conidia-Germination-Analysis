# Aspergillus Conidia Germination Analysis

This project contains a full data analysis pipeline for quantifying and modeling the germination dynamics of **Aspergillus** conidia over time using image-derived morphological features. The analysis includes classification of spore developmental phases and kinetic modeling using an asymmetric growth model.


## 🧪 What This Project Does

- **Processes** raw oCelloScope output for individual spores across time
- **Filters** out false positives (e.g., spores that shrink after appearing large)
- **Classifies** conidia into:
  - **R (Resting)** — minimal change
  - **S (Swollen)** — increased area but stable circularity
  - **G (Germinated)** — increased area and significant circularity change
- **Models** germination kinetics using an asymmetric model:
  - `Pmax` – maximum germinated/spores
  - `θ (theta)` – time at 50% germination
  - `d` – heterogeneity of the response
- **Exports** summary tables, model fits, confidence intervals, and RMSE



