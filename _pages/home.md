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

{% capture hackathon-2024-text %}
After the great success of the first edition in Toronto 2023, we're once again bringibg together open-minded MRS researchers who want to collaboratively solve problems and create useful tools and resources for the community. ! Please join us for the 2nd MRS Hackathon in Boston, Massachussetts, right after the official MRS Workshop. Registration is **free**. 

**[MRS Hackathon 2024 Website](https://sites.google.com/view/mrshackathon2024/home)**

**[ISMRM MRS Workshop 2024 Website](https://www.ismrm.org/workshops/2024/MRS)**
{% endcapture %}


<div class="notice--success" align="center">
  <h1>Registration now open for the MRS Hackathon 2024 in Boston (October 18-19)!</h1>
  {{ hackathon-2024-text | markdownify }}
</div>

{% include feature_row %}
