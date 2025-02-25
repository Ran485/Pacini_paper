# Integrated analysis of Xist upregulation and X-chromosome inactivation with single-cell and single-allele resolution
Guido Pacini, Ilona Dunkel, Norbert Mages, Verena Mutzel, Bernd Timmermann, Annalisa Marsico*, Edda G Schulz*

Data and code used to perform preprocessing and analysis of scRNA-seq and bulk RNA-seq data of differentiating female embryonic stem cells. (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE151009)

![image](https://user-images.githubusercontent.com/47419513/113004832-3072dd00-9174-11eb-8da7-7fa436f83b03.png)

## Abstract
To ensure dosage compensation between the sexes, one randomly chosen X chromosome is silenced in each female cell in the process of X-chromosome inactivation (XCI). XCI is a model for cellular decision making and epigenetic gene regulation. The random cell-autonomous nature of XCI however has so far prevented its chromosome-wide investigation in its endogenous context without genetic perturbation. Here we use allele-specific single-cell RNA-sequencing to assess the onset of random XCI with high temporal resolution in differentiating mouse embryonic stem cells, and develop dedicated analysis approaches. We find that XCI is initiated on both chromosomes in a subset of cells, but reverted to the final mono-allelic state once gene silencing is established. By exploiting the heterogeneity of XCI onset, we identify Nanog as its main trigger and discover additional genes that might control upregulation of Xist, the master regulator of XCI. Finally, we show that genetic variation between different mouse strains modulates the XCI process at multiple levels, and validate these findings through an orthogonal experimental approach. We thus draw a detailed picture of how XCI is initiated and the experimental and computational strategies we have developed here will now allow us to profile random XCI in more physiological contexts, including primary human cells in vivo.

## Description
The "alignment/" and "analysis/" directories respectively include all the input data and scripts necessary to reproduce the scRNA-Seq reads alignment and gene expression quantification, and all the analyses and figures included in the manuscipt (https://www.biorxiv.org/content/10.1101/2020.07.20.211573v1). In each directory, a README.md file describes the softwares and dependencies needed to reproduce the data analyses.
