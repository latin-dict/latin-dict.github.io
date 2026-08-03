---
layout: default
title: Documentation
---

# GoldenDict Quick Start Guide

GoldenDict is our recommended dictionary shell app. It's loaded with features, supports many dictionary formats, and it's free.

The original [GoldenDict](https://github.com/goldendict/goldendict/releases/) has been dormant for years, although it still works and is recommended as a stable solution. A newer fork [GoldenDict-ng](https://github.com/xiaoyifang/goldendict-ng/releases) has some minor compatibility issues but can also be used.

**Note:** Some HTML dictionaries from our collection are not compatible with GoldenDict-ng. SLOB files should work fine though.

## Working with dictionary files

Once you install GoldenDict, you can start adding the dictionary files that you download from this site. The instructions below give advice on downloading, adding, and updating dictionaries.

**Note:** The process for adding files depends on the file format. Check your file type and follow the appropriate instructions.

### Download a dictionary file

Follow these steps to ensure the dictionary file you select is correctly downloaded and compatible with GoldenDict:

1. Create a folder on your computer.
1. Download a dictionary and save it to the folder from step 1. Several dictionaries can be mixed in one folder.
1. If the dictionary is compressed into a ZIP archive, extract it. The target file should have an extension SLOB, MDX, or DICT.

### Add the dictionary

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Sources** tab in the Dictionary window. (It should be shown by default; see image below.)
1. Press **Add** and find the created folder.
1. Press **OK** to confirm and exit the Dictionaries window.

{% include img-viewer.html id="1" img="img/goldendict-2.png" %}

### Add an HTML dictionary to GoldenDict

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Websites** tab in the Dictionary window.
1. Press **Add**.
1. Fill in the entry items as follows:
  * Enabled: ☑ (on)
  * As link: ☑ (on)
  * Name: Give this dictionary a name. (Anything is OK.)
  * Address: Enter the filepath to the HTML dictionary file saved on your computer. It should look like this: `file:///C:/Users/user/Documents/Eulexis-html/index.html`.
1. Press **OK** to confirm and exit the Dictionaries window.

{% include img-viewer.html id="2" img="img/goldendict-3.png" %}

### Update a dictionary

To update an installed dictionary, simply replace the original file saved on your computer with the new release. Then in the menu bar, go to File&nbsp;>&nbsp;Rescan Files.
