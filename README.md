# Final project for Machine Learning for Functional Genomics (Columbia SEAS Fall '22)

This project was completed using Posit.cloud (formerly Rstudio Cloud). R code can be found in analysis.Rmd in rcloud_project. Necessary data are files also located within rcloud_project. 

Here we've attemped to improve upon work of Wang et al. in the MuSiC model (https://xuranw.github.io/MuSiC/index.html) for bulk RNA-seq cell type deconvolution. We believe incorporating a hierarchical tree with more specific classifications of cell types could improve model performance, allowing for meaningful descriptions of cell type mixtures, as data permits. The work of Pfitzinger "Cluster Regularization via a Hierarchical Feature Regression" (https://arxiv.org/abs/2107.04831) provided a framework to regularize parameter estimates with respect to hierarchical dendrogram representation of predictors in a linear model. This strategy could be applied to the cell type hierarchies like that already implemented in in MuSiC. Such an advancement would provide for more informative analysis of cell type mixtures in tissue samples, helping researchers better understand disase states and give more accurate prognoses to patients.


