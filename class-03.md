# class03
______________

# HTML & CSS Book 

## Chapter 3: “Lists” (pp.62-73)
### Vocabulary 
> **ordered lists** - lists where each item in the list is numbered
>   * < ol >
>   *   < li> < /li>
>   * < /ol>

> **unordered lists** - lists that begin with a bullet point
>   * < ul>
>   * < li>< li>
>   * < /ul>

> **definition lists** - made up of a set of terms along with definitions for each of those terms
>   * < dl>
>   * < dt>< /dt> - contains term being defined
>   * < dd>< /dd> - contains the definition
>   * < /dl>
> **nested lists** - a second list within another list that sits between the < li> element

### Summary 
> * 3 types of HTML lists: ordered, unordered, definition
> * Ordered lists use numbers
> * Unordered lists use bullets 
> * Definition lists are used to define terminology 
> * Lists can be nested inside one another


## Chapter 13: “Boxes” (pp.300-329)
### Outline
> * Box Dimensions (width,height)
>   * can use pixels, percentages, or ems
>   * when using percentages, size of the box is relative to size of browser window
>   * when using ems, size of the box is based on the size of text within it

> * Limiting Width (min-width, max-width)
>   * min-width - specifies the smallest size a box can be displayed, if page designs expand/shrink with user's screen
>   * max-width - specifies the maximum width a box can streth compared to browser window
> * Limiting Height (min-height, max-height)
>   * acts as max-width or min-width, but for height
>   * downfall is that if the text does not fit, it will overlap

> * Overflowing Content
>   * overflow - tells the browser what to do if the contents contained within a box is larger than the box itself.
>   * It's two values: 
>       * hidden - hides any extra content that does not fit in the box
>       * scroll - adds a scrollbar to the box so that users can scroll to see the missing content

> * Border, Margin and Padding (three available properties of every box)
>   * Border - all boxes have a border, even if not visible. The border separates the edge of one box from another
>   * Margin - margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes
>   * Padding - the space between the border of a box and any content contained within it.  Adding padding can increase the readability of its contents 
> * White Space and Vertical Margin 
>   * Padding and margin properties are very helpful in adding space between various items on a page
>   * **white space** - space between items on a page

> * Border Width (border-width) - used to control the width of a border in pexels or values: thin, medium, thick
>   * you can also specify specific parts of the border (border-top-width, border-right-width, border-bottom-width, border-left-width)
>   * you can also specify different widths for the four borders values in one property (border-width: 2px 1px 1px 2px;)
> * Border Style (border-style) - style of the border
>   * solid, dotted, dashed, double, groove, ridge, inset, outset, hidden/none
>   * you can individually change the styles of different borders using: border-top-style, border-left-style, border-right-style, 
border-bottom-style
> Border Color (border-color) - can specify colors of the border using RGB values, this can also be controlled by specific sides of the border
> * Shorthand(border) - allows to specify the width, style and color of a border in one property 
> * Padding (padding) - allows you to specify how much space should appear beween the content of an element
> * Margin (margin) - controls the gap between boxes
> * Centering Content - can set left and right margin to auto
>   * text-align property is inherited by the child elements and need to specify the text-align property on the centered box if you do not want text inside to be centered 
> * Change Inline/Block (display) - display property allows you to turn an inline element or vice versa and can be used to hide an element from the page. The values of this property:
>   * inline - causes the block-level element to act like an inline element
>   * block - this causes an inline element to act like a block-level element
>   * inline-block - causes a block-level element to flow lke an inline element, while retaining other features of a block-level comment
>   * none - hides the element from the page
>       * inline boxes are **not** supposed to create block-level lements 
> * Hiding Boxes (visiblity) - allows you to hide boxes from users but it leaves a space where the element would have been. This property can take two values: 
>   * hidden - hides the element
>   * visible - shows the element


### Summary
> * CSS treats each HTML element as if it has its own box
> * You can use CSS to control the dimensions of a box
> * You can also control the borders, margins and padding for each box with CSS
> * It is possible to hid elements using the display and visibility properties
> * Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes
> * Legibility can be improved by controlling the width of boxes containing text and the leading
> * CSS3 has introduced the ability to create image borders and rounded borders

__________________

# Javascript Book

## Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

### Summary
> * If...Else Statements - checks the condition. If it resolves to true, the first code block is executed. If false, the second code block is run instead
> * Switch Statements- starts with a varialbe called the switch value. Each case indicates a possible value for this varialbe and the code that should run if the variable matches that value
> * Type coercion - javascript converting data types behind the scens to complete an operation.
> * Javascript uses weak typing bc the data type for a value can change
> * Strong typing - Some other languages require that yo uspecify what data type each variable will be
> * Falsy - treated as if they are false. 
> * Truthy - treated as if they are true
> * Checking Equality & Existence - bc the presense of an object or array can be considered truthy, it is often used to check for the existence of an element within a page
> * unary operator - returns a result with just one operand 
> * Loops - check a condition
>   * if returned true, a code block will run
>   * for - to run a specific number of times. The condition is usually a counter which is used to tell how many times the loop should run
>   * while - if you don't know how many times the code should run, you can use this. Can be a condition other than a counter, and code will loop for as long as condition is true
>   * Do... while - very similar to the while loop, but has one key difference: it will always run the statement insdie the curly braces at least once, even if the condition is false


### Summary 
> * Switch statements allow you to compare a value against possbile outcomes (and also provides a default option if none match)
> * Data types can be coerced from one type to another
> * All values evaluate to either truthy or falsy 
> * There are three types of loop: for, while, and do...while. Each repeats a set of statements