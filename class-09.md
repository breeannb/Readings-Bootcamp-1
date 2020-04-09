
# HTML 
## Chapter 7: “Forms” (p.144-175)
> * Form - traditionally referred to as a printed document that contains spaces for you to fill in information 
> * Best known form on the web is the search box that is on Google
> * Allow you to search and perform functions
> * Different types of form controls: 
>   * Adding Text: text input, password input, text area
>   * Making choices: radio buttons, checkboxes, drop-down boxes
>   * Submitting Forms: submit buttons, image buttons, uploading files
> * How do they work? 
>   * A user fills in a form and then presses a button to submit hte information to the server > name of each form control sent to server with value user enters/selects > server processes info using programing languages and may store this in a database > server creates a new page to send back to the browser based on info received 
>  * A form may have several form controls, each gathering different info. The server needs to know which piece of inputted data corresponds with which form element. 
>  * Form structure - ```<form action="URL for page on the server" method="get or post methods" >``` 
>       * get method: values form the form are added to the end of the URL specified in the action attribute.  Ideal for: short forms(search boxes) and when retrieving data from a web server (not sending info that is added or deleted from database)
>       * post method: allows uploads of files, long, contains sensitive data, adds info or deletes from database
>       * id = value is used to identify form distinctly from otherelements on the page
>       * size - not used on new forms. used in older forms to indicate width of text input
>  * Text Input - used to create several different form controls
>       * type="text" - creates single line input
>       * name - identifies form control and is sent along with info they enter to server 
>       * maxlength - limit the number of characters a user may enter into the text field
> * Password input (type="password") - creates a text box that acts just like a single-line text input, except the characters are blocked out
>       * name - indicates the name of the password input, and is sent to the server with password user enters
>       * size, maxlength - carry the size and maxlength attributes like the single-line text input
> * Text Area (< textarea >) - used to create a multi-line text input.  
> * Radio button - allow users to pick just one of a number of options
>       * name - sent to server with value of option the user selects
>       * value - indicates the value that is sent to the server for the selected option 
>       * checked - can be used to indicate which value should be selected when the page loads 
> * Checkbox - ```<input type="checkbox">``` checkboxes allow users to select and deselect one or more options in answers to a question
>       * name - sent to server with value of options user selects
>       * value - indicates value sent to the server if this checkbox is checked
>       * checked - indicates that this box should be checked when the page loads
> * Other Forms
>       * Drop Down list 
>       * Multiple Select Box 
>       * File Input Box 
>       * Submit Button 
>       * Image Button 
>       * Button and Hidden Control 
> * Labeling Form Controls - makes accessible to vision impaired users. It can wrap around both the text and description or be kept seperate from the form control

## Chapter 14: “Lists, Tables & Forms” (pp.330-357)
> * Lists: 
>      * bullet point styles - list-style-type
>      * images: list-style-image
>      * Positioning the Marker 
>           * can have two values: outside or inside
>      * List Shorthand
>           * list-style - allows you to express marker's style, image and position

> * Table Properties 
>     * width
>     * padding
>     * text-transform
>     * letter-spacing, font-size
>     * border-top, border-bottom
>     * text-align
>     * background-color
>     * :hover


# Javascript
## Chapter 6: “Events” (pp.243-292)

> * Events can fire or be raised. 
> * Events trigger scripts or functions
> * How events trigger Javascript code: 
>     * Select the element nodes you want the script to respond to 
>     * Indicate which event on the selected nodes will trigger the response 
>     * State hte code you want to run when the event occurs 
> * How to bind an event in an element: Event handlers, and event listeners 
> * Traditional DOM event handlers: element.oneevent = functionName; 
> * Event Listeners - elemenbt.addEventListener('event', functionName, [, Boolean]); 

> * # Summary 
> * Events are browsers way of indicating when something has happened (such as when a page has finsihed loading or a button has been clicked)
> * Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon 
> * When an event occurs on an element, it can trigger a Javascript function. When this function then changes the web page in some way, it feels interactive bc it has responded to the user 
> * You can use event delegation to monitor for events that happen on all of the children of an element 
> * The most commonly used events are W3C DOM events, although there are others in the HTML5 specification as well as browser-specific events