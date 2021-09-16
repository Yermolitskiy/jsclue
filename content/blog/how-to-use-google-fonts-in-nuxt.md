---
title: How to use google fonts in nuxt
description: Very short guide, on how to import and implement google fonts.
slug: how-to-use-google-fonts-in-nuxt
img: https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fd%2Fd2%2FOFL_logo_rect_color.svg%2F250px-OFL_logo_rect_color.svg.png&f=1&nofb=1
---

# How to use <a href="https:/fonts.google.com/"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.designtagebuch.de%2Fwp-content%2Fuploads%2Fmediathek%2F2021%2F03%2Fgoogle-fonts-bildmarke-700x513.jpg&f=1&nofb=1"></a> in <a href="https:/nuxtjs.org/"><img src="https://nuxtjs.org/design-kit/colored-text.svg"></a>

First of all please navigate to <a href="https:/fonts.google.com/">Google Fonts</a>
<p>
Then search for a font that you like, using a search bar or just browse through the fonts.
</p>
<p>
Choose a font that you like, as an example <a href="https://fonts.google.com/specimen/Roboto">Roboto</a>
</p>
<p>
Choose a style that you like, by pressing a "+" symbol.
</p>
<p>
On the right side you will see a few fields, and radio buttons. Please choose @import radio button.
</p>
<p>
choose a layouts/default.vue (or you migh have another name of the file), in my case this is a file witth a default settings for the page, such as style as an example. Or it also can be used as a scoped style in a style section of any page.vue 
</p>
<p>
copy the style code displayed in the right column and copy it to the desired page or layout/default page, the code looks like this:
</p>
 &lt;style&gt; <br>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700;900&amp;display=swap');<br>
&lt;/style&gt; <br>
<p>
then add font-family code block that looks like the one below to the desired css class. 
</p>
<p>
CSS rules to specify families<br><br>

font-family: 'Electrolize', sans-serif;&lt;style&gt;<br>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700;900&amp;display=swap');<br>
&lt;/style&gt; <br>
<p>
    And that's it you have implemented a google fonts :)
</p>