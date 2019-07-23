# Junction balance analysis reveals long range structure of cancer genomes
This repository contains R scripts and datasets for reproducing the figures used in JaBbA paper.

Junction Balance Analysis (JaBbA, https://github.com/mskilab/JaBbA) is a mixed integer programming solver for reconstructing copy number annotated rearrangement graphs from whole genome sequencing (WGS) data.

# Please cite this
[FIT IN OUR URL/DOI!!]

# Prepare for running
`git fork github.com/xtYao/JaBbA_alpha ./ && cd JaBbA_alpha && make`

# Figures
## Benchmarking (Figure 2/ Supplementary Figure 2)
`Rscript figure2/figure2.R`

## (Co-)amplification (Figure 3 / Supplementary Figure 3 benchmarking)

## Fusion genes (Figure 4 / Supplementary Figure 4)

## Enhancer hijacking (Figure 4 / Supplementary Figure 4)

## Loose ends (Figure 5 / Supplementary Figure 5)

## Validation by long range technology (Figure 6 / Supplementary Figure 6)

# dependencies
- R(>3.5)
- gGnome
- GxG
- ggplot2
