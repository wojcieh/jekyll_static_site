---
title: Lekcje
layout: default
---
<h2>Lekcje</h2>
<ol>
{% for page in site.pages %}
{% if page.category %}
  <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ol>