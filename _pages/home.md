---
permalink: /
title: "DCU Natural Language Generation"
layout: splash
header:
    overlay_filter: rgba(237, 27, 47, 0.3)
    overlay_image: /assets/images/dcu_computing.jpg
    actions:
        - label: "GitHub"
          url: "https://github.com/DCU-NLG"

excerpt: "DCU NLG is a research group within Dublin City University and the ADAPT Research Centre, located in Dublin, Ireland. We work on language generation in its broadest sense, encompassing data-to-text, text-to-text and free generation tasks."

row_research:
  - image_path: /assets/images/20220523_121124.jpg
    url: /publications
    alt: "Poster Presentation"
    title: "Research"
    btn_label: "Publications"
    btn_class: "btn--primary"
    excerpt: "We have a number of focus topics within language generation, including controllability, disentanglement, modularisation, reproducibility and evaluation of automatically generated text."

row_code:
  - image_path: /assets/images/github.jpg
    url: https://github.com/DCU-NLG
    alt: "Our GitHub page"
    title: "Resource Sharing"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    excerpt: "We aim to publish resources including models, datasets, code and data sheets via GitHub to help others to use and build on our work. Feedback is always welcome."
  
row_about_us:
  - image_path: /assets/images/SM_MSR19.jpg
  - image_path: /assets/images/AB_2019.png
  - image_path: /assets/images/FM_2022.jpg
  - image_path: /assets/images/RH_EMNLP_2022.jpeg
  - image_path: /assets/images/AB_2022.jpg
  - image_path: /assets/images/ML_2023-2.jpg 
  - image_path: /assets/images/MP.jpg
  - image_path: /assets/images/SM_EMNLP19.jpg
  - image_path: /assets/images/20230201_141106.jpg


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

