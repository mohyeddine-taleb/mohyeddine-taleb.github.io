# TSPO Conservation Analysis

## Overview
This notebook demonstrates a bioinformatics analysis of the **Translocator Protein (TSPO)**
across multiple species, directly connecting PhD thesis work to standard NGS/bioinformatics
concepts used in industry and academia.

## What the Notebook Does
1. Fetches TSPO protein sequences from NCBI (Human, Rat, Mouse, *B. cereus*)
2. Performs pairwise global alignments using **Biopython PairwiseAligner**
3. Computes a **percent identity matrix** visualised as a heatmap
4. Generates a **conservation profile plot** per residue position
5. Highlights the **Ala147Thr polymorphism (rs6971)** and explains its clinical impact

## Requirements
```bash
pip install biopython matplotlib seaborn pandas numpy
```

## Key Tools Used
| Tool | Purpose |
|---|---|
| **Biopython (Entrez)** | Fetch sequences from NCBI databases |
| **Biopython (PairwiseAligner)** | Global pairwise sequence alignment |
| **pandas** | Tabular data management |
| **matplotlib / seaborn** | Visualisation (heatmap, conservation plot) |

## NGS Relevance
The concepts demonstrated here map directly to core NGS pipeline steps:

| This notebook | NGS pipeline |
|---|---|
| Sequence alignment | Read alignment (BWA, Bowtie2, STAR) |
| Percent identity | Mapping rate / alignment quality |
| Conservation scoring | Variant frequency analysis |
| Position annotation | Variant annotation (SnpEff, VEP) |
| Biological interpretation | Clinical variant classification |

## Author
**Mohyeddine Taleb**  
PhD — Biology, Chemistry, Health  
ICMR – CNRS 7312, University of Reims Champagne-Ardenne  
[mohyeddine-taleb.github.io](https://mohyeddine-taleb.github.io)
