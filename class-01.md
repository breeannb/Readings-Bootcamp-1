# class-01

# Read 01

_________

# HTML & CSS
# 1. Introduction (pp.2-11)
>  **Is It Hard To Learn?** 
> * Understanding HTML and CSS can help anyone who works with the web. Examples are designers, website editors, marketers and managers. 

> **The Structure of this Book:** 
> 1. HTML 
> * This will mostly be the content of your words and then add elements and tags to organize it, such as text, lists, links images and tables. 
> 2. CSS
> * **Presentation** - Control color of text, fonts you want to use, size of fonts, background colors.
> * **Layouts** - How to control where the differen elements are positioned in the screen. 
> 3. Practical 
> * Helfpul information that will assist in building websites, such as new tag introduced.

> **How People Access the Web:** 
> * Browsers, Webservers, Devices, Screen Readers

> **How Websites are Created:**
> * All websites use HTML and CSS, but content management systems, bloggin software and more e-commerce platforms often add a few more technologies into the mix.  
> * What you see? It is most likely your browser is receiving HTML andCSS from the web server that hosts the site, which interprets the code to create the page you are viewing. Some sites also use Javascript and Flash

> **How the Web Works**
> * When you visit a website, the web server hosting that site cxould be anywhere in the world.  To find the location, yoru browser will connect to the Domain Name System (DNS) server

# 2. HTML Chapter 1: “Structure” (pp.12-39)

> * HTML Describes the Structure of the Pages and are text documents  
> * **Elements** - usually made up of two **tags**: an opening and a closing tag. 
> * HTML uses the elements to describe the structure of pages
> * **Attributes tell us more about Elements** - they provide additional information about the contents of an eleent. They appear on the opening tag of the element and are made of two parts: **name** and **value**

