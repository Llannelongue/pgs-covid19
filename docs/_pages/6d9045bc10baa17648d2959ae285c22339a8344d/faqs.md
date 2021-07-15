---
Title: "FAQs" 
layout: splash
---


<br>
# Genetic score development
<p> 
<details>
  <summary><b>What method was used for genetic score development and why?</b> </summary>
   The machine learning method Bayesian Ridge (BR), that based on individual-level genotype data, was used to construct genetic scores of biomelecular traits in the Atlas. The selection of BR is based on the results in <a href="https://www.biorxiv.org/content/10.1101/2020.02.17.952788v1">one of our previous studies</a> that benchmarked the performance of a variety of representative genetic scoring methods for the construction of numerous continuous molecullar traits, and demonstrated BR was the top performing method in terms of both efficacy and efficiency.
  
</details> 
</p>

<p> 
<details>
  <summary><b>How were the genetic variants (i.e. SNPs) selected before feeding to the genetic scoring method?</b> </summary>
  To ensure the generalizability of genetic score models when applied to other cohorts, a variant filtering step was first performed for all the traits considered, which applied a MAF threshold of 0.5% and excluded all multi-allelic variants as well as ambiguous variants (i.e. A/T, G/C). A follow-up LD thinning step was carried out at an r<sup>2</sup> threshold of 0.8 on all the variants, which aims to remove a certrain level of LD dependencies among variants and reduce the computational burden of genetic scoring method. The remaining variants were then filtered at the genome-wide significance threshold of 5e-8 (based on their GWAS summary statistics conducted on the INTERVAL training samples) for each trait. 
</details>
</p>

<br>

# Genetic score validation
<p> 
<details>
  <summary><b>How was internal validation done?</b> </summary>
  <a href="https://www.inouyelab.org/">Coming soon</a>
</details>
</p>

<p> 
<details>
  <summary><b>How was external validation done?</b> </summary>
  <a href="https://www.inouyelab.org/">Coming soon</a>
</details>
</p>