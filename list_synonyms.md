---
layout: default
title: Dictionaries of synonyms
filter: synonyms
---

# Dictionaries of synonyms


Monolingual:

* **Popma, 1865:** [De differentiis verborum]({% link _dictionaries/Popma1865.md %})
  * **Richter, 1750:** [Differentias]({% link _dictionaries/Richter1750.md %})
  * **Strodtmann, 1754:** Spicilegium differentiarum
  * **Lázár, 1769:** Versus Mnemonici ad ductum Ausonii Pompae Frisii

Other dictionaries:

{% assign dicts = site.dictionaries | where: "categories",page.filter | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}]</span> {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}
