---
layout: default
title: Home
redirect_from:
  - /dictionaries.html
  - /online.html
---

# Salve!

This website is dedicated to Latin language (and some Greek).

Dictionaries are encoded for desktop computers and mobile devices, the primary goals are GoldenDict (desktop) and Aard2 (Android). Formats and supported dictionary shells are explained in the [documentation]({{ site.baseurl }}{% link docs/docs.md %}).

I am open for cooperation. If you want to share your dictionary, join to a digitalization project, or have technical questions, feel free to [contact me]({{ site.baseurl }}{% link about.md %}).

<div>

<div id="index-announce" markdown="1">

# Announcement

<p markdown="1" style="padding: 5px; background-color: #ffd6f5;">

I am looking for the **"Humanist Latin Dictionary"** made by **William Harris (1926-2009)**. It was sold in 1996-2002 as a computer application for MacOS 7-9 or Windows 3.1 by two distributors, Rob Latousek (Centaur Systems, US) and Julian Morgan (J&#8209;PROGS, UK). Also, it was included into the CD&#8209;ROM collections LatinStudio or Latina.

</p>

If you have a copy of this dictionary, please, share it with me. I will be grateful for any information about the Dr. Harris heirs: Min Harris (Shoreham, VT), James Harris (Somerville, MA), or John Harris (West Hartford, CT).

You can contact me by [e-mail]({{ site.baseurl }}{% link about.md %}), or on the web forums, [Textkit](https://www.textkit.com/greek-latin-forum/viewtopic.php?t=72932) or [Latin Discussion](https://latindiscussion.org/threads/search-humanist-latin-dictionary.36687/).

</div>

<div id="index-news" markdown="1">

# News

{% for post in site.posts limit:10 %}

{% if post.version %}
*  [{{ post.nickname }} {{ post.version }}]({{ site.baseurl }}{{ post.url }}) » _{{ post.date | date: "%Y-%m-%d" }}_
{% else %}
*  [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) » _{{ post.date | date: "%Y-%m-%d" }}_
{% endif %}

{% endfor %}

See [old news]({{ site.baseurl }}{% link news.md %}) or subscribe to [RSS feed](/feed.xml). 

</div>

</div>
