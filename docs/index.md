---
layout: splash

title: " <br/>OMICSPRED: The Atlas of Genetic Scores for Prediction of Multi-Omics Data "
excerpt: "  <br/>  <br/> "
header:
  overlay_image: /assets/images/home_banner.png

feature_row_pgs:
  - image_path: /assets/images/SomaLogic_singleRow.png
    title: "Proteins"
    url: /pgs/Somalogic-pgs/
    excerpt: "2,384 protein genetic scores validated on the [FENLAND cohort](https://www.mrc-epid.cam.ac.uk/research/studies/fenland/)."
  - image_path: /assets/images/Olink_singleRow.png
    title: "Proteins"
    url: /pgs/Olink-pgs/
    excerpt: "308 protein genetic scores validated on the [NSPHS cohort](https://pubmed.ncbi.nlm.nih.gov/20568910/) and [ORCADES cohort](https://www.ed.ac.uk/viking/about-us/our-studies)."
  - image_path: /assets/images/Metabolon_singleRow.png
    title: "Metabolites"
    url: /pgs/Metabolon-pgs/
    excerpt: "726 metabolites genetic scores validated on a held-out subset in INTERVAL."
  - image_path: /assets/images/Nightingale_logo.png
    title: "Metabolites"
    url: /pgs/Nightingale-pgs/
    excerpt: "141 metabolites genetic scores validated on [UK Biobank](https://www.ukbiobank.ac.uk/)."
  - image_path: /assets/images/RNAseq_logo.png
    title: "Gene expressions"
    url: /pgs/GE-pgs/
    excerpt: "13,668 gene expression genetic scores validated on a held-out subset in INTERVAL"


feature_study_intro:
  - image_path: /assets/images/interval-logo.png
    excerpt: "INTERVAL is a randomised trial of approximately 50,000 healthy blood donors, which aims to study the safety of varying frequency of blood donation. Between June 2012 and June 2014, the study recruited about 25,000 men and about 25,000 women aged 18 years and older (median 44 years of age) at 25 NHS Blood and Transplant (NSHBT) blood donation centres across England. The  collection  of  their  blood  samples  for  research  purposes  was  done  using  standard  protocols and  has  been  extensively [described  previously](http://www.intervalstudy.org.uk/files/2019/11/Moore-et-al.-Trials-2014.pdf)."
    btn_class: btn--primary



feature_phenotype:
  - image_path: /assets/images/UKB_largeFeature.png
    title: "Associations with phenotypes in UK biobank"
    url: /Application/pgs_ukb_disease_associations/
    excerpt: "Genetic scores of biomolecular traits from this Atlas were applied to [UK biobank](https://www.ukbiobank.ac.uk/) samples (white british) and used to test associations with various other complex phenotypes."

gallery_logos:
  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/DPHPC_gallery.png
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/HDRuk_gallery.png
  - url: "https://baker.edu.au"
    image_path: /assets/images/Baker_gallery.png

---
# The Atlas
---
You can explore and download genetic scores for a wide range of biomolecular traits in human whole blood, including gene expressions, proteins, metabolites.

The genetic scores were trained on the [INTERVAL cohort](https://www.intervalstudy.org.uk/) using the [Bayesian Ridge method](https://scikit-learn.org/stable/auto_examples/linear_model/plot_bayesian_ridge.html), and externally validated in other cohorts. Detailed methods and validation steps can be found in our [manuscripts](https://www.biorxiv.org/content/10.1101/2020.02.17.952788v1).
<br/>
<br/>

# The INTERVAL Study
---

<img src="/assets/images/interval-logo.png" alt="drawing"  style="float: right; margin-left: 1em; margin-top: 0.5em; width:350px; height:180px"/>

INTERVAL is a randomised trial of approximately 50,000 healthy blood donors, which aims to study the safety of varying frequency of blood donation. Between June 2012 and June 2014, the study recruited about 25,000 men and about 25,000 women aged 18 years and older (median 44 years of age) at 25 NHS Blood and Transplant (NSHBT) blood donation centres across England. The  collection  of  their  blood  samples  for  research  purposes  was  done  using  standard  protocols and  has  been  extensively [described  previously](http://www.intervalstudy.org.uk/files/2019/11/Moore-et-al.-Trials-2014.pdf).
<br/>
<br/>

# Platform with Genetic Scores
---

{% include feature_row id="feature_row_pgs" %} <br>




# Application of Genetic Scores in the Atlas
---
{% include feature_row id="feature_phenotype" type="left" %}  <br>


# Citation
---
The Atlas is under active development, and we continue to add in genetic scores of more bimolecular traits and external validations. If you use the Atlas in your research we ask that you cite our submitted ASHG2021 abstract (full manuscript is under preparation):

<em> Yu Xu, Scott Ritchie, Maik Pietzner, Samuel Lambert, Sebastian May-Wilson, Artika Nath, Praveen Surendran, Åsa Johansson, Elodie Persyn, Loïc Lannelongue, Bram Prins, Nicola Pirastu, Dirk Paul, Christopher Yau, James F. Wilson, Claudia Langenberg, Anders Mälarstig, John Danesh, Adam Butterworth, Michael Inouye. </em> **An atlas of genetic scores to predict multi-omic biomolecular traits in blood.**





## Questions and Feedback

We would love to hear from you! To provide feedback or ask a question, you can contact the Omics Atlas team [here](mailto:yx322@medschl.cam.ac.uk).



## Supported by:

{% include gallery id="gallery_logos" type="left"%}
