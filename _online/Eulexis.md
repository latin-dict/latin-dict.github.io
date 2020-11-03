---
title: Eulexis
description: morphological analyzer, dictionary
website: https://outils.biblissima.fr/en/eulexis/index.php
categories: [greek]
---
# {{ page.title }}

[{{ page.title }}]({{ page.website }}) is a lemmatiser for **Ancient Greek** texts. Our adaptaion contains lemmatization, morphological analyzing, and short English definitions (one-two words). 


## Download

Current version is [v1.0 (October 16, 2020)][2].


## Exemplum

{% include img-viewer.html img="img/Eulexis-1.png" id="1" %}
{% include img-viewer.html img="img/Eulexis-2.png" id="2" %}


## States and limitations

Comparing to [Alpheios][3], this dictionary is tolerant to incorrect or absent tones and breathing marks, but someitmes fails to recognize some declension or conjugation forms. Also, Greek words can be typed in transliteration:

```
αβγδεζηθικλμνξοπρςστυφχψωϝϟ
abgdezhqiklmncoprsstufxywfk
```


## Usage guidelines

Add file `index.html` to GoldenDict following the [guide for HTML dictionaries][4].


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


[1]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[2]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-10-16
[3]: {{ site.baseurl }}{% link _online/Alpheios.md %}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
