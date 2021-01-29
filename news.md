---
layout: default
title: News archive
---

# Old news

{% for post in site.posts offset:10 %}
*  [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) » _{{ post.date | date: "%Y-%m-%d" }}_
{% endfor %}