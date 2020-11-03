---
title: Janua linguarum reserata
author: Comenius
year: 2014
tags: [Greek, Latin]
nickname: Comenius2014
categories: [greek]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

**Ancient Greek** vocabulary translated to **Latin** was extracted from the "Janua Linguarum Reserata cum Graeca versione" (see Sources) and contains about 7,000 records (after reduplication).


## Download

Download [files compiled for dictionary shells][1] or view [source files][2]. Format Slob is recommended for GoldenDict, read [documentation][3] about other dictionary shells.


## Exemplum

{% include img-viewer.html img="img/Comenius2014-1.png" id="1" %}


# Sources

Our dictionary is based on the book of Felipe Vogel \[1\]. Title page states that it is a transcript of the book published in 1665 \[2\], however in place of French text the third collum contains Greek vocabulary. Source of this vocabulary is unknown, probably it was added by Felipe Vogel from one of latter editions of the book, such as \[3\].

1. Comenius, John Amos; Simon, Theodor; Courcelles, Étienne de; Vogel, Felipe; Lionello, Roberto; Gibbons, Randy. _Janua Linguarum Reserata cum Graeca versione._ Online, 2014. URL: <https://archive.org/details/comenius-janua-reserata>.
1. Comenius, John Amos; Simon, Theodor; Courcelles, Étienne de. _Janua Linguarum Reserata cum Graeca versione._ Amsterdam, 1665. URL: <https://books.google.com/books?id=E81mAAAAcAAJ>. 
1. Comenius, John Amos; Simon, Theodor; Teucher, Ludwig Heinrich. _Janua linguarum aurea reserata in linguam graecam._ Leipzig, 1789. URL: <https://archive.org/details/bub_gb_WGNcAAAAcAAJ/page/n114>. 


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


[1]: https://github.com/latin-dict/{{ page.nickname }}/releases
[2]: https://github.com/latin-dict/{{ page.nickname }}
[3]: {{ site.baseurl }}{% link docs/docs.md %}
[4]: {{ site.baseurl }}{% link docs/howto.md %}#html-dictionaries
