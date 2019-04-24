# muscData
Multi-sample multi-group scRNA-seq data

The `muscData` package is aimed at providing a set of publicly available single-cell RNA sequencing (scRNA-seq) datasets with complex experimental designs, i.e., datasets that contain multiple samples (e.g., individuals) measured across multiple experimental conditions (e.g., treatments), formatted into `SingleCellExperiment` (SCE) Bioconductor objects. All provided SCEs contain *unfiltered* raw counts, and any gene and cell metadata available from the original data source.

Currently available datasets:

- `Kang18_8vs8`:  
10x droplet-based scRNA-seq PBMC data from 8 Lupus patients before and after 6h-treatment with INF-beta [[source](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE96583), [reference](10.1038/nbt.4042)]

- `Sala19_2vs2`:  
10x scRNA-seq data from chimeric mice embryos in which Tal1-knockout (KO) embryonic stem cells were injected into a wild-type (WT) blastocyst (2 samples per group) [[source](https://content.cruk.cam.ac.uk/jmlab/chimera_tal1_data), [reference](https://www.ncbi.nlm.nih.gov/pubmed/30787436)]
