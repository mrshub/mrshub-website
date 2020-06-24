---
title: "Single-voxel MRS datasets"
permalink: /datasets_svs/
date: 2020-05-20T00:00:00+00:00
sidebar:
  nav: "datasets"
---

This is a list of single-voxel MRS datasets.

{% for dataset_collection in site.dataset_collection %}
  {% if dataset_collection.type contains "svs" %}
  <h2 id="{{ dataset_collection.name }}">
      {{ dataset_collection.name }}
  </h2>
  <img src= "{{ site.url }}{{ site.baseurl }}{{ dataset_collection.image }}" alt="" align="right" width="150"/>
  <p>{{ dataset_collection.abstract | markdownify }}</p>

  <table>
    <thead>
      <tr>
        <th colspan="2"> {{ dataset_collection.name }} </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Developer</b></td>
        <td>{{ dataset_collection.developer }}</td>
      </tr>
      <tr>
        <td><b>Format</b></td>
        <td>{{ dataset_collection.format }}</td>
      </tr>
      <tr>
        <td><b>Sequence</b></td>
        <td>{{ dataset_collection.sequence }}</td>
      </tr>
      <tr>
        <td><b>License</b></td>
        <td>{{ dataset_collection.license }}</td>
      </tr>
      <tr>
        <td><b>Credit</b></td>
        <td>{{ dataset_collection.credit }}</td>
      </tr>
      <tr>
        <td><b>Contact</b></td>
        <td>{{ dataset_collection.contact }}</td>
      </tr>
    </tbody>
  </table>

  {% if dataset_collection.mrshub_url %}<a href="{{ dataset_collection.mrshub_url }}">MRSHub Data</a>&nbsp;{% endif %}
  {% if dataset_collection.original_url %}<a href="{{ dataset_collection.original_url }}">Link to Dataset</a>&nbsp;{% endif %}{% if dataset_collection.paper %}<a href="{{ dataset_collection.paper }}">Publication</a>{% endif %}
  {% endif %}
{% endfor %}
