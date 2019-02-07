# LlamaCSS-FW
I will start working on a CSS FrameWork, I will upload it here.

I will try to make it as simple as possible. I will put no unnecessary features.
It will be kind of basic because I make it...

---
# Customize:
##Edit Colors:
It's really easy. go to `/palette/colors.css` and start edit the colors.

##Edit Font Sizes:
Again easy, go to `main.css` and there you'll find `:root` change the `font-size: 14pt` to whatever you like.

---
#Use:
##Basic:
There is/will be predefined styles for common elements, `<p> </p>`, `<h#> </h#>`, lists, forms, etc.

So there's no need to apply classes or IDs if you don't want to.
##Advanced:
####Default Colors:
You are be able to apply different colors to different elements (applied by giving a class of the color name in all lowercase):
- Red
- Yellow
- Green
- Cyan
- Blue
- Purple
- Black
- White
You can also customize the `primary` id and class style.

You can add a `B` in the end for a brighter color or `D` for a darker (also works with `.primary` & `#primary`).

Examples: `<p class="redB">This text should be red.</p>` `<h1 id="primaryB">This header should have the bright primary color.</h1>`

####Miscellaneous
#####Resize (classes)
- `noResize` - elements with this class can't be resized.
- `resize` - elements with this class can be resized both vertically and horizontally.
- `resizeH` - elements with this class can only be resized horizontally.
- `resizeV` - elements with this class can only be resized vertically.


---
# Credits:
NotoSans - Google
