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

{% capture workshop-2026-text %}
**More details to follow soon!**
{% endcapture %}

<div class="notice--success" align="center">
  <h1>🌟 Save the Date for October 14–18, 2026 - Join Us in Türkiye for MRS Workshop 2026!</h1>
  {{ workshop-2026-text | markdownify }}
</div>

{% capture notice-text %}
The MRSHub is a curated collection of resources for magnetic resonance spectroscopy, including data, software code, educational material, and a forum for knowledge exchange and collaboration. The MRSHub promotes open science. All resources are publicly available.

**[We are actively seeking contributions! If you are interested in advancing open science in MRS, please see our MRSHub User Guide!](https://forum.mrshub.org/t/mrshub-user-guide/7)**
{% endcapture %}

<div class="notice--info" align="center">
  <h1>Welcome to the MRSHub!</h1>
  {{ notice-text | markdownify }}
</div>

{% include feature_row %}
