---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

<h1>Test</h1>

{% comment %}
Language: Liquid of Jekyll
{% endcomment %}
