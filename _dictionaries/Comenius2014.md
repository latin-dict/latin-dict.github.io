---
title: Janua linguarum reserata
author: Comenius
year: 2014
tags: [Greek, Latin]
nickname: Comenius2014
categories: [greek]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

**Ancient Greek** vocabulary translated to **Latin** was extracted from the "Janua Linguarum Reserata" (see Sources) and contains about 7,000 records (after reduplication).


## Download

Current version is [v0.1 (October 31, 2020)][1]. Format Slob is recommended for GoldenDict, read [documentation][2] about other dictionary shells.


## Exemplum

{% include img-viewer.html img="img/Comenius2014-1.png" id="1" %}


# Sources

1. Comenius, John Amos; Simon, Theodor; Courcelles, Étienne de; Vogel, Felipe; Lionello, Roberto; Gibbons, Randy. _Janua Linguarum Reserata cum Graeca versione._ Online, 2014. URL: <https://archive.org/details/comenius-janua-reserata>.

Title page states that it is a transcript of the [book published in 1665](https://books.google.no/books?id=E81mAAAAcAAJ), however in place of French text third collum contains Greek vocabulary. Source of this vocabulary is unknown, probably it was added by Felipe Vogel.


# States and limitations

Currently vocabulary undergoes examination. It is fully functional, but can be improved in several ways.


## Usage guidelines

Add file `index.html` to GoldenDict following the [guide for HTML dictionaries][4].

Headwords are represented in three forms:

* Greek script polytonic: φιλέω
* Greek script w/o diacritics: φιλεω
* Latin script: filew

Transliteration schema:

```
αβγδεζηθικλμνξοπρςστυφχψωϝϟ
abgdezhqiklmncoprsstufxywfk
```


## License


<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br/>
This work is distributed as <a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">Public Domain</a>.


[1]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-10-31b
[2]: {{ site.baseurl }}{% link docs/docs.md %}
[3]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
