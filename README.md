# Curtis CSS Typeface

Curtis is the name I’ve given for a family of geometric sans-serif fonts. Other incarnations exist as Fontstructions: [Curtis Heavy](http://fontstruct.fontshop.com/fontstructions/show/180805) and [Curtis Pixel 14](http://fontstruct.fontshop.com/fontstructions/show/curtis_pixel_14). This version takes form in CSS. All shapes are rendered by the browser, using a combination of background color, border width, border radius, and a heavily reliance on absolute/relative positioning. You can get a better idea of how the letters were formed with the Inspect display option.

Each character is wrapped in a `<span>` and then depending on the complexity of that character, more empty `<span>` elements are added to the markup to render each shape. Here's the markup for R:

``` html
<span class="css_char r">
  R
  <span class="inside split_vert"></span>
  <span class="outside split_vert"></span>
  <span class="stroke"></span>
  <span class="fill"></span>
</span>
```

The Curtis CSS font wasn’t conceived of any practical application. I was more interested in seeing if it could be pulled off, and if so, what the final result would look like.

This design pattern is released under a [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/us/). You are free to share and remix this work.
