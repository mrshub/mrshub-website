---
title: "Macromolecules datasets"
permalink: /datasets_mm/
date: 2020-05-20T00:00:00+00:00
sidebar:
  nav: "datasets"
---

This is a list of macromolecules datasets.

{% for dataset_collection in site.dataset_collection %}
  {% if dataset_collection.type contains "mm" %}
  <h2>
      {{ dataset_collection.name }}
  </h2>
  <img src= "{{ site.url }}{{ site.baseurl }}{{ dataset_collection.image }}" alt="" align="right" width="150"/>
  <p>{{ dataset_collection.abstract | markdownify }}</p>
  <p>Sequence: {{ dataset_collection.sequence }}</p>
  <p>License: {{ dataset_collection.license }}</p>
  <a href="{{ dataset_collection.weblink }}">
  Website
  </a>   
  <a href="{{ dataset_collection.paper }}">
  Publication
  </a>
  {% endif %}
{% endfor %}
