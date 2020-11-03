---
title: Theatrum Latino-Germanico-Graecum
author: Reyher
year: 1712
tags: [Latin, German, Greek]
nickname: Reyher1712
categories: [latin]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

**Latin** headwords are explained in both **Latin** and **German** languages. In spite of the word "Graecum" in the book's title, Greek text was not transcribed, so our computer dictionary is only Latin-German.

Total number of the articles should be about 40000.


## Download

Current version is [v0.2 (February 20, 2020)][1]. Format Slob is recommended for GoldenDict, read [documentation][2] about other dictionary shells.

Source files are in the [github repository][3].


## Exemplum

Picture below shows the article after correction. Most of the articles are currently separated into independent paragraphs, German text is not highlighted, and Greek is absent.

{% include img-viewer.html img="img/Reyher1712-1.png" id="1" %}
{% include img-viewer.html img="img/Reyher1712-2.png" id="2" %}


# Sources

1. Reyher, Andreas. _Andreae Reyheri, Gymnasii Gothani Rectoris quondam meritissimi, Theatrvm Latino-Germanico-Graecum, Sive Lexicon Lingvae Latinae : In quo Ordine nativo Vocabvlorum Latinorum Origines, Genera, Flexiones, Significationes variæ, & Adpellationes Germanicæ pariter Græcæque, Similiter Formulæ loquendi præstantiores, Sententiæ, Facultatum Scientiarumque Locutiones peculiares, & Proverbia, Cum Oratoribus._ Wolfenbüttel, 1712. Lipsiae, 1712. URL: <https://archive.org/details/reyher1712>.
1. Reyheri, Andreae. _Theatrum Latino-Germanico-Graecum sive lexicon linguae latinae._ Herzog August Bibliothek Wolfenbüttel, 2012. URL: <http://diglib.hab.de/drucke/kb-19-2f/start.htm>.


# States and limitations

Transcript made by the HAB Wolfenbüttel lacks for semantic mark-up, so currently we could only draft headers. Paragraphs belonging to the same articles should be joined, but it requires manual proofing. In the future, we hope to add Greek text and mark up German words.


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/de/">
<img alt="Creative Commons License"
     style="border-width:0"
     src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" />
</a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/de/">Creative Commons Attribution-ShareAlike 3.0 License</a>.



[1]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-02-20
[2]: {{ site.baseurl }}{% link docs/docs.md %}
[3]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}

