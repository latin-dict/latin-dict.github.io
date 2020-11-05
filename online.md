---
layout: default
title: Online dictionaries
---

# Foreword

Dictionaries in this section are adaptations of online services for desktop GoldenDict, so they do require stable Internet connection but can be used seamlessly alongside with [offline dicitonaries]({{ site.baseurl }}{% link dictionaries.md %}).


# Latin

{% assign dicts = site.online | where: "categories","latin" %}
{% for dict in dicts %}

* **[{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}):** {{ dict.description }}
  
{%- endfor %}


# Ancient Greek

{% assign dicts = site.online | where: "categories","greek" %}
{% for dict in dicts %}

* **[{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}):** {{ dict.description }}
  
{%- endfor %}
