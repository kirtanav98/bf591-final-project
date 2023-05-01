# bf591-final-project

Final project for BF591—creation of an R Shiny application for various bioinformatics analyses.

BF591 is a course fpcusing on bioinformatic analyses with the R programming language. We develop functions for a wide variety of bionformatic analyses in R.

What the app contains:

Dataset: mRNA-Seq Expression profiling of human post-mortem BA9 brain tissue for Huntington’s Disease and neurologically normal individuals (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE64810).

Sample Information Exploration (samples.R):

Input - Sample Information Table (CSV)

a. Sample Information Summary Table

b. Sample Information Table

c. Sample Information Distribution Plots

Counts Matrix Exploration (counts.R)

Input - Normalized Counts Matrix (CSV)

a. Count Filtering Summary Table

b. Diagnostic Scatterplots

i. Median Count vs. Variance

ii. Medican Count vs. Number of Non-Zero Samples

c. Clustered Heatmap of Counts vs. Samples

d. PCA Biplot of User-Selected PCs

Differential Expression Analysis (diff_expr.R)

Input - Differential Expression Results (CSV)

a. Volcano Plot with User-Select Adjusted P-Value Threshold

b. Table of DEGs with Significant Adjusted P-Value

Gene Set Enrichment Analysis (gsea.R)

Input - FGSEA Results (C2: Canonical Pathway) (CSV)

a. Barplot of Top Pathways by Normalized Enrichment Score (NES)

b. Downloadable Table of Significantly Enriched Pathways

c. Scatterplot of NES vs. -log10(Adjusted P-Value)
