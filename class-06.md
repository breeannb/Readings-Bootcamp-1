# class-06

## Article: Understanding the problem domain is the hardest part of programming
> * What are the most difficult parts of writing code? 
>       * Learning a new technology
>       * Naming things
>       * Testing your code
>       * Debugging
>       * Fixing bugs
>       * Making software maintainable
>       * **Problem Domain** 
> * Why build the same thing over and over again? <i>Familiarity</i>
> * What I found with this simple application was that because it was so easy to understand, the focus was taken off of the problem domain and put instead on the technology.
> * By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.
> * **Why are problem domains hard?** 
>       * Figure out the major components 
>       * Sort hte peices by color or componenet 
>       * Put together all the border pieces 
>       * Put together each componenet of the picture form the piles you created 
> * Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.
> * I was easily able to learn that problem domain and because of it, I was able to write the code very easily as well.
> * **What can you do?:** 
>   * 1. Make the problem domain easier
>   * 2. Get better at understanding the problem domain
> * You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

_______________

## Javascript From the Duckett JS book

# Chapter 3: “Object Literals” (pp.100-105)
> * What is an object? 
>   * Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, the variables and functions take a new names. 
>   * In an object, varaibles become known as properties 
>   * if a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of the hotel or number of rooms it has 
>   * In an object, functions become known as methods.  Methods represent taks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms 
> * The object represents a hotel. It has five properties and one method. The object is in curly braces. It is stored in the variable called hotel 
> * key - properites and methods have a name and value. In an object, this is called a key. 
> * Creating an object: Literal Notation: Literal notation is the easisest and most popular way to create objects. There are several ways to create an object. 
> * Accessing an object and dot notation 
>   * access the properties or methods of an object using dot notation. You can also access properties using square brackets 



# Chapter 5: “Document Object Model” (pp.183-242)

# Summary 
> * The browser represents the page using the DOM tree
> * DOM trees have four types of nodes: document nodes, attribute nodes, and text nodes
> * You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax
> * Whenever a DOM query can return more than one node, it will always return a NOdelist
> * From an element node, you can use access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques. 
> * An element node can contain multiple text nodes and child elements that are sibling of eachother
> * In older browsers, implementation of the DOM is inconsistent and is a popular reason for using jQuery
> * Browsers offer tools for viewing the DOM tree 