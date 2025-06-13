# GSE Analysis of FUSIL Paralogues

This R Markdown notebook performs Gene Set Enrichment Analysis (GSE) across FUSIL gene categories using human paralogues, integrating GO terms and Reactome pathways.

## ?? Requirements

- R (= 4.0)
- R packages:
  - `GO.db`
  - `org.Hs.eg.db`
  - `biomaRt`
  - `ReactomePA`
  - `enrichplot`
  - `clusterProfiler`
  - `tidyverse`
  - `knitr`

To install all required packages:

```r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
  install.packages("BiocManager")
}
BiocManager::install(c("GO.db", "org.Hs.eg.db", "biomaRt", "ReactomePA", "enrichplot", "clusterProfiler"))
install.packages("tidyverse")


