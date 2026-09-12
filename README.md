# BRG1 CUT&RUN Analysis

Computational analysis of published BRG1 CUT&RUN data to investigate chromatin occupancy during the naïve-to-primed transition in mouse embryonic stem cells.

## Biological Question

How does BRG1 chromatin occupancy change between naïve and primed mouse embryonic stem cells, and which stage-specific BRG1-associated regions are affected by deletion of the BRG1 AT-hook?

## Dataset

- **GEO accession:** GSE207788
- **Organism:** *Mus musculus*
- **Assay:** BRG1 CUT&RUN
- **Cell system:** Mouse embryonic stem cells

## Project Overview

This project re-analyses publicly available BRG1 CUT&RUN data from a study investigating stage-specific SWI/SNF recruitment during early mammalian development.

The analysis will focus on:

1. Characterising the BRG1 occupancy landscape in naïve and primed ESCs
2. Identifying stage-specific and shared BRG1-associated regions
3. Examining the effect of BRG1 AT-hook deletion on BRG1 occupancy
4. Annotating and biologically interpreting regions showing differential BRG1 association

## Analysis Workflow

```text
BRG1 CUT&RUN data
        ↓
Metadata and data organisation
        ↓
Quality assessment
        ↓
BRG1 signal / peak analysis
        ↓
Naïve vs Primed comparison
        ↓
Stage-specific BRG1 regions
        ↓
WT vs AT-hook deletion
        ↓
Genomic annotation
        ↓
Biological interpretation
