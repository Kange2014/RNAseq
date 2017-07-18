# RNAseq

Following bcbio-nextgen RNAseq workflow, qc-summary.Rmd generates a report of the run:

    library(knitr)
    library(rmarkdown)
    render('qc-summary.Rmd')

Outputs include qc summary of the RNAseq data, alignment metrics, and so on. In addition, it will also use DESeq2 to do differential expression analysis, as well as using topGO to run gene enrichment analysis
