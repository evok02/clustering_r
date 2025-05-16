
# Clustering in R: K-Means, Hierarchical, and Density-Based Methods

This repository presents a simple home project written in R that demonstrates the differences between k-means, hierarchical, and density-based clustering algorithms.

## Overview

The project includes an R Markdown file (`clustering_training.Rmd`) and its corresponding HTML output (`clustering_training.html`) that:

- Load and preprocess a dataset
- Apply k-means clustering
- Apply hierarchical clustering
- Apply density-based clustering (e.g., DBSCAN)
- Visualize and compare the clustering results

## Getting Started

### Prerequisites

Ensure you have R installed on your system. The following R packages are required:

- `cluster`
- `factoextra`
- `dbscan`
- `ggplot2`
- `dplyr`

You can install them using:

```r
install.packages(c("cluster", "factoextra", "dbscan", "ggplot2", "dplyr"))
```

### Running the Analysis

1. Clone this repository:

   ```bash
   git clone https://github.com/evok02/clustering_r.git
   ```

2. Navigate to the project directory:

   ```bash
   cd clustering_r
   ```

3. Open `clustering_training.Rmd` in RStudio or your preferred R environment.

4. Knit the R Markdown file to generate the HTML output or run the code chunks interactively to explore the clustering methods.

## Project Structure

- `clustering_training.Rmd` – Main R Markdown file containing the analysis.
- `clustering_training.html` – Rendered HTML output of the analysis.
- `data/` – Directory containing the dataset used for clustering.

## Acknowledgments

This project is inspired by the desire to understand and compare different clustering techniques in R.
