---
layout: default
title: Home
redirect_from:
  - /dictionaries.html
  - /online.html
---

# Salve!

This website holds collection of Latin dictionaries. List of the available wordbooks is in the particular sections.

Dictionaries are encoded for desktop computers and mobile devices. Formats and supported dictionary shells are explained in the [documentation]({{ site.baseurl }}{% link docs/docs.md %}).

I am open for cooperation. If you want to share your dictionary, join to a digitalization project, or have technical questions, feel free to [contact me]({{ site.baseurl }}{% link about.md %}).

# News

{% for post in site.posts limit:10 %}

{% if post.version %}
*  [{{ post.nickname }} {{ post.version }}]({{ site.baseurl }}{{ post.url }}) » _{{ post.date | date: "%Y-%m-%d" }}_
{% else %}
*  [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) » _{{ post.date | date: "%Y-%m-%d" }}_
{% endif %}

{% endfor %}

See [old news]({{ site.baseurl }}{% link news.md %}) or subscribe to [RSS feed](/feed.xml). 