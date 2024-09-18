---
layout: default
title: "Blog"
---

<head>
  <style>
    body {
      background-color: #f4f4f9;
      color: #333;
    }
  </style>
</head>
¨
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

{% comment %}
Language: Liquid of Jekyll
{% endcomment %}
