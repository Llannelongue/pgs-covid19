---
permalink: /pgs/
---
A lot about PGSs here.

All PGSs files have the following format:

| rsid | chr | pos | effect_allele | other_allele | EN_Effect |
| --- | --- | -- | --- | --- | --- |
| rs116576188 | 6 | 31296369 | C | A | 0.015351 |
| rs568630420 | 6 | 31315587 | T | G | 0.0 |

With the following columns:

| `rsid` | this is...
| `chr` |
| `pos` |
| `effect_allele` |
| `other_allele` |
| `EN_Effect` |

An easy way to calculate the PGS on a new cohort is to use PLINK2, here is an example:

```shell
> PLINK --ddd
```