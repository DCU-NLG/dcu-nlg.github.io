---
permalink: /
title: "DCU Natural Language Generation"
layout: splash
header:
    overlay_filter: rgba(237, 27, 47, 0.3)
    overlay_image: /assets/images/trottier.jpg
    actions:
        - label: "GitHub"
          url: "https://github.com/DCU-NLG"
        - label: "Twitter"
          url: "https://github.com/DCU-NLG"

excerpt: "DCU NLG is a research group within Dublin City University and the ADAPT Research Centre, both located in Dublin, Ireland. We work on language generation in its broadest sense, encompassing data-to-text, text-to-text and free generation tasks."

row_research:
  - image_path: /assets/images/home/poster-1.jpeg
    url: /publications
    alt: "Poster Presentation"
    title: "Research"
    btn_label: "Publications"
    btn_class: "btn--primary"
    excerpt: "We are are group of researchers based in DCU and ADAPT, with external members at Aberdeen University, and IBM Research Dublin. Our collaborations extend to all continents, and both academia and industry."

row_code:
  - image_path: /assets/images/home/github.jpg
    url: https://github.com/DCU-NLG
    alt: "Our GitHub page"
    title: "Open-Source Code"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    excerpt: "We publish code for our models and datasets on GitHub to make it easier for researchers and developers to reproduce and build upon our work. We welcome pull requests and issues on active projects from the community."
  
row_about_us:
  - image_path: /assets/images/home/lunch-1.jpeg
  - image_path: /assets/images/home/jackie-axes-2019.jpg
  - image_path: /assets/images/home/park-1.jpeg
  - image_path: /assets/images/home/coffee-acl-2022.jpg
  - image_path: /assets/images/home/michaela-acl-2022.jpg
  - image_path: /assets/images/home/zichao-acl-2022.jpg
  - image_path: /assets/images/home/benno-acl-2022.jpg
  - image_path: /assets/images/home/nick-acl-2022.jpg
  - image_path: /assets/images/home/vaibhav-acl-2022.jpg


---
{% comment %}
Based on: https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/docs/_pages/splash-page.md
{% endcomment %}


{% include feature_row id="row_research" type="left" %}

{% include feature_row id="row_code" type="right" %}



# About Us
{: .text-center}

We are a group of faculty members, researchers and students affiliated with McGill University and Mila Quebec AI Institute, both located in Montreal, Canada. We often collaborate with researchers around the world.
{: .text-center}

{% include feature_row id="row_about_us" %}

