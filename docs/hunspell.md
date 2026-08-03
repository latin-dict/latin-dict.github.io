---
layout: default
title: Documentation
---

# Hunspell: Help for your word searches

Because Latin is an inflected language and has used different spelling conventions over its long existence, it can be difficult to determine the correct dictionary look-up form (or *lemma*) of a given word. For example, if you search for *junctus* (for the Classical *iunctus*) or *amaverat* (an inflected form of *amo*), you most likely won't get any hits.

**Hunspell** is a free spell checker that performs automatic lemmatization. In addition to inflections and letter variants, it can handle ligatures (*pæne* for *paene*) and diacritics (*curâ* or *malè*) that can otherwise complicate a word search.

If you misspell a word or enter one that Hunspell cannot lemmatize, it will offer a list of suggestions. (See image.)

{% include img-viewer.html id="1" img="img/hunspell-1.png" %}

**Note:** Unfortunately, Hunspell does not work well with Ancient Greek.

## Hunspell dictionaries

Hunspell is already loaded on GoldenDict. But before you can activate it, Hunspell needs its own dictionary. Currently, there are two good options for Latin:

- **[A Latin Spellchecker](https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries) by Karl Zeiler and Jean-Pierre Sutto.** This vast dictionary contains more than 130,000 words from all periods of Latin. (Click the link in step 1 of the instructions below to download the file directly.)
- **[A Classical Latin Spelling Dictionary](http://www.obta.uw.edu.pl/~draco/) by Konrad Kokoszkiewicz.** (Scroll to the very bottom of the linked page.) This strictly Classical lexicon is limited to words from before the end of the second century C.E.

**Note:** Both of these dictionaries can be used for spellchecking in other apps, including LibreOffice, Chrome, and Firefox.

## Set up Hunspell on GoldenDict

1. [Download the Hunspell dictionary](hunspell-la.zip) and extract the files.
1. In the GoldenDict app, navigate to the **Morphology** window:  
    - In the menu bar, go to **Edit > Dictionaries**.
    - Select the **Sources** tab in the Dictionaries window. (It should be selected by default; see image below.)
    - Select the **Morphology** sub-tab.
1. Set your Hunspell dictionary:
    - Press the **Change...** button, near the top of the **Morphology** window. This will open a popup window.
    - Navigate to the folder where you saved the extracted Hunspell dictionary.
    - Click **Open**. (You'll see the path to your selected dictionary appear in the field next to the **Change...** button.)
    - Enable (check on) "Latin Morphology," and press **OK**.

{% include img-viewer.html id="2" img="img/hunspell-2.png" %}

# Mobile applications

Two dictionary shells for Android, [GoldenDict Mobile](http://goldendict.mobi/) and [MDict](https://www.mdict.cn), support Hunspell. While MDict provides an iOS version, we have not tested whether adding spelling dictionaries is possible there.

[**Download** the Hunspell dictionary](hunspell-la.zip) and extract the files `la_LA.aff` and `la_LA.dic`.

## GoldenDict Mobile

Copy files `la_LA.aff` and `la_LA.dic` to the phone's memory, into the GoldenDict folder. Run the application, and it will recognize them as a new dictionary.

## MDict

Copy files `la_LA.aff` and `la_LA.dic` to the phone's memory, into the "/mdict/data/" folder.
