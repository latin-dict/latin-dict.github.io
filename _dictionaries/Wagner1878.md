---
title: Lexicon Latinum
author: Wagner
year: 1878
tags: [Latin, French]
nickname: Wagner1878
comment: suspended
categories: [synonyms]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

This phraseological dictionary of **Latin** language contains translation of words to **French**, synonyms, antonyms, adjectives or adverbs applicable to these words, and example phrases from classic Latin works. Addendum folds in an index of Latin neologisms **[Lat-Lat]**, profesisonal lexicon **[Fra-Lat]**, and **French-Latin** dictionary.

**Early developer version**; part 1/18 — words from A to ANGUSTUS. [Full version of the dictionary][3] (indexed page scans) is available on the [web-site of Godmy][4] (also known as Martinus Bohemus). Personally I am not interested in this dictionary, so future development is not expected to be active.

For download see [Release][101] section; development version and source files are in the [github repository][1].


## Exemplum

{% include img-viewer.html img="img/Wagner1878-1.png" id="1" %}
{% include img-viewer.html img="img/Wagner1878-2.png" id="2" %}


## Sources

1. Wagner, Franz S. J.; Borgnet, Auguste. _Lexicon latinum seu Corpus Phraseologiæ._ Brugis, 1878. URL: <https://archive.org/details/LexiconLatinum> \[Accessed 4 March 2019\].
1. On-going transcribe project. URL: <https://www.pgdp.net/c/project.php?id=projectID5b3d9b5f27ee1> \[Accessed 4 March 2019\].


## Usage guidelines

XDXF edition has embedded functionality for hiding citations (see exempla above) which requires using [special styles][2] different (**sic!**) from [custom styles][103] recommended for our dictionaries (they could be concatenated though).


## States and limitations

Format and structure of the dictionary hardly fit the XDXF format. _Draft version_ fails test agains DTD schema and probably will diverge more from the XDXF format in future editions. This file was tested only in GoldenDict and could be incompatible with other dictionary shells.


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


[1]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[2]: https://github.com/nikita-moor/latin-dictionary/blob/master/Wagner1878/article-style.css
[3]: http://www.lexica.linguax.com/wagner.php
[4]: http://www.lexica.linguax.com/

{% include dicitonary_ref.md %}

