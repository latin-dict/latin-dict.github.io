---
layout: default
title: Documentation
---

# Dictionary shells
## Preface

Choosing dictionary shell, one need to take in account two questions:

1. Does the application support the format of the dictionaries you have?
1. Does it provide effective search through your collection?

We publish our dictionaries in a **XDXF**, **Slob**, **StarDict**, and **MDict** formats, so it is likely you will find compatible shell easily.

Concerning the second question, Hunspell library is the most advanced method to the date. For example, using Hunspell and querying for words "amare", "amavistis", "amabam", user will receive the same article with canonical headword "amo". Section ["Hunspell"]({{ site.baseurl }}{% link docs/hunspell.md %}) tells more about Hunspell.


## Desktop

[GoldenDict](http://goldendict.org/) is leaving no alternative desktop dictionary shell. It works on Windows, Linux, and MacOS, and supports great variety of file formats. To the date it is the most functional application for work with dictionaries, and talking about Latin language you would not find more appropriate software. Read article ["Quick Start"]({{ site.baseurl }}{% link docs/howto.md %}) about initial configuration of the GoldenDict.


## Mobile

Situation around mobile dictionary shells is not such good. Some of them correctly recognize dictionaries, but do not provide good search, or support one format very well but do not accept other files from your collection. Below we list some software but cannot recommend absolutely satisfying one:

* [Aard 2](http://aarddict.org/) (Android) — open source application. Use **Slob** format.
* [Alpus](https://alpusapp.com/index.html) (Android, iOS) — commercial, _Free Edition_ works with up to 5 dictionaries. Interface is somewhat confusing, but it supports many formats and could import merely every Latin dictionary you could find in the Internet. We provide **XDXF** and **StarDict** files for this application.
* [GoldenDict Mobile](http://goldendict.mobi/) (Android) — commercial, _Free_ version limits number of active dictionaries to 5. Use **StarDict** files.
* [BlueDict](http://www.ssdlsoft.com/bluedict/) (Android) — Chinese application (see on [Google Play](https://play.google.com/store/apps/details?id=cn.ssdl.bluedict)) supporting only **MDict** format. However, it has morphology search (read ["Hunspell"]({{ site.baseurl }}{% link docs/hunspell.md %}) for details).

More mobile shells could be found in [this discussion](https://github.com/nikita-moor/latin-dictionary/issues/2). If you need some exotic format, please, [contact us]({{ site.baseurl }}{% link about.md %}).

