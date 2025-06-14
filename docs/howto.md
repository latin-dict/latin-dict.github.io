---
layout: default
title: Documentation
---

# GoldenDict quick start guide

GoldenDict is our recommended dictionary shell app. It's loaded with features, supports many dictionary formats, and it's free.

Since GoldenDict is open source, you can find variations of it from various sources. For instance, the original [GoldenDict](http://goldendict.org) has been dormant for years, although it still works. All new features, however, are implemented in a [GitHub fork](https://github.com/xiaoyifang/goldendict/releases) supported by user [@xiaoyifang](https://github.com/xiaoyifang/goldendict).

**Download** the latest version of GoldenDict here:

* [Windows](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Windows).
* [macOS](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Mac-OS-X).
* [Linux](https://flathub.org/apps/io.github.xiaoyifang.goldendict_ng). (Or try [AppImage build](https://github.com/Abs62/goldendict/releases).)

**Note:** Some dictionaries from our collection (especially HTML dictionaries) are not yet compatible with xiaoyifang's version. SLOB files should work fine though.

## Working with dictionary files

Once you instal GoldenDict, you can start adding the dictionary files that you download from this site. The instructions below give advice on downloading, adding, and updating dictionaries.

**Note:** The process for adding files depends of the file format. Check your file type and follow the appropriate instructions.

### Download a dictionary file

Follow these steps to ensure your dictionary file your select is correctly downloaded and compatible with GoldenDict:

1. **Select** your desired dictionary file.

    Browse the Latin Dictionary site, then select files that end with either "slob.zip" or "html.zip" and ignore any named "Source code."
1. If your downloaded ZIP file doesn't automatically expand, **double click** on it.

    You should end up with a folder containg at least one file. For example, if you downloaded Lewis' An Elementary Latin Dictionary, you should have a folder titled Lewis1890-slob, which contains the file Lewis1890-lat-eng.slob.
1. **Save** the extracted folder and its contents on your computer.

    **Note:** If you plan on downloading multiple dictionaries, it's a good idea to save them in single location for easy access.

### Add a SLOB dictionary

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Sources** tab in the Dictionary window. (It should be shown by default; see image below.)
1. Press **Add**. This will open a popup window.
1. Click on the **pulldown menu** at the top of the popup window, and navigate to where you keep your dictionaries. Select the folder that contains the dictionary you want to add, and click **Open**. (You'll see the path to your selected dictionary appear in the Sources tab.)
1. Press **OK** to confirm and exit the Dictionaries window.

{% include img-viewer.html img="img/goldendict-2.png" %}

### Add an HTML dictionary to GoldenDict

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Websites** tab in the Dictionary window. (See image below.)
1. Press **Add**. A blank new entry will appear in the Websites window. (See the highlighted line in the image below.)
1. Fill in the entry items as follows:

    * Enabled: ☑ (on)
    * As link: ☑ (on)
    * Name: Give this dictionary a name. (Anything is OK.)
    * Address: Enter the filepath to the HTML dictionary file saved on your computer. It should look like this: `file:///C:/Users/user/Documents/Eulexis-html/index.html`.
    
        **Note:** The app provides `http://` by default. Be sure to change this to `file:///`, and then add your filepath.

1. Press **OK** to confirm and exit the Dictionaries window.

{% include img-viewer.html img="img/htmldict.png" %}

### Update a dictionary

To upadate and installed dictionary, simply replace the original folder saved on your computer with the new release. Then in the menu bar, go to File&nbsp;>&nbsp;Rescan Files.
