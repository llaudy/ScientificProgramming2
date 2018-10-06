# ScientificProgramming2

Assignment 2: Making Multivariate Statistics Reproducible

In this assignment, a dataset that is published on PubChem (PubChem Assay AID 624202) is used to build a partial least squares model in order to predict molecules their ability to activate the expression of BRCA1. A R Markdown notebook (Assignment_2.Rmd) is created to integrate both the code and output of the analysis. The notebook requires an .csv file that contains the molecule ID and and activity score in the first and second column respectively, as well as a .sdf file that contains the molecule ID in the first column and various descriptors in the remaining columns. Users need to set their working directory such that these data files can be accessed Both data files can be obtained from PubChem. During the analysis, 80% of the data will function as a training set to train the model during cross-validation, and 20% of the data is used to test the model's performance. The final plots provide an overview of how accurate the model predictions are.







