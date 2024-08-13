---
layout: default
title: Documentation
---

# GoldenDict quick start guide

GoldenDict is our recommended dictionary shell app. It's loaded with features, supports many dictionary formats, and it's free.

**Download** the latest version of GoldenDict here:

* [Windows Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Windows).
* [macOS Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Mac-OS-X).
* [Linux](https://flathub.org/apps/io.github.xiaoyifang.goldendict_ng). Another option is [AppImage build](https://github.com/Abs62/goldendict/releases).

(Since GoldenDict is open source, you can find variations of it from various sources. For instance, the original [GoldenDict](http://goldendict.org) has been dormant for years, although it still works.)

All new features are implemented in a [GitHub fork](https://github.com/xiaoyifang/goldendict/releases) supported by user [@xiaoyifang](https://github.com/xiaoyifang/goldendict). Note, however, that some dictionaries from our collection (especially HTML dictionaries) are not yet compatible with xiaoyifang's version. SLOB files should work fine though.

## Working with dictionaries in GoldenDict

To use the dictionaries on this site, you must add them to GoldenDict.
Install the app, and then follow these steps:

### Prepare a dictionary file

1. **Download** your desired dictionary file. *Browse the Latin Dictionary site, then select files that end with either "slob.zip" or "html.zip" and ignore any named "Source code."*
1. If your downloaded ZIP file doesn't automatically expand, **double click** on it. *You should end up with a folder containg at least one file. For example, if you downloaded Lewis' An Elementary Latin Dictionary, you should have a folder titled Lewis1890-slob, which contains the file Lewis1890-lat-eng.slob.*
1. **Save** the extracted folder and its contents on your computer. *If you plan on downloading multiple dictionaries, it's a good idea to save them in single location for easy access.*

### Add a SLOB dictionary to GoldenDict

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Sources** tab in the Dictionary window. *It should be shown by default; see image below.*
1. Press **Add**. *This will open a popup window.*
1. Click on the **pulldown menu** at the top of the popup window, and navigate to where you keep your dictionaries. Select the folder that contains the dictionary you want to add, and click **Open**. *You'll see the path to your selected dictionary appear in the Sources tab.*
1. Press **OK** to confirm. *Now your're now ready to look up words.*

{% include img-viewer.html img="img/goldendict-1.png" %}

**Note:** if you organized dictionaries into groups (menu Edit > Dictionaries, tab Groups), then the new dictionary will not be added automatically. In such a case, on the step 4 in place of "OK" press "Apply", then on the tab Groups add new dictionary into the desired group.

### Add an HTML dictionary to GoldenDict

1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Websites** tab in the Dictionary window.
1. In GoldenDict, open menu Edit > Dictionaries.
1. Switch to the tab Websites.
1. Press **Add**. *A blank new entry will appear in the Websites window.*
1. Fill in the entry items as follows:

    * Enabled: ☑ (on);
    * As link: ☑ (on);
    * Name: Enter anything you like;
    * Address: `file:///C:/Users/user/Documents/Eulexis-html/index.html` (Adapt this to match the path to your HTML dictionary file; it should start with 'file:///'.)
1. Press **OK** to confirm. *Now you're ready to look up words.*

### Update a dictionary

To upadate and installed dictionary, simply replace the original folder with the new release. Then in the menu bar, go to File&nbsp;>&nbsp;Rescan Files.
