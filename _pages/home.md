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

{% capture hackathon-2025-text %}
We are excited to announce that registration is now open for the [MRS](https://sites.google.com/view/mrsxmrathon2025/home) x [MRathon](https://mrathon.github.io/honolulu2025/) 2025!

For the first time, we are teaming up to bring together MRI and MRS researchers, tool developers, and enthusiasts to solve challenges, create innovative resources, and connect with like-minded individuals in a collaborative, fun environment.

**[MRS x MRathon 2025 Website](https://sites.google.com/view/mrsxmrathon2025/home)**
{% endcapture %}

<div class="notice--success" align="center">
  <h1>Registration now open for the MRS x MRathon 2025 in Honolulu (May 8-9)!</h1>
  {{ hackathon-2025-text | markdownify }}
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
