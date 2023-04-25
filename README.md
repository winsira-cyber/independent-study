# independent-study
This is a tutorial for visualization of TCGA data  using available R packages such as:
1- heatmaps
2- corrplots
3- network plots
4- circlize
5- complexhetmap

The TCGA_eset dataset is part of the curatedOvarianData package in R. It contains gene expression data from The Cancer Genome Atlas (TCGA) project, specifically for ovarian cancer samples. This dataset includes 578 samples, with both tumor and normal (healthy) tissue samples, and contains expression data for 13,104 genes.
Some key aspects of the TCGA_eset dataset are:

Data type: It is an ExpressionSet object, which is a data structure from the Bioconductor project that stores gene expression data and associated metadata.

Gene expression data: The gene expression data can be accessed using the exprs() function. It returns a matrix with genes as rows and samples as columns.
Sample metadata: The pData() function can be used to extract the sample metadata, which includes information about the samples, such as the sample type (tumor or healthy).
Feature metadata: The fData() function can be used to extract the feature metadata, which includes information about the genes or probesets.
