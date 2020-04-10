# class-07

## Article: Domain Modeling
> ### Summary 
> * Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

> * When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
> * Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
> * Create instances using the new keyword followed by a call to a constructor function.
> * Store the newly created object in a variable so you can access its properties and methods from outside.
> * Use the this variable within methods so you can access the object's properties and methods from inside.

## From the Duckett HTML book: Chapter 6: “Tables” (pp.126-145)
> * The < table> element is used to add tables toa web page 
> * A table is drawn out row by row. Each row is created wit ha < tr> element
> * Inside each row there are a number of cells represented by the < td> element or the < th> if it is a header
> * You can make cells of a table span more than one row or column using the rowspan and colspan attributes
> * For long tables, you can split the talbe into < thead>, < tbody>, < tfoot>



## From the Duckett JS Book: Chapter 3: “Functions, Methods, and Objects” (pp.106-144)
> * functions allow you to group a set of related statements together that represent a single task
> * /functions can take parameters information required to do their job and may return a value 
> * An object is a series of variable and functions that represent dsomething from the world around you
> * In an object, variables are known as properties of the object; functions are known as methods of the object
> * web browsers implement objects that represent both the browser window and the document loaded into the browser window 
> * Javascript also has several built in objects such as string, number, math and date. Their properties and methods offer functionality that help you write scripts
> * Arrays and objects can be used to create complex sets and both can contain the other 