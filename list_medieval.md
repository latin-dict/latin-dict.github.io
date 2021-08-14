---
layout: default
title: Medieval Latin
filter: medieval
---

# Medieval Latin

{% assign dicts = site.dictionaries | where: "categories",page.filter | sort: "nickname" %}
{% for dict in dicts %}

{% if dict.disable %}
* <span style="color: grey;">**{{ dict.author }}, {{ dict.year }}:** {{ dict.title }} \\
  [{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}</span>
{% else %}
* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}
{% endif %}

{%- endfor %}


## Extras

{% assign dicts = site.data.extras_medieval | sort: "author" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ dict.website }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}

{%- endfor %}
