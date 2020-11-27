---
title: "Selecting variants and building the PGS"
---

# QC step

Variants to include in the PGS for each traits were selected with several steps.

For all phenotypes, only variants matching the following criteria were kept:
- Minor Allele Frequency (MAF) > 0.5%
- biallelic SNPs
- not palindromic SNPs (A/T or G/C)
- LD-thinning at r2 > 0.8
- p-value < 0.001

Furthermore, for proteins traits, all SNPs in the cis-region of the encoding gene(s) were included.

# Training PGS
The training pipeline followed [Xu. et al.](https://www.biorxiv.org/content/10.1101/2020.02.17.952788v1) (preprint).

All PGSs were trained on the INTERVAL cohort. 
