# [Learn Layout CSS](https://www.learnlayout.com)

> * Display - most important property. Default is usually block or inline
> * Block element - A block element is often called a block-level element.
>   * div is the standard block-level element. A block-level element starts on a new line and stretches out to the left and right as far as it can. 
>   * Other common block-level elements are p and form, and new in HTML5 are header, footer, section, and more.
> * Inline element - An inline element is always just called an inline element.
>   * span is the standard inline element. An inline element can wrap some text inside a paragraph <span> like this </span> without disrupting the flow of that paragraph. The a element is the most common inline element, since you use them for links.
> * Other common value displays: none, usually used for script
>   * visibility - having it to hidden will hide the element but still take up the space
>   * list-item and table 
>   * [A HANDY LIST](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

> * margin: auto; 
```
#main {
  width: 600px;
  margin: 0 auto; 
} 
```
>   * Setting the width of a block-level element will prevent it from stretching out to the edges of its container to the left and right. Then, you can set the left and right margins to auto to horizontally center that element within its container. 
> * max-width - Using max-width instead of width in this situation will improve the browser's handling of small windows.
```
#main {
  max-width: 600px;
  margin: 0 auto; 
}
```
> * # The Box Model 
```
.simple {
  width: 500px;
  margin: 20px auto;
}

.fancy {
  width: 500px;
  margin: 20px auto;
  padding: 50px;
  border-width: 10px;
}
```

>   * When you set the width of an element, the element can actually appear bigger than what you set: the element's border and padding will stretch out the element beyond the specified width.
> * box-sizing - The original box model behavior was eventually considered unintuitive, so a new CSS property called box-sizing was created. When you set box-sizing: border-box; on an element, the padding and border of that element no longer increase its width. Here is the same example as the previous page, but with box-sizing: border-box; on both elements:
```
.simple {
  width: 500px;
  margin: 20px auto;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}

.fancy {
  width: 500px;
  margin: 20px auto;
  padding: 50px;
  border: solid blue 10px;
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}
```
> * position - 
>   * static: static is the default value. An element with position: static; is not positioned in any special way. A static element is said to be not positioned and an element with its position set to anything else is said to be positioned.
```
.static {
  position: static;
}
```
> * fixed - A fixed element is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. As with relative, the top, right, bottom, and left properties are used.
```
.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 200px;
  background-color: white;
}
```
> * absolute - absolute is the trickiest position value. absolute behaves like fixed except relative to the nearest positioned ancestor instead of relative to the viewport
``` 
.relative {
  position: relative;
  width: 600px;
  height: 400px;
}
.absolute {
  position: absolute;
  top: 120px;
  right: 0;
  width: 300px;
  height: 200px;
}
```
> * float - Another CSS property used for layout is float. Float is intended for wrapping text around images, like this:
```
img {
  float: right;
  margin: 0 0 1em 1em;
}
```
> * clear - The clear property is important for controlling the behavior of floats.
```
<div class="box">...</div>
<section>...</section>
.box {
  float: left;
  width: 200px;
  height: 100px;
  margin: 1em;
}
```
> * inline block - You can create a grid of boxes that fills the browser width and wraps nicely. This has been possible for a long time using float, but now with inline-block it's even easier. inline-block elements are like inline elements but they can have a width and height. Let's look at examples of both approaches.
>   * the hard way:  
```
.box {
  float: left;
  width: 200px;
  height: 100px;
  margin: 1em;
}
.after-box {
  clear: left;
}
```
>   * the easy way: You can achieve the same effect using the inline-block value of the display property.
```
.box2 {
  display: inline-block;
  width: 200px;
  height: 100px;
  margin: 1em;
}
```
> * inline-block layout
>   * inline-block elements are affected by the vertical-align property, which you probably want set to top.
>   * You need to set the width of each column
>   * There will be a gap between the columns if there is any whitespace between them in the HTML
```
nav {
  display: inline-block;
  vertical-align: top;
  width: 25%;
}
.column {
  display: inline-block;
  vertical-align: top;
  width: 75%;
}
```
> * column - There is a new set of CSS properties that let you easily make multi-column text. 
```
.three-column {
  padding: 1em;
  -moz-column-count: 3;
  -moz-column-gap: 1em;
  -webkit-column-count: 3;
  -webkit-column-gap: 1em;
  column-count: 3;
  column-gap: 1em;
}
```
> * flexbox - 
    > * Simple Layout: 
```
.container {
  display: -webkit-flex;
  display: flex;
}
nav {
  width: 200px;
}
.flex-column {
  -webkit-flex: 1;
          flex: 1;
}
```
>   * Fancy layout: 
```
.container {
  display: -webkit-flex;
  display: flex;
}
.initial {
  -webkit-flex: initial;
          flex: initial;
  width: 200px;
  min-width: 100px;
}
.none {
  -webkit-flex: none;
          flex: none;
  width: 200px;
}
.flex1 {
  -webkit-flex: 1;
          flex: 1;
}
.flex2 {
  -webkit-flex: 2;
          flex: 2;
}
```
> * Centering using Flexbox
```
.vertical-container {
  height: 300px;
  display: -webkit-flex;
  display:         flex;
  -webkit-align-items: center;
          align-items: center;
  -webkit-justify-content: center;
          justify-content: center;
}
```