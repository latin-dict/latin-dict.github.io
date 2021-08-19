---
layout: default
title: Monolingual dictionaries
filter: latin
---

# Latin-Latin dictionaries

Fast introduction into the Latin-Latin dictionaries:

- concise: [Laurenzi]({% link _dictionaries/Laurenzi1708.md %}), [Blatt]({% link _dictionaries/Blatt1997.md %})
- middle-sized: [Reyher]({% link _dictionaries/Reyher1712.md %}), [Gallicciolli]({% link _dictionaries/Gallicciolli1778.md %})
- extensive: [Forcellini]({% link _dictionaries/Forcellini.md %}), [Gesner]({% link _dictionaries/Gesner1749.md %}), [TLL]({% link _dictionaries/ThLL.md %})

<!-- Such Medieval Latin dicitonaries as [Blatt]({% link _dictionaries/Blatt1997.md %}) -->

These and other monolingual dictionaries:


{% assign dicts = site.dictionaries | where: "categories",page.filter | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}


## Extras

{% assign dicts = site.data.extras_monolingual | sort: "author" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ dict.website }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}

{%- endfor %}