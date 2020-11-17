---
title: Lexicon Latinae Linguae Antibarbarum
author: Nolte
year: 1744
tags: [Latin]
nickname: Nolte1744
categories: [scientific]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

This **Latin** (with some **German** notes) treatise is a guide to the purification of the Latin language and contains about 8800 articles explaining meaning, syntactic arrangement and prosody of doubtful words.


## Download

[Download][2] files compiled for dictionary shells. Format Slob is recommended for GoldenDict, read [documentation][3] about other dictionary shells.


## Exemplum

{% include img-viewer.html img="img/Nolte1744-1.png" id="1" %}
{% include img-viewer.html img="img/Nolte1744-2.png" id="2" %}


## Sources

1. Nolte, Johann Friedrich. _Lexicon Latinae Linguae Antibarbarum Quadripartitum._ Leipzig, 1744. URL: <http://mateo.uni-mannheim.de/camenaref/nolte.html>.


## States and limitations

Appendix "Series Latinorum Scriptorum" is not included into our version.

Headwords were changed to lowercase to be compatible with Hunspell dicitonary, but it can break some logic related to the words which should to be in title-case. For example, Hunspell is not able to recognize that "hispana" is a form of "Hispanus". Besides the letter case, headwords were left without change, so distinct articles will be found on "amo" and "amare". Verbs are usually in a form of infinitive or first-preson; nouns can have any of inflectional forms; short phrases and sentence are also common.

We recommend using "Search Pane" in GoldenDict to have access to the lookup hints (menu View\|Search Pane). 

Some keywords are not marked in the text, e.g. "caritas" in the article about "amor", or "basia" in "oscula" (see images above), so these words are not indexed.


## License

[![CC BY-SA](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/3.0/)\\
This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-sa/3.0/).


[1]: https://github.com/latin-dict/{{ page.nickname }}
[2]: https://github.com/latin-dict/{{ page.nickname }}/releases
[3]: {{ site.baseurl }}{% link docs/docs.md %}
