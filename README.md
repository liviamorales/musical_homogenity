# Musical Homogeneity in Popular Music (1950–2010)

This repository contains the data, code, and final paper for an empirical analysis of whether mainstream popular music has become more homogeneous over time. The analysis constructs within-genre dispersion measures using Spotify audio features and evaluates time trends using weighted least squares regressions with genre controls and robustness checks.

## Paper

📄 **Final paper:**  
[`Musical_Homogeneity_Analysis.pdf`](paper/Musical_Homogeneity_Analysis.pdf)

## Repository Structure

- `01_exploration.ipynb` — main analysis notebook
- `data/` — input dataset (Kaggle source below)
- `outputs/` — generated figures and tables
- `paper/` — final written paper

## Data Source

**Top 10000 Spotify Songs (1950–Now)**  
Kaggle dataset (CC0: Public Domain)  
https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now

## Reproducibility

Run `01_exploration.ipynb` top-to-bottom to reproduce all figures and tables used in the paper.  
Key libraries: pandas, numpy, matplotlib, statsmodels.
