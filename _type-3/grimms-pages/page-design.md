---
layout: type3
serial: level-3-assignment-3-subpage-page-design
---
### Design Your Page

#### Text Alignment

This project will have you using left-justified type. If you look at the graphic below, you'll see that this is different than left-aligned text. With left-justified text, you have no rag. Only the last line of the paragraphs are left-aligned.

![Text Alignment Left justified]({{site.url}}/svg/text-alignment-left-justified.svg){:width="50%"}

A large majority of the text you'll set in your career will be simply left-aligned. Some will be left-justified. The others are used less frequently, and only in specific contexts that require them.

#### Option #1: The Perfect Page 

There are many formula for creating the single-column grid. Most of them are trash, myths. There are others which are actually useful. The first is the Van de Graaf Canon. Let's dive in!

J.A. van de Graaf created the [Van de Graaf Canon](https://duckduckgo.com/?q=Van+de+Graaf+Canon&iar=images&iax=images&ia=images){:target="_blank"}. This is a formula to create a harmonious single-column pages.

  **We're not going to use this type of grid.** I just want you to be aware of it.

![Van De Graaf Canon]({{site.url}}/svg/van-de-graaf-canon.svg){:width="80%"}

Using these guides, no matter the dimensions of the pages, the margins will always have the same ratio. This creates margins with a ratio of: inner margin 2, top margin 3, outer margin 4, and bottom margin 6, or 2:3:4:6. We can also express this as 1/9 and 2/9 of the page.

There are other page layout canons. You can [see them here](https://en.wikipedia.org/wiki/Canons_of_page_construction){:target="_blank"}.

#### Option #2: The Economical Approach

Here, we're going to take a more practical approach to our page layout. All we need is enough margins to accommodate the binding on the inside, our thumbs on the outside, running headers at the top and folios at the bottom.

![Economical Layout]({{site.url}}/svg/grimms-pages/economical-layout.svg){:width="80%"}

Your pages will measure 11cm by 19cm. You'll choose your margins. The inside margins should be larger than the outside margins.

### The Colour of the Page

The phrase *colour of the page* doesn't literally refer to colour itself. It refers to what the page looks like if you print one, hold it at arm's length, then blur your vision. How light or dark grey is the page? The density of the content is the colour of the page. There are many factors that affect page colour, type selection, type weight, leading and letter-spacing. See some examples in this PDF.

<a href="https://www.dropbox.com/s/b3zqqafvrb8jv8e/colour-of-the-page.pdf?dl=1" title="Download the PDF" target="_blank">![Download a PDF]({{site.url}}/svg/button-download-pdf.svg){:width="40%"}</a>

> Your page should have somewhere around 28 lines of text and 9-12 words per line. Consult the Info panel for the numbers.

The goal is to create a harmonious page, free of distracting graphic elements.

|   Page Size   |            |
|:-------------:|:----------:|
|   Width       |   11.6cm   |
|   Height      |   19.2cm   |

#### Composition

With no document open, open the settings for your <span class="commmand">Basic Paragraph</span> style. Go to <span class="command">Justification</span> to enter this.

|          | Minimum   |   Desired   |   Maximum   |
|:--------:|:----------:|:----------:|:-----------:|
|   Word Spacing   |   96%   |   100%   |   104%   |
|    Letter Spacing   |   -3%   |   0%   |   3%   |
|   Glyph Scaling   |   96%   | 100%   |   104%   |

Set <span class="command">Single Word Justification</span> to <span class="command">Align Left</span>.

These numbers are a starting point. They're not written in stone. They're better than what Adobe set as defaults, but if they don't work for you, adjust them.

  <figure>
	<img src="{{ site.baseurl }}/svg/indesign-composition-highlighting.svg" alt="Highlighted bad word spacing.">
  <figcaption>
    The yellow highlighting indicates that there's bad letter and word spacing.
  </figcaption>
  </figure>

You'll know you're settings are incorrect if there is yellow highlighting on your InDesign pages. You can see bad and good justified text in the PDF file linked below. To see this highlighting, go to <span class="command">InDesign > Preference > Composition</span>, turn on <span class="command">H&J Violations</span>.

<a href="https://www.dropbox.com/s/tceqy4n160vpwsn/good-vs-bad-justification.pdf?dl=1" title="Good Vs Bad Justification" target="_blank">![Download a PDF]({{site.url}}/svg/button-download-pdf.svg){:width="40%"}</a>

> Remember! You're using first line indents—not spaces between paragraphs.

#### Rivers

Rivers are unfortunate spaces which vertically span lines of text. They're mostly a thing of the past. InDesign takes care of this for us. [This is what they look like](http://www.edgee.net/wp-content/uploads/2014/05/justified_rivers.png){:target="_blank"}, just in case.

#### Hyphenation

In your body copy paragraph style, be sure to go to your Hyphenation settings. Change them to:

|   Words with at least   |   6   |   letters   |
|   After first   |   3   |   letters   |
|   Before last   |   3   |   letters   |
|   Hyphen limit   |   2   |   hyphens   |

Un-check all the check boxes.

Hyphenation zone is irrelevant with justified type.

#### Optical Margin Alignment

With no document open, go <span class="command">Window > Type & Tables > Story</span>. In that panel, check the box, then set the type size to 9, which is an average body copy point size.


  ![Optical Margin Alignment]({{site.url}}/svg/story-panel-optical-alignment.svg){:width="90%"}

This will make text on the left margin hang out of the text frame to create an optically aligned margin. Though it may look strange here, when it's at a normal size, it makes the edge of the text actually look straight.

#### Widows & Orphans

We can use InDesign's settings to get rid of *most* widows and orphans. The rest we must fix manually. We'll explore <span class="command">Keep Options</span> in your Paragraph Style for the body copy.