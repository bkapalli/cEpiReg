# Gene Regulatory Landscape in Alzheimer's Disease

## Overview
This repository contains code and data related to the construction of a gene regulatory landscape in Alzheimer's Disease (AD). The project integrates multiple genomic datasets to identify regulatory interactions between transcription factors, cis-regulatory elements, and target genes.

## Objectives
- **Gene Regulatory Networks (GRNs):** Built using pySCENIC to link transcription factors (TFs) to target genes.
- **Cis-Regulatory Elements (CREs):** Mapped via ATAC-seq analysis.
- **eQTL Analysis:** Conducted cell-type–specific expression quantitative trait loci (eQTL) analysis to associate SNPs with genes and their regulatory elements.
- **Web Interface:** Developed an interactive platform for exploring regulatory interactions in Alzheimer's Disease.
- **Functionalities:** Enabled data retrieval, external database linking (UCSC Genome Browser, dbSNP), and interactive visualization tools (IGV, heatmaps, dropdown selections, CSV downloads).


## Usage
- Use the **search feature** to query genes, CREs, or SNPs.
- Apply **filters** for specific cell types or regulatory interactions.
- Click on gene links to access UCSC Genome Browser annotations.
- Download query results in **CSV format** for analysis.
