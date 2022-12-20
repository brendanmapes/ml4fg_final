# Final project for Machine Learning for Functional Genomics (Columbia SEAS Fall '22)

This project was completed using Posit.cloud (formerly Rstudio Cloud). R code can be found in analysis.Rmd in rcloud_project. Necessary data are files also located within rcloud_project. 

Here we've attemped to improve upon work of Wang et al. in the MuSiC model (https://xuranw.github.io/MuSiC/index.html) for bulk RNA-seq cell type convolution. We believe incorporating a hierarchical tree with more specific classifications of cell types could improve model performance, allowing for lower level classification of cell types, data permitting. The work of Pfitzinger "Cluster Regularization via a Hierarchical Feature Regression" (https://arxiv.org/abs/2107.04831) provided a framework to regularize cell type proportion parameter estimates according to location within the hierarcchical tree. This strategy could be applied to the cell type hierarchies like used in MuSiC, and potentially improve model performance. More specific cell type classifications would provide more meaningful results for researchers analyzing cell type mixtures to better understand disease states and give more accurate prognoses to patients.


