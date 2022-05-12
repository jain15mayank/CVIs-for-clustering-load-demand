# CVIs-for-clustering-load-demand

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

> Jain, M., Jain, M., AlSkaif, T. and Dev, S.(2022). Which internal validation indices to use while clustering electric load demand profiles? *under review*, 2022

### Executive summary
Clustering is a basic requirement for most analyses on electricity load demand profile datasets. Different algorithms often generate varied clustering results. In absence of ground truth labels, several cluster validation indices (CVI) exist to compare these results and choose the best clustering. However, the issue subsists because these indices might also recommend distinct algorithms. This work shows that the choice of appropriate CVI depends upon the characteristics of the concerned
load demand profile data under study. It provides a comprehensive analysis of the different CVIs response upon changes in data characteristics. The paper finally recommends the indices that ought to be (or not to be) used for a dataset if certain data characteristics are emerging in the clustering results.

### Code
All codes are written in `python3`.
+ `pre-processing.ipynb`: Performs the pre-processing of the data file.
+ `clustering_main.ipynb`: Performs the clustering and CVI impact evaluation study for different data characteristics.
