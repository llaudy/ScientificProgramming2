# ScientificProgramming2

Assignment 2: Making Multivariate Statistics Reproducible

In this assignment, a dataset that is published on PubChem (PubChem Assay AID 624202) is used to build a partial least squares model in order to predict molecules their ability to activate the expression of BRCA1. A R Markdown notebook (Assignment_2.Rmd) is created to integrate both the code and output of the analysis. The notebook requires two .csv files that can be downloaded from this repository: the file called qsarSmallData.csv contains the molecule ID and and activity score in the first and second column respectively, and the file called descriptors.csv contains the molecule ID in the first column and various descriptors in the remaining columns. Users need to download these files and change the working directory in the script such that these data files can be accessed. The files are subset of the original data files, which can be obtained from PubChem.  During the analysis, 80% of the data will function as a training set to train the model during cross-validation, and 20% of the data is used to test the model's performance. The final plot provides an overview of how accurate the model predictions are. The R Markdown notebook can also be opened as an .html file (Assignment_2.html).







