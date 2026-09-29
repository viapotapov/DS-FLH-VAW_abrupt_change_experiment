# Gaussian-RKHS single-switch experiment

This repository contains the code reproducing the experiment from the paper 
**Viacheslav D. Potapov, and Dmitry B. Rokhlin**, *Dynamic Regret for Unconstrained Online Regression via the Follow-the-Leading-History Algorithm with Vovk–Azoury–Warmuth Forecasters*

## Files

- `gaussian_rkhs_single_switch.ipynb` — experiment notebook.
- `expected_summary.csv` — expected aggregate results.
- `requirements.txt` — Python dependencies.

## Reproduction

Install the dependencies and run all notebook cells from top to bottom.
No external data are required.

The final cell writes

- `gaussian_single_switch_records_lifetime_mu.csv`;
- `gaussian_single_switch_summary_lifetime_mu.csv`.

The latter can be compared with `expected_summary.csv`.

