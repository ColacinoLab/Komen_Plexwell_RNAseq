# Komen Plexwell Bulk RNA-seq Experiment
In this workflow, we use _Plexwell seqWell©_ library preparation to perform bulk RNA-sequencing analysis on conditionally reprogrammed, patient-derived cell lines from _Susan G. Komen_ tissue donors. Starting with _featureCounts_ mapped at the gene-level, we perform data pre-processing, exploratory analyses, and finish off with differential expression analyses and gene set pathway testing/co-expression network analysis. 
  
Base **_R_** and the **_edgeR_** package are used to import, filter, and organize the raw counts and to perform data reduction visualizations and quality control checks. We perform downstream differential expression analysis using the **_edgeR_** quasi-likelihood pipeline (_edgeR-quasi_) and use **_KEGG_**, **_goana_**, **_CAMERA_** and **_fry_** for competitive and self-contained gene set testing, respectively. 

By doing so, we seek to elucidate the effects of environmental chemical exposures on gene expression and potential molecular mechanisms of action on human breast cancer outcomes. In particular, our findings lend insight to gene expression changes associated with dysregulation in stem-cell biology such as cellular differentiation states and developmental trajectories. 

&nbsp;

This pipeline is inspired by _[Chen et al. 2020](https://bioconductor.org/packages/release/workflows/vignettes/RnaSeqGeneEdgeRQL/inst/doc/edgeRQL.html#camera-gene-set-enrichment-analysis)_, _[Law et al. 2018](https://bioconductor.org/packages/release/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html)_, and Justin Colacino's '_Komen plexwell processing.R_' script (unpublished).
  
![](https://sph.umich.edu/news/2021posts/images/sph-building-exterior.jpg)

_**[© 2022 Colacino Lab](https://www.colacinolab.com/)**_
