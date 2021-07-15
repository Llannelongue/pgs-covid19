---
<!-- permalink: /pgs/ -->
permalink: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/
title: About Genetic Scores
---


## What is a genetic score ?

A genetic score, also called a polygenic score (PGS), polygenic risk score (PRS), genetic risk score, or genome-wide score, is a number that summarises the estimated effect of many genetic variants (usually SNPs) on an individual's phenotype, typically calculated as a weighted sum of trait-associated alleles [(wikipedia)](https://en.wikipedia.org/wiki/Polygenic_score).


## What does a genetic score model look like in the Atlas?
A genetic score model file presents in the following format:

| rsid | chr | pos | effect_allele | other_allele | effect |
| --- | --- | -- | --- | --- | --- |
| rs116576188 | 6 | 31296369 | C | A | 0.015 |
| rs568630420 | 6 | 31315587 | T | G | 0.02 |
| ... |  | |  |  |  |
| rs78630340 | 6 | 31342334 | A | T | 0.05 |

where:

| `rsid` | rsID
| `chr` |  Chromosome code
| `pos` | Base-pair coordinate (GRCh37)
| `effect_allele` | Effect allele with regard to the dosage of a variant
| `other_allele` | The other allele
| `effect` | Effect size of the variant


## How do we calculate genetic scores with the genetic score model of a trait?
An easy way to calculate genetic scores of a new cohort is to use [PLINK2](https://www.cog-genomics.org/plink/2.0/score). Here is an example:

```shell
>plink2
--bfile ${bed_file}
--score ${model_file} 1 4 6 header list-variants cols=scoresums
--out  ${results}
```
where:

| `bed_file` | Plink bed file of genetic data in a new cohort
| `model_file` |  Path for a genetic model file downloaded from the Atlas
| `results` | Result file path

 
