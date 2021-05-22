This repository contains the scripts (R Markdown files) that were used for the analyses accompanying the manuscript "Functional genomics analysis identifies T- and NK-cell activation as a driver of epigenetic clock progression".

In this manuscript, we describe how epigenetic clocks, which are DNA-methylation-based predictors of calendar age, are infliuenced by proportions of naive and activated T-cells and NK-cells in a biological sample.

The scripts were run in order (from 1 to 10). The purpose of each script is as follows:

Script 1: create an annotation file for all CpGs on teh Illumina 450K array.
Script 2: gather the CpGs included in each of the 4 investigated epigenetic clocks.
Script 3: prepare the DNA-methylation and gene expression data from 3,132 whole blood samples.
Script 4: apply the clocks to predict age of the 3,132 samples.
Script 5: compare the clocks in terms of age prediction and correlation of methylation values.
Script 6: analyze the enrichments for genomic annotations of the clock CpG sets.
Script 7: run a TWAS investigating the association between clock CpG methylation and gene expression.
Script 8: run the R package "bacon" to correct the TWAS-associations for bias and inflation.
Script 9: analyze the results of the TWAS.
Script 10: analyze the effect of blood cell types on clock CpG methylation, gene expression, and age prediction.
