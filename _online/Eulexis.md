---
title: Eulexis
description: morphological analyzer, dictionary
website: https://outils.biblissima.fr/en/eulexis/index.php
nickname: Eulexis-html
categories: [greek]
---
# {{ page.title }}

[{{ page.title }}]({{ page.website }}) is a lemmatiser for **Ancient Greek** texts. Our adaptaion contains lemmatization, morphological analyzing, and short English definitions (one-two words). 

<span style="background-color: #ffa6a6; padding: 1em;">
This dictionary was superseded with [off-line version][5] and will not be updated in the future.
</span>


## Download

[Download][2] the most recent version and add file `index.html` to GoldenDict following the [guide for HTML dictionaries][4].


## Exemplum

{% include img-viewer.html img="img/Eulexis-1.png" id="1" %}
{% include img-viewer.html img="img/Eulexis-2.png" id="2" %}


## States and limitations

Comparing to [Alpheios][3], this dictionary is tolerant to incorrect or absent tones and breathing marks, but someitmes fails to recognize some declension or conjugation forms. Also, Greek words can be typed in transliteration:

```
αβγδεζηθικλμνξοπρςστυφχψωϝϟ
abgdezhqiklmncoprsstufxywfk
```


## License

[![Public Domain](https://licensebuttons.net/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)\\
This work is distributed as [Public Domain](http://creativecommons.org/publicdomain/mark/1.0/).

[1]: https://github.com/latin-dict/{{ page.nickname }}
[2]: https://github.com/latin-dict/{{ page.nickname }}/releases
[3]: {{ site.baseurl }}{% link _online/Alpheios.md %}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
[5]: {{ site.baseurl }}{% link _dictionaries/morphology-grc.md %}