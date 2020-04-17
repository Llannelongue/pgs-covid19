---
layout: splash

permalink: /

header:
  overlay_image: /assets/images/background_DNA.jpg
  <!-- overlay_filter: rgba(255, 255, 255, 0.) -->

excerpt: "Some text to be added here"

intro:
  - excerpt: "These are initial results obtained after training polygenic scores (PGSs) on the INTERVAL dataset and testing them on UK Biobank."

feature_row:
  - image_path: /assets/images/background_DNA.jpg
    title: "Molecular PGSs"
    url: /pgs/molecular-pgs/
    excerpt: "(proteins, metabolites etc)"
  - image_path: /assets/images/background_DNA.jpg
    title: "Cellular PGSs"
    url: /pgs/cellular-pgs/
    excerpt: "(blood cell traits)"
  - image_path: /assets/images/background_DNA.jpg
    title: "COVID19 phenotypes"
    url: /pgs/covid19-phenotype/
    excerpt: "(death risk, severity, susceptibility)"

feature_molecular:
  - image_path: /assets/images/background_DNA.jpg
    title: "Molecular PGSs"
    url: /pgs/molecular-pgs/
    excerpt: "(proteins, metabolites etc)"

feature_cellular:
  - image_path: /assets/images/background_DNA.jpg
    title: "Cellular PGSs"
    url: /pgs/cellular-pgs/
    excerpt: "(blood cell traits)"

feature_phenotype:
  - image_path: /assets/images/background_DNA.jpg
    title: "COVID19 phenotypes"
    url: /pgs/covid19-phenotypes/
    excerpt: "(death risk, severity, susceptibility)"

gallery_logos:
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/logo_hdruk.jpg
  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/logo_dphpc.png
  - url: "https://baker.edu.au"
    image_path: /assets/images/logo_baker.png

---

{% include feature_row id="intro" type="center" %}

<!-- {% include feature_row %} -->

{% include feature_row id="feature_molecular" type="left" %}

{% include feature_row id="feature_cellular" type="right" %}

{% include feature_row id="feature_phenotype" type="left" %}

## Methods
 These PGS are calculated based on a pipeline developed by [Xu. et al.](https://www.biorxiv.org/content/10.1101/2020.02.17.952788v1) (preprint).

 All the PGSs are calculated and tested on INTERVAL.

## About us
These work was led by ...

### Supported by:

{% include gallery id="gallery_logos" %}
