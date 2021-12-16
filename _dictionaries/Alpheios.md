---
title: Ancient Greek morphology
author: Alpheios
year: (online)
description: morphological analyzer
website: https://alpheios.net/
nickname: Alpheios-html
tags: [Ancient Greek]
categories: [archive]
comment: 
---
# {{ page.title }}

[{{ page.title }}]({{ page.website }}) provides a set of tools for reading classical literatures, and particularly an analyzer of **Ancient Greek morphology**. This service is based on a modified Morpheus engine originally developed for [Perseus Digital Library](http://www.perseus.tufts.edu/).

<span style="background-color: #ffa6a6; padding: 1em;">
This dictionary was superseded with off-line [Morphologia Graeca][5] and will not be updated in the future.
</span>


## Download

[Download][2] the most recent version and add file `index.html` to GoldenDict following the [guide for HTML dictionaries][4].

Version in DSL (ABBYY Lingvo) format can be found in the [Dadako' Knigohran](http://dadako.narod.ru/paperpoe.htm).


## Exemplum

{% include img-viewer.html img="img/Alpheios-1.png" id="1" %}
{% include img-viewer.html img="img/Alpheios-2.png" id="2" %}


## States and limitations

In contrast to [Eulexis][3], this dictionary only accepts words written in correct Polytonic orthography with all necessary tones; letter case is significant. So, it will recognize "φιλ<span style="color: red">έ</span>ω" but not "φιλ<span style="color: red">ε</span>ω".


## License

[![Public Domain](/assets/img/license-public-domain.png)](http://creativecommons.org/publicdomain/mark/1.0/)\\
This work is distributed as [Public Domain](http://creativecommons.org/publicdomain/mark/1.0/).

[1]: https://github.com/latin-dict/{{ page.nickname }}
[2]: https://github.com/latin-dict/{{ page.nickname }}/releases
[3]: {{ site.baseurl }}{% link _dictionaries/Eulexis.md %}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
[5]: {{ site.baseurl }}{% link _dictionaries/morphology-grc.md %}