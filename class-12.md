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
> * 
> * 
> * 
> * 
> * 
> * 
> * 

4. [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text) 
> * 
> * 
> * 
> * 
> * 
> * 
