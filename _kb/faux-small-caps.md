---
layout: type
serial: kb-subpage-faux-small-caps
title: Faux Small Caps
deck: "What are faux small caps? How can we spot them?"
---

Faux small caps happen when we scale down a capital letter to the same x-height as a lower case letter. What happens here is that the weight of the glyph gets scaled down too much compared to the lower-case letter next to it.

![Faux Small caps]({{site.url}}/svg/kb/faux-small-caps.svg){:width="80%"}

When a font doesn't contain a small cap, some page layout software scales down the glyph. This causes a faux small cap.

Note that small caps are sometimes slightly larger than the x-height of the lower case glyphs. There are also **petite caps**, which are exactly the same x-height as the lower case glyphs.

### How do I know?

You should be able to see the difference between real small caps and faked ones. If you're concerned you can't, simply consult the Glyphs panel to see if they're there.

![Faux Small Caps Example]({{site.url}}/svg/kb/faux-small-caps-example.svg){:width="90%"}

In the example above you can see how the weight of the capital compared to the rest of the phrase is incorrect in the lower example. It's a fairly subtle difference, but it's there.

### CSS & Small Caps

If you wish to use small caps in a web page you're designing, you'll need to invoke them in a specific way.

One would think that using <span class="command">font-variant: small-caps</span> would do the trick in all circumstances. Unfortunately, it doesn't always work. All this is going to do is have the browser render faux small caps, if they aren't available in the typeface design.

<div style="font-family: 'Arial'; font-size: 2.5rem; font-variant: small-caps;">This is in faux small caps.</div>

<div style="font-family: FiraSans-Regular; font-size: 2.5rem; font-variant: small-caps;">This is in real small caps.</div>

You need to make sure your typeface includes small caps the same way you do in InDesign.

![Scaled Capitals]({{site.url}}/svg/kb/scaled-capitals.svg){:width="90%"}

Either way, it is generally frowned upon to scale a letter within a word. The weights of each character are affected. It just looks bad.
