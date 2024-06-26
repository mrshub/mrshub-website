---
title: "MRSHub"
layout: splash
permalink: /
date: 2020-04-09T12:00:00-04:00

feature_row:
  - image_path: /assets/images/code.png
    alt: "Software & Code"
    title: "Software & Code"
    excerpt: "The MRSHub code repository collects software packages and functions to process, manipulate, analyse, and display MRS data."
    url: /software
    btn_label: "To the MRSHub code listing"
    btn_class: "btn--info btn--small"
  - image_path: assets/images/forum.jpg
    alt: "MRSHub Forum"
    title: "Forum"
    excerpt: "The MRSHub forum is a place for the MRS community to seek support, exchange ideas, ask questions, and collaborate."
    url: https://forum.mrshub.org
    btn_label: "To the MRSHub forum"
    btn_class: "btn--info btn--small"
  - image_path: /assets/images/data.jpg
    alt: "Data"
    title: "Data"
    excerpt: "The MRSHub data repository collects MRS datasets for demonstration and testing of new methods."     
    url: /datasets
    btn_label: "To the MRSHub data listing"
    btn_class: "btn--info btn--small"

---

{% capture notice-text %}
The MRSHub is a curated collection of resources for magnetic resonance spectroscopy, including data, software code, educational material, and a forum for knowledge exchange and collaboration. The MRSHub promotes open science. All resources are publicly available.

**[We are actively seeking contributions! If you are interested in advancing open science in MRS, please see our MRSHub User Guide!](https://forum.mrshub.org/t/mrshub-user-guide/7)**
{% endcapture %}

<div class="notice--info" align="center">
  <h1>Welcome to the MRSHub!</h1>
  {{ notice-text | markdownify }}
</div>

{% capture mrs-workshop-text %}
Proceedings from the 2022 Lausanne MRS Workshop (including video-recorded lectures and presentation PDFs) are now online for free access without registration!

**[2022 Lausanne MRS Workshop Proceedings](https://mrs2022.cibm.ch/agenda/)**
{% endcapture %}


<div class="notice--success" align="center">
  <h1>Proceedings from the 2022 MRS Workshop in Lausanne</h1>
  {{ mrs-workshop-text | markdownify }}
</div>

{% include feature_row %}
