---
permalink: /
title: "DCU Natural Language Generation"
layout: splash
header:
    overlay_filter: rgba(237, 27, 47, 0.3)
    overlay_image: /assets/images/dcu.png
    actions:
        - label: "GitHub"
          url: "https://github.com/DCU-NLG"
        - label: "Twitter"
          url: "https://github.com/DCU-NLG"

excerpt: "DCU NLG is a research group within Dublin City University and the ADAPT Research Centre, both located in Dublin, Ireland. We work on language generation in its broadest sense, encompassing data-to-text, text-to-text and free generation tasks."

row_research:
  - image_path: /assets/images/20220523_121124.jpg
    url: /publications
    alt: "Poster Presentation"
    title: "Research"
    btn_label: "Publications"
    btn_class: "btn--primary"
    excerpt: "We have a number of focus topics within language generation, including controllability, disentanglement, modularisation, reproducibility and evaluation of automatically generated text."

row_code:
  - image_path: /assets/images/github.png
    url: https://github.com/DCU-NLG
    alt: "Our GitHub page"
    title: "Open-Source Code"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    excerpt: "We publish code for our models and datasets on GitHub to make it easier for researchers and developers to reproduce and build upon our work. We welcome pull requests and issues on active projects from the community."
  
row_about_us:
  - image_path: /assets/images/poster02.jpg
  - image_path: /assets/images/SM_INLG18.jpg
  - image_path: /assets/images/poster03.jpg
  - image_path: /assets/images/RH_EMNLP_2022.jpeg
  - image_path: /assets/images/20220523_122856.jpg
  - image_path: /assets/images/SM_MoBen.jpg
  - image_path: /assets/images/20220523_121124.jpg
  - image_path: /assets/images/MP.png 
  - image_path: /assets/images/20221212_164258.jpg


---
{% comment %}
Based on: https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/docs/_pages/splash-page.md
{% endcomment %}


{% include feature_row id="row_research" type="left" %}

{% include feature_row id="row_code" type="right" %}



# About Us
{: .text-center}

We are are group of researchers based in DCU and ADAPT, with external members at Aberdeen University, and IBM Research Dublin. Our collaborations extend to all continents, and both academia and industry.
{: .text-center}

{% include feature_row id="row_about_us" %}

