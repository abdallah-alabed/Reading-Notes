## Canvas
 provides a means for drawing graphics via JavaScript and the HTML <canvas> element.
  
 - canvas element has only two attributes, width and height these are both optional.
 - different from the img tag wew need a closing tag for the canvas.
  - we use it for 2D rendering.
  
  ### Drawing shapes with canvas
  > Normally 1 unit in the grid corresponds to 1 pixel on the canvas.
  
- fillRect(x, y, width, height)
> Draws a filled rectangle.
- strokeRect(x, y, width, height)
> Draws a rectangular outline.
- clearRect(x, y, width, height)
> Clears the specified rectangular area, making it fully transparent.
- we can draaw a path using the followinig commands:
1. beginPath()
> Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
2. Path methods
> Methods to set different paths for objects.
3. closePath()
> Adds a straight line to the path, going to the start of the current sub-path.
4. stroke()
> Draws the shape by stroking its outline.
5. fill()
> Draws a solid shape by filling the path's content area.
6. moveTo(x, y)
> Moves the pen to the coordinates specified by x and y.

  ### styling and coloring
- fillStyle = color
> Sets the style used when filling shapes.
- strokeStyle = color
> Sets the style for shapes' outlines.
- globalAlpha = transparencyValue
> Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.
- lineWidth = value
> Sets the width of lines drawn in the future.
- lineCap = type
> Sets the appearance of the ends of lines.
- lineJoin = type
> Sets the appearance of the "corners" where lines meet.
- miterLimit = value
> Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
- getLineDash()
> Returns the current line dash pattern array containing an even number of non-negative numbers.
- setLineDash(segments)
> Sets the current line dash pattern.
- lineDashOffset = value
> Specifies where to start a dash array on a line.
- createLinearGradient(x1, y1, x2, y2)
> Creates a linear gradient object with a starting point of (x1, y1) and an end point of (x2, y2).
- createRadialGradient(x1, y1, r1, x2, y2, r2)
> Creates a radial gradient. The parameters represent two circles, one with its center at (x1, y1) and a radius of r1, and the other with its center at (x2, y2) with a radius of r2.
- createConicGradient(angle, x, y)
> Creates a conic gradient object with a starting angle of angle in radians, at the position (x, y).
  
  ### drawing texts
- fillText(text, x, y [, maxWidth])
> Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
> Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
- font = value
> The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
- textAlign = value
> Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
- textBaseline = value
> Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
- direction = value
>Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.
- measureText()
> Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
