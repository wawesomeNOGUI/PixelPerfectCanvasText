# PixelPerfectCanvasText
A Mapping for Atari 2600 pixel characters that can be drawn without anti-aliasing on an html5 canvas.

The mapping means the x,y start of each character and the x,y end of each character in chunkyFont.png

# Use
Here's an example for how to use atariPixelFont.js in javascript:
```
//Don't Anti-Alias Scaled Images
ctx.imageSmoothingEnabled = false;

//drawText is defined as: drawText(myContext, string, x, y, spacing = 16, scaleX = 16, scaleY = 16)
var myString = "Hello World!";
drawText(ctx, myString, 25, 25);

//drawColorText is defined as: drawColorText(myContext, string, color, x, y, spacing = 16, scaleX = 16, scaleY = 16)
drawText(ctx, myString, "#FF00FF", 50, 25);
```
# Credits
Thanks to http://members.bitstream.net/marksim/atarimac/fonts.html for the font! (I only changed the color to black and added a dash symbol to Atari Classic Chunky).

