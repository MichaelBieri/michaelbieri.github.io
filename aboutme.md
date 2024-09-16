---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

<!DOCTYPE html>
<html>
  <body>
     {{ test }}
  </body>
</html>

{% comment %}
Language: Liquid of Jekyll
{% endcomment %}
