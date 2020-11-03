---
title: Alpheios
description: morphological analyzer
website: https://alpheios.net/
categories: [greek]
---
# {{ page.title }}

[{{ page.title }}]({{ page.website }}) provides a set of tools for reading classical literatures, and particularly an analyzer of **Ancient Greek morphology**. This service is based on a modified Morpheus engine originally developed for [Perseus Digital Library](http://www.perseus.tufts.edu/).


## Download

Current version is [v1.0 (October 16, 2020)][2].


## Exemplum

{% include img-viewer.html img="img/Alpheios-1.png" id="1" %}
{% include img-viewer.html img="img/Alpheios-2.png" id="2" %}


## States and limitations

In contrast to [Eulexis][3], this dictionary only accepts words written in correct Polytonic orthography with all necessary tones; letter case is significant. So, it will recognize "φιλ<span style="color: red">έ</span>ω" but not "φιλ<span style="color: red">ε</span>ω".


## Usage guidelines

Add file `index.html` to GoldenDict following the [guide for HTML dictionaries][4].


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


[1]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[2]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-10-16
[3]: {{ site.baseurl }}{% link _online/Eulexis.md %}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
