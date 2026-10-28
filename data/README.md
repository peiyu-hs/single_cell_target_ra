# Data

This project uses publicly available single-cell RNA-seq data from the AMP Rheumatoid Arthritis Phase 1 study.

The analyzed expression matrix contains **5,265 quality-controlled cells and 29,165 genes**. Expression values were processed by the original study as `log2(CPM + 1)`.

Large source data files are intentionally excluded from this repository.

## Files used locally

Place the following files in this directory before running the analysis notebook:

- `exprMatrix.tsv` — processed gene-expression matrix
- `meta` — cell-level cluster metadata

## Original Study and Resources

**Publication**

Zhang F, Wei K, Slowikowski K, et al. *Defining inflammatory cell states in rheumatoid arthritis joint synovial tissues by integrating single-cell transcriptomics and mass cytometry.* Nature Immunology. 2019;20:928–942.  
DOI: 10.1038/s41590-019-0378-1

**Original analysis source code**

https://github.com/immunogenomics/amp_phase1_ra

**AMP RA Phase I data portal**

https://immunogenomics.io/ampra/

**Data repository**

ImmPort study accession: `SDY998`

## About This Repository

This repository contains an independent Python/Scanpy reanalysis focused on cell-state transcriptional programs, ranked gene-set enrichment, and therapeutic target prioritization.

The original study's published cell-state annotations and processed expression data are used as the starting point; the target-prioritization workflow in this repository is a separate downstream analysis.