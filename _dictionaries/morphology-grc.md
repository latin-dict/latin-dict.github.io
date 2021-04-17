---
title: Morphologia Graeca
author: Verkerk
year: 2020
tags: [Greek]
nickname: Morphologia-Graeca
categories: [greek]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

Morphology dictionary of **Ancient Greek** language. It contains 114,723 lemmas and more than 1,500,000 corresponding declinated/conjugated forms.


## Download

[Download][2] files compiled for dictionary shells. Files for other formats can be produced [by request][10].

Similar dictionaries:

- [Greek Analyses][11] (by Jacob Rosen) - StarDict and Babylon formats, based on [Diogenes][12].
- [Morphologia Graeca][13] (by yozhic) - ABBYY Lingvo format, based on [Perseus Hopper][14].


## Exemplum

{% include img-viewer.html img="img/morphology-grc-1.png" id="1" %}


## Sources

1. Verkerk, Philippe. _Eulexis: Ancient Greek lemmatisation tool, version 1.1._ (on-line), 2020. URL: <https://github.com/PhVerkerk/Eulexis_off_line/>.


## Usage

In spite of the fact that files are in the StarDict format, they were specifically adapted for GoldenDict, so they may be incompatible with other dictionary shells.

Desktop GoldenDict version is made to support "Extra search via synonyms" feature, which can be activated in menu Edit\|Preferences, tab Advanced. Placing this dictionary on the first place in the list, will automatically redirect all the following dictionaries to the lemma.

Along with the original headwords, keys with removed diacritics were added (ἔρως > ερως). If you find it inconvenient, remove file `morphology-grc.syn.dz` and re-index dictionary (menu File\|Rescan Files in desktop GoldenDict, or 'Re-scan dictionaries' in mobile version).


## License

<a rel="license" href="https://outils.biblissima.fr/fr/eulexis/aide/licence.html">
  <img alt="GNU GPLv3"
       style="filter: grayscale(1); -webkit-filter: grayscale(1);"
       src="https://www.gnu.org/graphics/gplv3-with-text-84x42.png"/>
</a> \
This work is licensed under a [GNU GPLv3 License](https://outils.biblissima.fr/fr/eulexis/aide/licence.html).

[1]: https://github.com/latin-dict/{{ page.nickname }}
[2]: https://github.com/latin-dict/{{ page.nickname }}/releases
[3]: {{ site.baseurl }}{% link docs/docs.md %}
[10]: {{ site.baseurl }}{% link about.md %}
[11]: http://www.mobileread.mobi/forums/showthread.php?t=256360
[12]: https://d.iogen.es
[13]: https://mega.nz/folder/SlAFzIgA#ncZrAHvLuDIMDS_KzGhWOg/file/ylxShDCA
[14]: http://www.perseus.tufts.edu/hopper/morph
