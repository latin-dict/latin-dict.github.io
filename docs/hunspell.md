---
layout: default
title: Documentation
---

# Hunspell: words normalization

Latin is an inflected language, so a word could have several forms but dictionaries usually contain only its normal form, such as nominative singular for nouns. For this reason, one cannot simply copy an unknown word into GoldenDict, but has to manually type its correct form.

Hunspell is a spell checking system, also able to produce lemmas, i.e. normal forms of the words, so, for example, word "puellam" will be transformed to "puella", which significantly simplifies work with dictionaries. Other examples of normalization are ligatures, "pæne" > "paene", and diacritics, "curâ" or "malè".

**Note:** Hunspell helps finding lemmas of Latin language, but it does not work so with Ancient Greek.

Hunspell by itself needs a dictionary. To the date we could choose between two variants:

1. Dictionary by [Karl Zeiler and Jean-Pierre Sutto][1]
1. Dictionary by [Konrad Kokoszkiewicz][2] (at the very bottom of the page)

The first dictionary is the most universal, the second contains strictly classical lexicon (to the end of 2nd century AD). Each dictionary should work fine with GoldenDict. Additionally, they could be used for spellchecking in LibreOffice, Chrome, Firefox, &c.


# Setting up

## GoldenDict (desktop)

**Note:** Users of Linux could install Hunspell dictionaries as ordinary applications (see Software Center or something alike). For example, Arch Linux [provides a package][3] based on the dictionary of Karl Zeiler and Jean-Pierre Sutto. After installing, follow the step 3 in the list below, or start from beginning if your distributive has no Hunspell dictionary for Latin language.

Procedure is simple:

1. [Download the dictionary](hunspell-la.zip) and extract files (Karl Zeiler's variant).
1. Start GoldenDict, open menu Edit > Dictionaries, tab Sources > Morphology.
1. Change "Path to a directory with Hunspell/Myspell dictionaries" to the folder where you saved the files. (**Linux:** if you installed dictionary as package, then the correct path will be "/usr/share/hunspell".)
1. Enable (check on) "Latin Morphology" in the list.
1. Press OK. Try typing an incorrect word, you should see the list of spelling suggestions (see image).
1. If not, open settings (Edit > Dictionaries), and on the tab Groups add "Latin Morphology" to the group.

{% include img-viewer.html img="img/hunspell-1.png" %}

## GoldenDict Mobile

Copy files `la_LA.aff` and `la_LA.dic` to the phone's SD card, into the GoldenDict folder. Run application, it will recognize them as a new dictionary.

## BlueDict (mobile)

Mobile application [BlueDict][5] for Android could use special [morphology dictionary][6]. Registration is required for download from the website (all in Chinese). Probably, this file could be used in other applications reading MDict format, but it was not tested.

## MDict (mobile)

[MDict][4] supports unmodified Hunspell dictionaries. Files `la_LA.aff` and `la_LA.dic` should be copied into the "/mdict/data/" folder.


[1]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
[2]: http://www.obta.uw.edu.pl/~draco/
[3]: https://aur.archlinux.org/packages/hunspell-la
[4]: https://www.mdict.cn/
[5]: http://www.ssdlsoft.com/bluedict/
[6]: https://www.pdawiki.com/forum/forum.php?mod=viewthread&tid=19511

