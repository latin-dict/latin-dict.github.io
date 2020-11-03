---
layout: default
title: Documentation
---

# Custom styles

All dictionaries of this project are made to be equally usable with original and custom styles, so every user should decide install new styles or not.

Styles provided by this project fix several formatting problems: reduce line-space between headwords, add indent of subclauses in dictionary articles, remove parentheses around of the `<co>` elements, add formatting to examples (`<ex>` element).

Original (left) and custom (right) styles:

{% include img-viewer.html img="img/styles-1.png" id="1" %}
{% include img-viewer.html img="img/styles-2.png" id="2" %}

Some dictionaries are made of page images. Special styles add feature to show full image on click on the preview. If you do not use custom styles, you will need to double click on the preview, then the full image will be opened in external image viewer.

{% include img-viewer.html img="img/styles-3.png" id="3" %}

You may want to change the maximum size of the image. For that purpose tune parameter "height":

```css
.nikita-moor-image {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 999;
    height: 800px;
    max-height: 98%;
}
```


# Setting up

File "article-style.css" is included into every release, and could be [downloaded][1] from the repository. GoldenDict looks for it in the next folders:

* Linux: `~/.goldendict`
* Windows: `%APPDATA%\GoldenDict`

Copy-past this path into the address bar of your file browser, press Enter, and save file there. If you already have your own styles definition, then add new content to the end of the file. Read [GoldenDict's wiki][2] for additional information.


[1]: https://github.com/nikita-moor/latin-dictionary/blob/master/utils/article-style.css
[2]: http://goldendict.org/wiki/index.php/FAQ#How_do_I_change_the_font_used_for_the_articles.3F_Or_alter_its_appearance_in_any_other_way.3F

