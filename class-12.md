# Read [Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) on the Chart.js API.
> * Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
> * Steps to import: 
>   * download [Chart.js](https://github.com/chartjs/Chart.js)
> * In this article, it goes over how to add: 
>   * A linechart
>   * A piechart
>   * A barchart

# [Chart.js docs](https://www.chartjs.org/docs/latest/): You’ll be needing these!

> * download from [Github](https://github.com/chartjs/Chart.js/releases/tag/v2.9.3)
> * Create a Chart
>   * All that's required is the script included in your page along with a single ```<canvas>``` node to render the chart.
>   * In article, shows how to create a barchart and references this article for usage documentation for other ways to make a chart [usage documentation](https://www.chartjs.org/docs/latest/getting-started/usage.html)
>   * I thought that the most useful part for what stage we are in in APIs was [here](https://www.chartjs.org/docs/latest/developers/api.html)
>   * .destroy() - destroy any chart instances created 
>   * .update(config) - triggers update of chart
>   * .reset() - reset the chart to its state before the initial animation 
>   * .render(config) - triggers redraw of all chart elements
>   * .stop() - stop any current animation loop 
>   * .resize() - manually resize the canvas element
>   * .clear() - will clear chart canvas
>   * .generateLegend()
>   * 


# Canvas API Articles: 
1. [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
> * ```<canvas> element ``` - does not have src or alt attributes and only has two attributes: width and height
> * if width and height are not specified, it will default to 300px wide x 150px high
> * The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. 
> * The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.
> * A skeleton template is also available within this article, though they splaced an embed script inside HTML

2. [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
> * Grid - Normally 1 unit in the grid corresponds to 1 pixel on the canvas.
> * Drawing rectangles - ```fillRect(x, y, width, height) - Draws a filled rectangle. strokeRect(x, y, width, height) - Draws a rectangular outline. clearRect(x, y, width, height) - Clears the specified rectangular area, making it fully transparent.```
> * Drawing paths - a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color and should be closed
>   * To make shapes: First, you create the path.
Then you use drawing commands to draw into the path.
Once the path has been created, you can stroke or fill the path to render it.
>   * Functions used to perform these steps: 
>   * <img src='../assets /Screen Shot 2020-04-13 at 7.22.03 PM.png'/>
> * Other shape that this article covers: triangle, moving the pen, lineTo, Arcs, Bezier and quadratic curves, Cubic Bezier curves, Rectangles and combinations
> * Path2D objects - The Path2D() constructor returns a newly instantiated Path2D object, optionally with another path as an argument (creates a copy), or optionally with a string consisting of SVG path data.
> * SVG paths - Another powerful feature of the new canvas Path2D API is using SVG path data to initialize paths on your canvas. 

3. [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
> * Colors - ```fillStyle = color``` and ```strokeStyle = color```
>   * color is a string representing a CSS <color>, a gradient object, or a pattern object.
> * Transparency - ```globalAlpha = transparencyValue``` - Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.
> * rgba() - gives you a little more control and flexibility because we can set the fill and stroke style individually.
> * Line styles
>   * lineWidth = value - Sets the width of lines drawn in the future.
>   * lineCap = type - Sets the appearance of the ends of lines.
>   * lineJoin = type - Sets the appearance of the "corners" where lines meet.
>   * miterLimit = value - Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
>   * getLineDash() - Returns the current line dash pattern array containing an even number of non-negative numbers.
>   * setLineDash(segments) - Sets the current line dash pattern.
>   * lineDashOffset = value - Specifies where to start a dash array on a line
> * Gradients - We create a CanvasGradient object by using one of the following methods. We can then assign this object to the fillStyle or strokeStyle properties.
>   * createLinearGradient(x1, y1, x2, y2) - Creates a linear gradient object with a starting point of (x1, y1) and an end point of (x2, y2).
>   * createRadialGradient(x1, y1, r1, x2, y2, r2) - Creates a radial gradient. The parameters represent two circles, one with its center at (x1, y1) and a radius of r1, and the other with its center at (x2, y2) with a radius of r2.
>   * gradient.addColorStop(position, color) - Creates a new color stop on the gradient object. The position is a number between 0.0 and 1.0 and defines the relative position of the color in the gradient, and the color argument must be a string representing a CSS <color>, indicating the color the gradient should reach at that offset into the transition.
> * Patterns
>   * createPattern(image, type) - Creates and returns a new canvas pattern object. image is a CanvasImageSource (that is, an HTMLImageElement, another canvas, a <video> element, or the like. type is a string indicating how to use the image.
>       * repeat - Tiles the image in both vertical and horizontal directions.
>       * repeat-x - Tiles the image horizontally but not vertically.
>       * repeat-y - Tiles the image vertically but not horizontally.
>       * no-repeat - Doesn't tile the image. It's used only once.
> * Shadows
>   * shadowOffsetX = float
>   * shadowOffsetY = float
>   * shadowBlur = float
>   * shadowColor = color
> *  Canvas fill rules
>   * "nonzero": The non-zero winding rule, which is the default rule.
>   * "evenodd": The even-odd winding rule.

4. [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text) 
> * Drawing text
> * fillText(text, x, y [, maxWidth]) - Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
> * strokeText(text, x, y [, maxWidth]) - Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw. 
> * Styling text
>   * font = value - The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
>   * textAlign = value - Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
 >   * textBaseline = value - Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
 >   * direction = value - Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.
> * Advanced text measurements
>   * measureText() - Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.