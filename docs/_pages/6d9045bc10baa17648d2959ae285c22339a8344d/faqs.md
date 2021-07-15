---
Title: "FAQs" 
layout: splash
---



<br>
# General questions
<p> 
<details>
  <summary><b>What can we do with these genetic score models?</b> </summary>
These genetic score models can be used to predict levels of biomelecular traits in genotyped cohorts. The predicted levels can be associated with complex phenotypes, which offers as a useful tool to investigate the molecular underpinnings of these phenotypes. The predicted levels can also allow integrative analyses with other available biomelucular traits in the cohort.
  
</details> 
</p>



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

<p> 
<details>
  <summary><b>How were traits selected for genetic score development in each platform?</b> </summary>
  We selected traits that have at least one genetic variant with p-value < 5e-8 in their GWAS (based on the INTERVAL training samples) to allow running of the genetic scoring method.
</details>
</p>

<br>

# Genetic score validation
<p> 
<details>
  <summary><b>How was the internal validation done?</b> </summary>
  The INTERVAL training samples of a trait were randomly and equally partitioned to five portions, from which any four portions are used to learn a genetic score model of the trait with Bayesian ridge regression, and the model’s performance was then tested on the remaining 20% of INTERVAL training samples, i.e. calculating the r<sup>2</sup> score and Spearman correlation coefficient between the predicted genetic scores and the actual levels of the trait for these samples.
</details>
</p>

<p> 
<details>
  <summary><b>How was the external validation done?</b> </summary>
  The genetic score model trained with INTERVAL training samples for a trait was used to calculate genetic scores of the validation samples (external cohorts or withheld INTERVAL samples). Then r<sup>2</sup> score and Spearman correlation coefficient were calculated using the predicted scores of these samples against their acutal trait levels.
</details>
</p>