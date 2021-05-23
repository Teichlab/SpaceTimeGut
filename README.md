# SpaceTimeGut

Analysis notebooks for preprint "Cells of the human intestinal tract mapped across space and time" (https://www.biorxiv.org/content/10.1101/2021.04.07.438755v1).

For each dataset, we processed data from cellranger filtered quantification matrix and applied SoupX and Scrublet for ambient RNA and doublet removal. The standard scanpy (v1.4) and clustering pipelines were preformed for fetal, pediatric and adult datasets separatelly. The datasets were then integrated using BBKNN for batch correction across samples. Clustering and annotation was done in the integrated dataset manually guided by known marker genes.

The analysis code uses publicly available scanpy_scripts.
