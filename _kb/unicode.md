---
layout: type
serial: kb-subpage-unicode
title: Unicode
deck: "Historically, there have been different technologies to display type on a computer in different countries. Unicode is an international standard to ensure most of the world's writing systems can be properly displayed."
---
The Unicode system include approximately 150,000 glyphs from over 160 writing systems. You can see a [list of writing systems here](https://unicode-table.com/en/blocks/). It also defines the international standards for over 3,500 emoji. The standard has a goal of bringing together all the disperate systems which have developed in time, throughout the world.

### How It Works

The Unicode system is comprised of codes which are transformed into bytes of information on your computer. The codes look like this, `U+0026`, which is **&**, the ampersand. It's always `U+` followed by four or five digits. This encoding allows for over one million assignable codes.

The code is like a structure on which the glyph is painted. Different operating systems can apply their own paint to a code. That's why emoji look different on iOS compared to Windows or Facebook. Each paints their own emoji artwork on a Unicode code.

<span style="font-size: 48px;">U+1F602 = 😂</span>

This particular one is described as *face with tears of joy*. You can see what how each platform paints emoji [on this site](https://unicode.org/emoji/charts/full-emoji-list.html#1f602).

### Why Should I Care?

First, it's simply important to know how the tools of your trade work.

Have you ever gotten strange, jumbled characters when you imported text into InDesign? That is caused by incorrect character encoding. If you save the text file to UTF-8 encoding, it will render the problem glyphs properly in InDesign.

Character encoding can affect our daily lives as designers.

### Unicode and Typography

When a typographer designs a typeface, they're painting their design onto each Unicode code. The typographer has the choice of how many of the codes they're going to use. Most typefaces only include what the typographer judges is the necessary complement of glyphs for a given writing system (Latin, Cyrillic, Hebrew, etc…)

If there's a **&#x2612;** in it in your text, that's because the typeface does not include a glyph for that code. [This is a great web site](https://unicode-table.com/en/) to find Unicode information.

### How Can I Use Unicode?

In InDesign, you can use Unicode to search and replace glyphs. There's a GLYPHS tab in the `Find/Change` dialogue. It allows you to find a glyph, then replace it with the code for a new one. You could, for example, replace this 16/4 with 16 &#x00F7; 4.

In HTML, you can include any Unicode glyph by wrapping it in `&#xCODE;`. So `&#x00BC;` will give you &#x00BC; rather than 1/4.

No matter which platform you're using, you can always search for a Unicode code to insert a specific glyph in your designs. The only caveat is that it's designed into the typeface you're using.