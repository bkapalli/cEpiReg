# Gene Regulatory Landscape in Alzheimer's Disease

This repository contains code and data for constructing a gene regulatory landscape in Alzheimer's Disease (AD). The project integrates multiple genomic datasets to identify regulatory interactions between transcription factors, cis-regulatory elements (CREs), and target genes using state-of-the-art genomic tools and workflows.

### ATAC-seq Data Processing & CRE Integration
Obtained ATAC-seq data from Alzheimer's disease samples. Processed the data using a Snakemake workflow to ensure reproducibility and scalability. CRE Data from Epimap [Epimap Mark Matrices](https://personal.broadinstitute.org/cboix/epimap/mark_matrices/) ENCODE [Human cCRE (hg38)(https://screen.encodeproject.org) Utilized BEDTools `intersect` to combine datasets. Applied HOMER for peak annotation to facilitate further analysis.

Curated CRE data from ENCODE. Incorporated eQTL data from [this Nature publication](https://www.nature.com/articles/s41593-022-01128-z). Developed a distance linking score to connect CREs with target genes via SNPs, enhancing our understanding of regulatory relationships.


