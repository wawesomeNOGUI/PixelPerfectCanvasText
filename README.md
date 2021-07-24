# PixelPerfectCanvasText
A Mapping for Atari 2600 pixel characters that can be drawn without anti-aliasing on an html5 canvas.

The mapping means the x,y start of each character and the x,y end of each character in chunkyFont.png

# Use
```
//Don't Anti-Alias Scaled Images
ctx.imageSmoothingEnabled = false;
// replace 25, 25 with where you want to draw the character and 16, 16, for how you want to scale the character (each character is drawn in the png at 16x16 pixels)
ctx.drawImage(fontImg, fontMap["!"][0], fontMap["!"][1], fontMap["!"][2], fontMap["!"][3], 25, 25, 16, 16);
```

