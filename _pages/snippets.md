---
title: "Snippets"
permalink: /snippets/
date: 2016-02-24T03:02:20+00:00
toc: true
---

This is a list of little bits and pieces of code, which might be useful for others to build on, but are not part of a larger software package or a function library.

{% for software_collection in site.software_collection %}
  {% if software_collection.type contains "snippet" %}
  <h2>
      {{ software_collection.name }}
  </h2>
  <img src= "{{ site.url }}{{ site.baseurl }}{{ software_collection.image }}" alt="" align="right"/>
  <p>{{ software_collection.abstract | markdownify }}</p>
  <p>Language: {{ software_collection.language }}</p>
  <p>License: {{ software_collection.license }}</p>
  <a href="{{ software_collection.url }}">
  Website
  </a>   
  <a href="{{ software_collection.paper }}">
  Publication
  </a>
  {% endif %}
{% endfor %}
