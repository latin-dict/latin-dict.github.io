---
layout: default
title: Scientific or special
filter: scientific
---

# Scientific or special

{% assign dicts = site.dictionaries | where: "categories",page.filter | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}


## Extras

{% assign dicts = site.data.extras_scientific | sort: "author" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ dict.website }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}

{%- endfor %}
