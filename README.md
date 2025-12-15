# Modern Python Detector Data Analysis

A small end-to-end data analysis project demonstrating modern Python
tools applied to synthetic detector data.

## Motivation

This project showcases a modern, Python-based data analysis workflow
similar to those used in experimental physics and data science,
emphasizing clarity, reproducibility, and interpretability.

## Repository structure

- `notebooks/eda.ipynb` — data generation, cleaning, analysis, and plots
- `data/` — synthetic detector dataset (CSV)
- `README.md` — project overview

## Analysis summary

- Synthetic detector data with energy and momentum measurements
- Gaussian energy distribution with detector-like resolution
- Basic data cleaning via physical selection
- Visualization of distributions and correlations
- Statistical summary and conclusions

## How to run

Open the repository in GitHub Codespaces and execute the notebook
`notebooks/eda.ipynb`. All analysis is self-contained.

## Limitations and future work

- Negative energies are removed via a simple selection cut
- More realistic detector effects could be modeled
- Analysis could be extended to larger datasets or real data