# 3. HTML Chapter 8: “Extra Markup” (p.176-199)
> * Doctypes tell browsers which version of HTML you are using
> * You can add comments to your code between the <!-- and ---> markers 
>   * It is a good idea to add comments to your code because no matter how familiar you are with the page at the time of wiring it, when you come back to it later, it will make it much easier to understand
> * The id and class attributes allow you to identify particular elements and to add script work with that particular element in Javascript
>   * The id attribut is known as a **global attribute** because it can be used in any element
> * The < div > and < span > elements allow you to group block-level and inline elements together
>   * **Block-level** elements will always appear to start on a new line in the browser window, such as < h1 >, < p >, < ul > and < li >
>   * **Inline elements** will always appear to continue on the same line as their neighboring elements such as < a >, < b >, < em >, < img >
>   * < div > allows you to group a set of elements together in one block-level boc
>   * < span > acts like an inline equivalent of the < div > element. It is used to either: 
>       * 1. contain sections of text where ther eis no other suitable element to differentiate it from the surrounding text 
>       * 2. Contain a number of linline elements
> * < iframes > cut windows into your web pages through which other pages can be displayed
>   * Attributes that are needed to know to use it: 
>       * src - specifies the URL of the page to show in the frame
>       * height - specifies the height of the iframe in pixels 
>       * width - specifies the width of the iframe in pixels 
>       * scrolling 
>       * frameborder 
>       * seamless 
> * The < meta > tag allows you to supply all kinds of informations about your web page 
>   * Lives in the < head> element
>   * Tells search engines about your page and should be a maximum of 155 characters
>   * Contains a list of keywords that a user might search on to find the page
>   * Robots - indicates wheather search engines should add this to their search results or not
>   * Defines the author 
>   * pragma - prevents the browser from caching the page (storing it locally to save downloading it on subsequent visits)
>   * expries - because browsers often cache the content of a page, the expries option can be used to indicate when the page should expire
> * Escape characters are used to include special characters in your pages such as <, >, and the copyright symbol. 
>   * [HTML Escape Character Cheatsheet](https://cheatography.com/davechild/cheat-sheets/html-character-entities/)

# 4. HTML Chapter 17: “HTML5 Layout” (pp.## 428-451)
> * The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure
> * The new elements provide clearer code (compared with using multiple < div> elements)
>   * Headers and footers - can be used for the main header or footer that appears at the top or bottom of the page. You can also make a header or footer for an individual < article > or < section>. 
>       * Each individual header and footer for an individual article or section within a page
>       * Navigation < nav> - used to contain the major navigational blocks on the site such as primary site navigation, such as using for the bottom of links that appear at the bottom of pages, such as privacy policy, terms of conditions
>       * Article < article> - acts as a container for any section of a page that could stand alone and potentially be syndicated
>       * Can be nested inside eachother as wel, such as a blog post might live inside one article element and each comment on the article could have a child article element
>       * Aside < aside> - has two purposes, depending on if it is inside the article element or not
>           * When inside, it should contain info that is related to the article, but not essential to its overall meaning. 
>           * When outside, it act as a container for content thatis related to the entire page, such as lnks to other sections of the site
>       * Sections < section > - groups related content together, and typically each section would have its own heading
>           * May contain several distinct article elements that have a common theme or purpose
>           * Should not be used as a wraper for the entire page, unless the page only contains one distince piece of content. Div would be more appropriate  for containing an element for the entire page
>       * Heading Groups < hrgroup> - to group together more than one < h1> through < h6> elements
>       * Figures element - used to contain any content that is referenced from the main flow of an article such as images, videos, graphs, diagrams, code samples, etc. 
> * Older browsers that do not understand HTML5 elements are block-level elements
> * JTo make HTML5 elements work in Internet Explorer 8, extra Javascript is needed, which is available free from Google


# 5. HTML Chapter 18: “Process & Design” (pp.452-475)
> * It's important to understand your target audience and why they would come to yoru site, what information they want to find and when they will return
>       * Questions to ask can differentiate between indivuals and companies. Discover the motivations of the visitors coming to your site and exame the goals of the visitor to establish triggers to make them come to your site now
> * Site maps allow you to plan the structure of a site
>       * You can also use a technique called card sorting
> * Wireframes allow you to organize the information that will need to go on each page
> * Design is about communication. Visual heirarchy helps visitors understand what you are trying to tell them
>   * Content - masthead or logo, links to navigation site, links to related content, login or membership options
>   * Designer needs to organize and prioritize the information to communicate their message
> * Prioritizing - Making parts look distinc from surrounding content, designers draw attention to or away from those items
>   * Designers create a visual hierarchy to help users focus on the key messages that will draw people's attention, and then guide them to subsequent messages
> * Organizing - grouping together related content into blocks or chuncks makes the page look simpler and easier to understand 
> * Visual Hierarchy - You can differentiate between pieces of information using size, color, and style
> * Can use grouping and similarity to help simplify the information you present. 

_________

# Javascript and JQuery

# 1. Introduction (pp. 2-10)
> **How does Javascript make web pages more interactive?** 
> * Access Content - can use JavaScript to select any element, attribute, or text from HTML pag
> * Modify Content - can use to add elements, attributes and text to the page or remove them
> * Program Rules - Can specify a set of steps for the browser to follow which allows to access or change content of the page
> * React to Events - specifiy that a script should run when a specific event has occurred 
> * Examples: Slideshows, Forms, Reload part of a page, Filtering Data

# 2.JS Chapter 1: “The ABC of Programming” (pp.11-52)
> **What is a script and how do I create one?** 
> * A script is a series of instructions that the computer can follow in order to achieve a goal
>   * to write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it
> * Each time the script runs, it might only use a subset of all the instructions
> * Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically 
> * To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task

> **How do Computers fit in with the world around them?** 
> * Computers create models of the world using data
> * The models use objects to represetn physical things. Objects have properties that tell us about the object, methods that perform tasks using the properties of that object; events which are triggerd when a user interacts with the computer
>   * Each property has a name and value, and each of these pairs tells you something about each individual instance of the object
>   * Methods - represent how people or things interact with an object in the real world
> * Programmers can write code to say "when this event occurs, run that code" 
> * Web browsers use HTML markup to creat a model of the web page. Each element creates its own node (which is a kind of object)
> * To make web pages interactive, you write code that uses the browser's model of the web page 

> **How do I write Script for a Web Page?** 
> * It is best to keep Javascript code in its own file.  They have .js extensions. 
> * HTML < script> element is used in HTML pages to tell the browser to load the Javascript file (rather than like the < link> element can be used to load CSS
> * If you view the source code of a page in the browser, the Javascript will not have change the HTML, because the script works with the model of the web page that the browser created 