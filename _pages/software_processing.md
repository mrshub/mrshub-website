---
title: "Processing"
permalink: /software_processing/
date: 2020-05-15T9:00:00+00:00
sidebar:
  nav: "software"
toc: true
---

This is a list of analysis and quantification software.

{% for software_collection in site.software_collection %}
  {% if software_collection.type contains "processing" %}
  <h2 id="{{ software_collection.name }}">
      {{ software_collection.name }}
  </h2>
  <img src= "{{ site.url }}{{ site.baseurl }}{{ software_collection.image }}" alt="" align="right" width="150"/>
  <p>{{ software_collection.abstract | markdownify }}</p>

  <table>
    <thead>
      <tr>
        <th colspan="2"> {{ software_collection.name }} </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Developer</b></td>
        <td>{{ software_collection.developer }}</td>
      </tr>
      <tr>
        <td><b>Language</b></td>
        <td>{{ software_collection.language }}</td>
      </tr>
      <tr>
        <td><b>License</b></td>
        <td>{{ software_collection.license }}</td>
      </tr>
      <tr>
        <td><b>Credit</b></td>
        <td>{{ software_collection.credit }}</td>
      </tr>
    </tbody>
  </table>

  {% if software_collection.mrshub_url %}<a href="{{ software_collection.mrshub_url }}">MRSHub Code</a>&nbsp;{% endif %}
  {% if software_collection.original_url %}<a href="{{ software_collection.original_url }}">Author Website</a>&nbsp;{% endif %}
  {% if software_collection.paper %}<a href="{{ software_collection.paper }}">Publication</a>{% endif %} {% if software_collection.paper2 %}<a href="{{ software_collection.paper2 }}">Publication 2</a>{% endif %} {% if software_collection.paper3 %}<a href="{{ software_collection.paper3 }}">Publication 3</a>{% endif %}
  {% endif %}
{% endfor %}
