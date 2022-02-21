# BrainOrganoids

This is a repository consists of multiple projects contributing to the detection of cell type specific enhancer - promoter pairs during human brain development. 

### The repository is parted into following sections: 
  1. Peak calling using SCAFE
  2. Generation of cell clusters using Seurat
  3. Generation of cell type trajectories using Monocle 
  4. Enhancer - promoter detection using Cicero
  5. Validation of Enhancer - promoter pairs using public data 


### Description of projects
1. Peak calling using SCAFE
This function is more sensitive in detection lowly expressed peaks such as of enhancer RNAs. 

2. Generation of cell clusters and cell cluster annotation using most differentially expressed genes
In order to identify cell type specific enhancer - promoter pairs we used Seurat to cluster the cells and annotated the clusters using the 
top 20 differentially expressed genes from each cluster. 

3. Generation of cell lineages using monocle3
In order to study the cell differentiation process, we used monocle3 to create a pseudotime to identify co-dynamically expressed enhancer-
promoter pairs during lineage differentiaiton. 

4. Validation of co-dynamically expressed enhancer-promoter pairs using Cicero
Cicero predicts genomic interactions using a graphical lasso. We used this in silico prediction to validate our enhancer-promoter pairs

5. Validation of enhancer-promoter pairs using epigenomic data
After having dynamically co-expressed and also in silico validated pairs, we wanted to know if these enhancer-promoter pairs can be further 
validated using public available epigenomic data. 




