---
layout: splash

<!-- permalink: /6d9045bc10baa17648d2959ae285c22339a8344d/ -->

title: " <br/>OMICSPRED: An atlas of genetic scores for prediction of multi-omics data"
excerpt: "  <br/>  <br/> "
header:
  overlay_image: /assets/images/home_banner.png

feature_row_pgs:
  - image_path: /assets/images/Somalogic_logo_simple.png
    title: "Proteomics (plasma)"
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Somalogic-pgs/ -->
    url: /pgs/Somalogic-pgs/
    excerpt: "2,384 protein genetic scores, validated on the [FENLAND cohort](https://www.mrc-epid.cam.ac.uk/research/studies/fenland/)."
  - image_path: /assets/images/Olink_logo_simple.png
    title: "Proteomics (plasma)"
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Olink-pgs/ -->
    url: /pgs/Olink-pgs/
    excerpt: "308 protein genetic scores, validated on the [NSPHS cohort](https://pubmed.ncbi.nlm.nih.gov/20568910/) and [ORCADES cohort](https://www.ed.ac.uk/viking/about-us/our-studies)."
  - image_path: /assets/images/Metabolon_logo_simple.png
    title: "Metabolomics (plasma)"
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Metabolon-pgs/ -->
    url: /pgs/Metabolon-pgs/
    excerpt: "726 metabolite genetic scores, validated on a withheld subset of INTERVAL."
  - image_path: /assets/images/Nightingale_logo_simple.png
    title: "Metabolomics (serum)"
    url: /pgs/Nightingale-pgs/
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Nightingale-pgs/ -->
    excerpt: "141 metabolite genetic scores, validated on [UK Biobank](https://www.ukbiobank.ac.uk/)."
  - image_path: /assets/images/RNAseq_logo_simple.png
    title: "Transcriptomics (whole blood)"
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/GE-pgs/ -->
    url: /pgs/GE-pgs/
    excerpt: "13,668 gene expression genetic scores, validated on a withheld subset of INTERVAL."


feature_study_intro:
  - image_path: /assets/images/interval-logo.png
    excerpt: "INTERVAL is a randomised trial of approximately 50,000 healthy blood donors, which aims to study the safety of varying frequency of blood donation. Between June 2012 and June 2014, the study recruited about 25,000 men and about 25,000 women aged 18 years and older (median 44 years of age) at 25 NHS Blood and Transplant (NSHBT) blood donation centres across England. The  collection  of  their  blood  samples  for  research  purposes  was  done  using  standard  protocols and  has  been  extensively [described  previously](http://www.intervalstudy.org.uk/files/2019/11/Moore-et-al.-Trials-2014.pdf)."
    btn_class: btn--primary



feature_phenotype:
  - image_path: /assets/images/UKB_largeFeature.png
    title: "Associations with phenotypes in UK biobank"
    <!-- url: /6d9045bc10baa17648d2959ae285c22339a8344d/Application/pgs_ukb_disease_associations/ -->
    url: /Application/pgs_ukb_disease_associations/
    excerpt: "Genetic scores in OMICSPRED have been applied to [UK biobank](https://www.ukbiobank.ac.uk/) to test for associations with various complex phenotypes."

gallery_logos:
  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/DPHPC_gallery.png
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/HDRuk_gallery.png
  - url: "https://baker.edu.au"
    image_path: /assets/images/Baker_gallery.png

---
# Summary
---
OMICSPRED is a resource for predicting multi-omics data (proteomics, metabolomics, transcriptomics etc) directly from genotypes. To do this, we have used a single cohort (INTERVAL) with extensive multi-omics data to train genetic scores using machine learning. Here, you can explore and download the genetic scores for a wide range of biomolecular traits in human blood as well as the summary statistics of their associations with key traits and diseases in the UK Biobank.

Genetic scores were trained on the [INTERVAL cohort](https://www.intervalstudy.org.uk/) using [Bayesian Ridge regression](https://scikit-learn.org/stable/auto_examples/linear_model/plot_bayesian_ridge.html). Validation was performed on independent individuals from other cohorts or on withheld subsets of INTERVAL (more info below). Detailed methods and validation steps can be found <a href="/faqs/">here</a>.
<br/>
<br/>

# Platforms with Genetic Scores
---

{% include feature_row id="feature_row_pgs" %} <br>




# Application of Genetic Scores
---
{% include feature_row id="feature_phenotype" type="left" %}  <br>


# Citation
---
OMICSPRED is under active development, and we will continue to add genetic scores. If you use OMICSPRED in your research, we ask that you cite our submitted ASHG 2021 abstract for now (below). A full manuscript is in preparation and is anticipated to be preprinted in Q3/Q4 2021.

Manuscript: <em> Xu Y. et al. </em> An atlas of genetic scores to predict multi-omic biomolecular traits in blood. (in preparation)

ASHG Abstract: <em> Yu Xu, Scott Ritchie, Maik Pietzner, Samuel Lambert, Sebastian May-Wilson, Artika Nath, Praveen Surendran, Åsa Johansson, Elodie Persyn, Loïc Lannelongue, Bram Prins, Nicola Pirastu, Dirk Paul, Christopher Yau, James F. Wilson, Claudia Langenberg, Anders Mälarstig, John Danesh, Adam Butterworth, Michael Inouye. </em> **An atlas of genetic scores to predict multi-omic biomolecular traits in blood.** American Society of Human Genetics (2021)





## Questions and Feedback

We would love to hear from you! To provide feedback or ask a question, you can contact the OMICSPRED team [here](mailto:omicspred@gmail.com).



## Supported by:

{% include gallery id="gallery_logos" type="left"%}
