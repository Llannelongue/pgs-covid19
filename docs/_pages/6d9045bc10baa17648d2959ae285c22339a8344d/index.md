---
layout: splash
title: "PGS of Molecular and Celluar Traits"
permalink: /6d9045bc10baa17648d2959ae285c22339a8344d/

header:
  overlay_image: /assets/images/background_DNA.jpg
  <!-- overlay_filter: rgba(255, 255, 255, 0.) -->

excerpt: ""



intro:
  - excerpt: "These are initial results obtained after training polygenic scores (PGSs) on the INTERVAL dataset and testing them on UK Biobank."

feature_row:
  - image_path: /assets/images/SomaLogic_Logo.jpg
    title: "SOMAscan Plasma Proteins"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/molecular-pgs/
    excerpt: "(proteins, metabolites etc)"
  - image_path: /assets/images/background_DNA.jpg
    title: "Cellular PGSs"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/cellular-pgs/
    excerpt: "(blood cell traits)"
  - image_path: /assets/images/background_DNA.jpg
    title: "COVID19 phenotypes"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/covid19-phenotype/
    excerpt: "(death risk, severity, susceptibility)"
  - image_path: /assets/images/background_DNA.jpg
    title: "COVID19 phenotypes"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/covid19-phenotype/
    excerpt: "(death risk, severity, susceptibility)"


feature_molecular:
  - image_path: /assets/images/SomaLogic_Logo.jpg
    title: "Plasma proteins"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Somalogic-pgs/
    excerpt: "(2384 protein PGS, which were trained on [INTERVAL cohort](https://www.intervalstudy.org.uk/) and externally validated on [FENLAND cohort](https://www.mrc-epid.cam.ac.uk/research/studies/fenland/))"

feature_cellular:
  - image_path: /assets/images/olink_logo.png
    title: "Plasma proteins"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Olink-pgs/
    excerpt: "(309 protein PGS, which were trained on [INTERVAL cohort](https://www.intervalstudy.org.uk/) and externally validated on [NSPHS cohort](https://pubmed.ncbi.nlm.nih.gov/20568910/) and [ORCADES cohort](https://www.ed.ac.uk/viking/about-us/our-studies))"

feature_metabolon:
  - image_path: /assets/images/Metabolon_logo.png
    title: "Plasma metabolites"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/Metabolon-pgs/
    excerpt: "(727 metabolites PGS, which were trained on [INTERVAL cohort Phase 1](https://www.intervalstudy.org.uk/) and validated on INTERVAL cohort Phase 2)"

feature_phenotype:
  - image_path: /assets/images/UK_biobank_logo.png
    title: "Aossications with phenotypes in UK biobank"
    url: /6d9045bc10baa17648d2959ae285c22339a8344d/pgs/covid19-phenotypes/
    excerpt: "(PGS models of molecular and celluar traits in this Atlas were applied to calculate PGSs of these traits of [UK biobank](https://www.ukbiobank.ac.uk/) [white british] samples , which were then used to test associations with vairous other complex phenotypes)"


gallery_logos:

  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/logo_dphpc.png
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/logo_hdruk.jpg
  - url: "https://baker.edu.au"
    image_path: /assets/images/logo_baker.png

---

<!-- {% include feature_row id="intro" type="center" %}-->


# Welcome
---
<div style="text-align: justify"> 
<p>
This site offers services of exploring and downloading polygenic scores (PGS) of a wide range of molecular and celluar traits in human whole blood, which includes proteins, metabolites, blood cell traits, etc..
</p>
</div>


These PGSs were trained on the [INTERVAL study](https://www.intervalstudy.org.uk/) using the [Bayesian Ridge method](https://scikit-learn.org/stable/auto_examples/linear_model/plot_bayesian_ridge.html), and externally validated in other cohorts. Detailed methods and validation steps can be found in our [manuscripts](https://www.biorxiv.org/content/10.1101/2020.02.17.952788v1).    


<br/>



<!-- {% include feature_row %} -->





# PGS Resources
---

{% include feature_row id="feature_molecular" type="left" %}

{% include feature_row id="feature_cellular" type="left" %}

{% include feature_row id="feature_metabolon" type="left" %}
<br/>




# Applications of the PGS Atlas
---
{% include feature_row id="feature_phenotype" type="left" %}
<br/>




## Acknowledgements
<div style="text-align: justify"> 
<p>Participants in the INTERVAL randomised controlled trial were recruited with the active collaboration of <a href="http://www.nhsbt.nhs.uk">NHS Blood and Transplant England</a>, which has supported field work and other elements of the trial. DNA extraction and genotyping was co-funded by the National Institute for Health Research (NIHR), <a href="http://bioresource.nihr.ac.uk">the NIHR BioResource</a> and the NIHR [Cambridge Biomedical Research Centre at the Cambridge University Hospitals NHS Foundation Trust]. The academic coordinating centre for INTERVAL was supported by core funding from: NIHR Blood and Transplant Research Unit in Donor Health and Genomics (NIHR BTRU-2014-10024), UK Medical Research Council (MR/L003120/1), British Heart Foundation (SP/09/002; RG/13/13/30194; RG/18/13/33946) and the NIHR [Cambridge Biomedical Research Centre at the Cambridge University Hospitals NHS Foundation Trust]. A complete list of the investigators and contributors to the INTERVAL trial is provided in the <a href="https://pubmed.ncbi.nlm.nih.gov/28941948/">reference</a>. The academic coordinating centre would like to thank blood donor centre staff and blood donors for participating in the INTERVAL trial.</p>
</div>

<div style="text-align: justify"> 
UK Biobank data access was approved under project 7439, and all the participants gave their informed consent for health research.
</div>






<br/><br/>
### Supported by:

{% include gallery id="gallery_logos" type="left"%}
