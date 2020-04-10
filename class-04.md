# class-04
__________

# HTML & CSS 
## Chapter 4: Ch.4 “Links” (pp.74-93)
> * Writing Links 
>   * Links are created using the < a> element. Users can click on anything between the tag and closing tag. You will specify which page you want to link to using the href attribute 
> * Linking to Other Sites (< a>) - it needs to link to the **absolute** URL, which includes the full web address
> * Linking to other pages on the same site ( < a>) - you do not need to specify the domain name in url, and can use the shorthand called **relative** URL
> * Directory Structure
>   * On larger websites, its a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes refered to as directions
>       * structure - top level folder is refered to as **root** folder.  This contains all of the other files and folders for the website
>       * relationships - the relationship between files and folders on a website is described as a family tree  
>       * homepages - main homepage of a site written in HTML is called index.html. WEb servers usually set up to return the index.html file if no file name is specified
> * Relative URLs - Relative URLs can be used when linking to pages within your own website. They can provide a shorthand way of telling the browser where to find your files 
> * Email Links - (mailto:) this creates a link that starts up the user's email program and addresses an email to a specified email address, you use the < a> element. 
> * Opening Links in a New Window (target) - if you want a link to open a new window, you can add the target as '_blank'

> * # Summary 
> * Links are created using the < a> element
> * The < a> element uses the href attribute to indidcate the page you are linking to 
> * If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs
> * You can create links to open email programs with an email address in the "to" field
> * You can use the id attribute to target elements within a page that can be linked to


## Chapter 15: “Layout” (pp.358-404)
> * # Vocabulary 
> * Block Level Elements 
>   * < h1> < p> < ul> < li>
> * Inline Elements 
>   * < img> < b> < i>
> * It is common to group a number of elements together inside a < div> or other block-level element. 
> * Positioning Schemes 
>   * Normal Flow - every block level element appears on a new line, causing each item to appear lower down the page than the previous one. 
>   * Relative Positioning - moves an element from the position it would be in norml flow, shifting it to the top, right bottom or left of where it would have been placed
>   * Absolute positioning - positions the element in relation to its containing element
> * Fixed Positioning - form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element
> * Floating Elements - floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow  
> * z-index - property allows you to control which box appears on top  
> * Normal Flow (position:static) - for the elements to be in normal flow 
> * Relative Positioning (position:relative) - moves an element in relation to where it would have been in normal flow 
> * (position:absolute)
> * (position:fixed) - type of absolute positioning that requires the position property to have a value of fixed and positions the element in relation to the browser window
> * z-index - to control which element sits on top if elements overlap 
> * float - allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible
>   * can help place boxes next to each other, but the heigh of the boxes can affect where the following elements sit  
> * clear - allows you to say that no element should touch the left or right hand sides of a box with the following values: left, right, both, none. 
> * parents of floated elements: problem - if a containing element only contains floated elements, some browsers treat it as if it is  zero pixels tall
>   * solution: overflow property is give na value auto and width: 100%
> * Multi-column layouts - width, float and margin 
> * **Designers try to create pages around 960-1000 pixels**

> * # Summary 
> * < div> elements are often used as containing elements to group together sections of a page. 
> * Browsers display pages in normal flow unless you specifiy relative, absolute, or fixed position
> * The float property moves content to the left or right of the page and can be sued to create multi-colum layouts (they require a defined width)
> * Pages can be fixed width or liquid (stretchy) layouts
> * Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling)
> * Grids help create professsional and flexible designs
> * CSS Frameworks provide rules for common tasks 
> * You can include multiple CSS files in one page 
_________

# JAVASCRIPT 
## Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
> * Function - let you grop a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function. 
> * Function declaration - give it a name and then write the statements needed to achieve its task inside the curly braces


## Article: “6 Reasons for Pair Programming”
> * "two heads are better than one" 
> * How Does it Work? 
>   * the Driver and the Navigator: Driver is the programmer that is typing and the only one whose hands are on the keyboard. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer
> * Why Pair Programming? 
>   * These 4 fundamental skills help anyone learn a new language: Listening, Speaking, Reading, Writing
>   * This will create: Greater efficiency, Engaged collaboration, Learning from Fellow Students, Social Skills, Job interview readiness, Work environment readiness