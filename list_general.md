---
layout: default
title: General dictionaries
filter: general
---

# General dictionaries

{% assign dicts = site.dictionaries | where: "categories",page.filter | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}
