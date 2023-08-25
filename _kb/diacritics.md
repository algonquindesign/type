---
layout: type
serial: kb-subpage-diacritics
title: Diacritics
deck: "What we commonly call <i>accents</i> are formally known as <i>diacritics</i>. So much content designers work with is <i>en français</i>, which includes many diacritics. Let's learn more about them here."
---
*Diacritic* comes from the Greek, meaning *distinguishing*. They are marks which modify a glyph. The term *diacritic* is the formal typographic term for *accents*. The most common ones known to Canadians are French accented characters. So we can say we're typing *diacritics*, or *diacritical marks*.

Most diacritics in english are borrowed from the French. There's *résumé*, *café*, and *façade*, for instance. The accents are sometimes omitted in written English.

To type these on macOS, you simply need to hold down the letter on the keyboard. In macOS apps, the contextual menu will appear. Each entry is numbered. Just type the number to choose one.

![Diacritics menu on macOS]({{site.url}}/svg/kb/diacritics-macos-menu.svg){:width="50%"}

Some applications, like Adobe apps, don't support the contextual menu. In these circumstanced, you can type the following;

<span style="font-size: 2rem; color:B3B3B3;">Option-e then e, for</span>
<span style="font-size: 2rem; color:2997FF; font-family:FiraSans-Medium;">é</span>

<span style="font-size: 2rem; color:B3B3B3;">Option-\` then e, for</span>
<span style="font-size: 2rem; color:2997FF; font-family:FiraSans-Medium;">è</span>

<span style="font-size: 2rem; color:B3B3B3;">Option-i then e, for</span>
<span style="font-size: 2rem; color:2997FF; font-family:FiraSans-Medium;">ê</span>

### In HTML

In the head of your HTML document, be sure to set the character encoding to UTF-8 like this;

`<meta http-equiv="Content-Type" content="text/html; charset=utf-8">`

That will allow you to simply type the glyphs as shown above. They'll appear properly on your pages. This is because glyphs such as é are included in the [UTF-8 character set](https://www.fileformat.info/info/charset/UTF-8/list.htm).