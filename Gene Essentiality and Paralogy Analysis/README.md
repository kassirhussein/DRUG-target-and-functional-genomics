# FUSIL Analysis: Exploring Gene Viability and Paralogy Datasets

This project investigates gene essentiality using FUSIL categories and gene paralogy data in human genes.

## ?? Requirements

- **R** (4.0+)
- R packages used:
  - `tidyverse`
  - `readxl`
  - `writexl`
  - `ggalluvial`
  - `reshape2`
  - `biomaRt`
  - `knitr`
  - `stringr`

Install missing packages:

```r
install.packages(c("tidyverse", "readxl", "writexl", "ggalluvial", "reshape2", "stringr"))
if (!requireNamespace("BiocManager", quietly = TRUE))
  install.packages("BiocManager")
BiocManager::install("biomaRt")

