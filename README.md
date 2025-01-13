# antiPD1_predictive_mod

Scripts and data necessary to support the research findings.

This repository provides sample code to reproduce figures and all the findings from Science Advances Tarantino et al. Genomic heterogeneity and ploidy identify patients with intrinsic resistance to PD-1 blockade in metastatic melanoma, with associated source data (supplemental data and tables from the paper).

Please contact the corresponding or the first author for any questions, comments, or concerns regarding the paper in general.

giuseppe_tarantino@dfci.harvard.edu
David_Liu@DFCI.HARVARD.EDU 

subfolder input with the data to reproduce the analysis:
- The supplementary tables of the paper (1-5)
- TCGA melanoma, the data from TCGA, specifically reanalyzed data have been obtained JR. Conway et al. from https://doi.org/10.1038/s41588-020-00739-1 (opens in new window)
- TotalCN_circos to reproduce the circos plots

subfolder <b>*scripts*</b> with the code to reproduce the main figures:

Figure1.Rmd <p>
Figure2.Rmd <p>
Figure3.Rmd <p>
Figure4.Rmd <p>
Figure5.Rmd <p>

useful_functions.R functions used to plot confusion matrix and decision boundaries
