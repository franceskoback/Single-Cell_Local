## Workflow for Single-Cell Analysis Local Version

To use this script:

git clone https://github.com/franceskoback/Single-Cell_Local

Add your own inputs to the data and filtered_featured_bc folders. You will need the paths to 
filtered_feature_bc_matrix
aggregation.csv
cell_cycle_genes.txt  

Prerequisites for this pipeline involve installing RStudio (https://www.rstudio.com/products/rstudio/download/) and installing the packages required in each of these R Notebooks (https://www.datacamp.com/community/tutorials/r-packages-guide) 

Use these notebooks in this order:
1. Step1_Preprocessing.Rmd 
2. Step2_Clustering_Filtering.Rmd

In each of these, search (command F) for the term USER_EDIT. These outline which lines you'll need to edit for your specific data and how to go through the process of analyzing what these scripts will output. If you have any questions on this, please do not hesitate to reach out.

All of this code was modified from Angelo Pelonero's code for this pipeline 
