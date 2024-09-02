---
layout: default
title: Documentation
---

# Hunspell: Help for your word searches

Because Latin is an inflected language and used different spelling conventions over its long existence, it can be difficult to determine the correct dictionary look-up form (or *lemma*) of a given word. For example, if you search for *junctus* (for the Classical *iunctus*) or *amaverat* (an inflected form of *amo*), you most likely won't get any hits.

**Hunspell** is a free spell checker that performs automatic lemmatization. In addition to inflections and letter variants, it can handle ligatures (*pæne* for *paene*) and diacritics (*curâ* or *malè*) that can otherwise complicate a word search.

If you misspell a word or enter one that Hunspell cannot lemmatize, it will offer a list of suggestions. (See image.)

{% include img-viewer.html img="img/hunspell-1.png" %}

**Note:** Unfortunately, Hunspell does not work well with Ancient Greek.

## Hunspell dictionaries

Hunspell is already loaded on GoldenDict. But before you can activate it, Hunspell needs its own dictionary. (Most dictionaries on this site are **not** compatible with Hunspell.) Currently, there are two good options for Latin:

- **[A Latin Spellchecker](https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries) by Karl Zeiler and Jean-Pierre Sutto.** (**Linux** users, download **[here](https://aur.archlinux.org/packages/hunspell-la)**.) This vast dictionary contains more than 130,000 words from all periods of Latin. (Click the link in step 1 of the instructions below to dowload the file directly.)
- **[A Classical Latin Spelling Dictionary](http://www.obta.uw.edu.pl/~draco/) by Konrad Kokoszkiewicz.** (Scroll to the very bottom of the linked page.) This strictly Classical lexicon is limited to words from before the end of the second century C.E.

**Note:** Both of these dictionaries can be used for spellchecking in other apps, including LibreOffice, Chrome, and Firefox.

## Set up Hunspell on GoldenDict

1. [**Download** the Hunspell dictionary](hunspell-la.zip) and extract the files. (In addition to possible Read Me or License files, your unzipped folder should contain two dictionary files: one in AFF format and one in DIC.)

1. In the **GoldenDict** app, navigate to the **Morphology** window:  
    1. In the menu bar, go to **Edit > Dictionaries**.
    1. Select the **Sources** tab in the Dictionaries window. (It should be selected by default; see image below.)
    1. Select the **Morphology** sub-tab.
1. Set your **Hunspell dictionary**:
    1. Press the **Change...** button, near the top of the **Morphology** window. This will open a popup window.
    1. Click on the **pulldown menu** at the top of the popup window, and navigate to where you saved your **Hunspell dictionary**.
    1. Select the **folder** that contains your Hundspell dictionary, and click **Open**.(You'll see the path to your selected dictionary appear in bar next to the **Change...** button.)

         **For Linux users:** If you installed dictionary as package, then the correct path will be `/usr/share/hunspell`.
    1. Enable (check on) "Latin Morphology," and press **OK**.

{% include img-viewer.html img="img/hunspell-2.png" %}
