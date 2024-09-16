
---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

{% comment %}
Language: Liquid of Jekyll
{% endcomment %}


Please have a look on my CV.

[Get it]({{ '/assets/pdfs/CV_MichaelBieri.pdf' | relative_url }})