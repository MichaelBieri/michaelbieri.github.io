---
layout: default
title: "Blog"
---

<head>
  <style>
    body {
      background-color: #f4f4f9;
    }
    .container {
      max-width: 909.062px;
      margin: 60px auto 60px auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>
  <div class="container">
    {% if site.show_excerpts %}
      {% include home.html %}
    {% else %}
      {% include archive.html title="Posts" %}
    {% endif %}

    {% comment %}
    Language: Liquid of Jekyll
    {% endcomment %}
  </div>
</body>