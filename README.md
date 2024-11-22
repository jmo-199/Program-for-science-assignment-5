# Program-for-science-assignment-5

# Gene Expression Analysis

## Name: Jason Moore 
## Programming Language: R  
## Date: 11/24/2024

---

## Description

This assignment performs an exploratory data analysis (EDA) on gene expression data to investigate differences between tumor and normal samples. It includes preprocessing steps, statistical calculations, and visualizations such as heatmaps, clustermaps, bar charts, and histograms. Key findings like differentially expressed genes (DEGs), fold changes, and chromosome-level insights are summarized.

---

## Required Files

1. **Gene_Expression_Data.xlsx**: Contains raw expression data for various genes across samples.
2. **Gene_Information.csv**: Provides metadata, including gene symbols and chromosomal locations.
3. **Sample_Information.tsv**: Includes sample metadata, linking each sample to its phenotype (tumor or normal).

---

## Required R Packages

The following R packages are used for data manipulation, statistical analysis, and visualizations:

- `tidyverse`: Comprehensive suite for data manipulation and plotting.
- `readxl`: To read Excel files.
- `reshape2`: For reshaping data into tidy formats.
- `ggplot2`: To create heatmaps, histograms, and other visualizations.
- `stats`: For hierarchical clustering.
- `gplots`: To generate enhanced heatmaps (optional).

To install the packages, run:
```R
install.packages(c("tidyverse", "readxl", "reshape2", "ggplot2", "gplots"))
```

---

## Instructions

1. **Preprocessing**:
   - Load and clean data from the provided files.
   - Update sample names in the gene expression data based on phenotypes.

2. **Exploratory Data Analysis**:
   - Generate histograms and bar charts to explore the distribution of DEGs across chromosomes and sample types.
   - Create heatmaps and clustermaps for gene expression visualization.

3. **Statistical Analysis**:
   - Compute average expression values for tumor and normal groups.
   - Calculate log2 fold changes to identify DEGs.

4. **Execution**:
   - Clone the repository or download all files.
   - Open the R script or R markdown file in RStudio.
   - Ensure the working directory contains the required files.
   - Execute each code block sequentially.

---

## Outputs

1. **Histograms**:
   - Distribution of DEGs by chromosome.
   - Segregation of DEGs by sample type (tumor vs. normal).

2. **Bar Charts**:
   - Percentage of genes upregulated in tumor samples vs. normal samples.

3. **Heatmaps**:
   - Visualize gene expression levels across samples.

4. **Clustermaps**:
   - Hierarchical clustering of gene expression for genes and samples.

5. **Summary Files**:
   - Log2 fold change results and a list of significant DEGs.

---

## Key Findings

- **Fold Change Analysis**: Most genes show modest changes; a few have significant upregulation or downregulation.
- **Chromosome Hotspots**: Certain chromosomes have a higher concentration of DEGs.
- **Expression Patterns**: Tumor samples generally exhibit higher expression levels than normal samples for key genes.
