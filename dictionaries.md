---
layout: default
title: Dictionaries
---

# Latin-Latin dictionaries

Fast introduction into the Latin-Latin dictionaries:

- brief and compact: [Laurenzi]({% link _dictionaries/Laurenzi1708.md %})
- middle-sized: [Reyher]({% link _dictionaries/Reyher1712.md %}), [Gallicciolli]({% link _dictionaries/Gallicciolli1778.md %})
- extensive: [Forcellini]({% link _online/Forcellini.md %}), [Gesner]({% link _dictionaries/Gesner1749.md %}), [TLL]({% link _dictionaries/ThLL.md %})

These and other monolingual dictionaries:


{% assign dicts = site.dictionaries | where: "categories","latin" | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}<span>
  
{%- endfor %}

# General dictionaries

{% assign dicts = site.dictionaries | where: "categories","general" | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}<span>
  
{%- endfor %}

# Dictionaries of synonyms

{% assign dicts = site.dictionaries | where: "categories","synonyms" | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}<span>

{%- endfor %}

# Scientific or special

{% assign dicts = site.dictionaries | where: "categories","scientific" | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}<span>

{%- endfor %}

# Ancient Greek

{% assign dicts = site.dictionaries | where: "categories","greek" | sort: "nickname" %}
{% for dict in dicts %}

* **{{ dict.author }}, {{ dict.year }}:** [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) \\
  <span style="color: #0A749E;">[{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}<span>

{%- endfor %}

