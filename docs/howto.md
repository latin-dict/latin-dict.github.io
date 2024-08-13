---
layout: default
title: Documentation
---

# GoldenDict quick start guide

GoldenDict is our recommended dictionary shell app. It's loaded with features, supports many dictionary formats, and it's free.

**Download** the latest version of GoldenDict here:

* Windows: use [Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Windows).
* macOS: use [Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Mac-OS-X).
* Linux: install application from the software manager on your system; choose Qt5-based version if there are options. Another variant is [AppImage build](https://github.com/Abs62/goldendict/releases).

(Since GoldenDict is open source, you can find variations of it from various sources. For instance, the original [GoldenDict](http://goldendict.org) has been dormant for years, although it still works.)

All new features are implemented in a [GitHub fork](https://github.com/xiaoyifang/goldendict/releases) supported by user [@xiaoyifang](https://github.com/xiaoyifang/goldendict). Note, however, that some dictionaries from our collection (especially html dictionaries) are not yet compatible with xiaoyifang's version. Files in Slob format should work fine though.

## Working with dictionaries in GoldenDict

To use the dictionaries on this site, you must add them to GoldenDict.
Install the app, and then follow these steps:

### Download dictionaries
1. Click the **link** to your desired dictionary file. *On the Latin Dictionary site, look for files that end with either "slob.zip" or "html.zip" and ignore "Source code."*
1. Make sure your downloaded file has been extracted. *You should have a folder containg at least one file. For example, if you downloaded Lewis' An Elementary Latin Dictionary, you should have a folder titled Lewis1890-slob, which contains the file Lewis1890-lat-eng.slob. If you have just a file with a .zip extension, **double click** to extract it.*
1. **Save** the extracted folder on your computer. *If you plan on downloading multiple dictionaries, it's a good idea to save them in single location for easy access.*
### Add dictionaries to GoldenDict
1. In the GoldenDict menu bar, go to **Edit > Dictionaries**.
1. Select the **Sources** tab in the Dictionary window. *It should be shown by default; see image below.*
1. Press **Add**. *This will open a popup window.*
1. Click on the **pulldown menu** at the top of the popup window, and navigate to where you keep your dictionaries. Select the folder that contains the dictionary you want to add, and click **Open**. *You'll see the path to your selected dictionary appear in the Sources tab.*
1. Press **OK** to confirm.
1. Your're now ready to look up words.

{% include img-viewer.html img="img/goldendict-1.png" %}

**Note:** if you organized dictionaries into groups (menu Edit > Dictionaries, tab Groups), then the new dictionary will not be added automatically. In such a case, on the step 4 in place of "OK" press "Apply", then on the tab Groups add new dictionary into the desired group.


### HTML dictionaries

This type of dictionaries works similar to websites:

1. Download the most recent version of the dictionary.
1. Extract files from the archive.
1. In GoldenDict, open menu Edit > Dictionaries.
1. Switch to the tab Websites.
1. Press button "Add…" and fill new item:
  - enabled: ☑ (on);
  - as link: ☑ (on);
  - name: on your choice (does not matter);
  - address: `file:///C:/Users/user/Documents/Eulexis-html/index.html` (adapt it to the real path to "index.html"; it should start with 'file:///'; use "forward" slashs instead of backslash).


## Updating dictionary

If you are updating an old dictionary, simply replace it with files from new release. Then open menu File&nbsp;>&nbsp;Rescan Files.
