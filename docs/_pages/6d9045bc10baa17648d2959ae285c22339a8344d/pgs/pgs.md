---
permalink: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/
title: About the Genetic Scores
---

## What is Genetic Score ? 

A lot about PGSs here.


## Genetic Score Models in the Atlas ? 
All PGSs files have the following format:

| rsid | chr | pos | effect_allele | other_allele | Effect |
| --- | --- | -- | --- | --- | --- |
| rs116576188 | 6 | 31296369 | C | A | 0.015 |
| rs568630420 | 6 | 31315587 | T | G | 0.02 |
| ........... |  | |  |  |  |
| rs78630340 | 6 | 31342334 | A | T | 0.05 |

With the following columns:

| `rsid` | this is...
| `chr` |
| `pos` |
| `effect_allele` |
| `other_allele` |
| `EN_Effect` |


## How to calculate genetic scores ? 
An easy way to calculate the PGS on a new cohort is to use PLINK2, here is an example:

```shell
> PLINK --ddd
```