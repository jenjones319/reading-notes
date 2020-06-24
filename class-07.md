# Reading Notes
## June 23, 2020

__Domain Modeling Article__
* Domain modeling is creating a model in code to address a problem.
* Constructor functions are defined using upper camel case.
* From there, the c function is assigned a function with parameters. 
* methods can be added to a constructor function's prototype.
* Tips for buidling domain models, from the article: 
* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.

__HTML Chapter 6: Tables__
* tables provide information in grid format. 
* table, thead is table header, tr is table row, td is table data. thead is header, tbody is body, tfooter is footer. its a whole container for a table.
* colspan and rowspan attributes are used to span rows and columns. 
* border and bgcolor attributes can be used in the table tag to style.

__Chapter 3: Functions, Methods, and Objects__ 
* This covers up to p. 144
* Constructor notation is a shorthand way to create objects
* Browser object models are on p 124 - window objects
* Document object represents the web page loaded into the browser window. p.126
* String objects are global and are listed on 128-9
* Simple data types are string, number, boolean, undefined, and null
* complex data are objects. Arrays are objects.
* global number objects are on 132.
* Math objects are on 134 and include Math.round, Math.sqrt, Math.ceil, Math.floor, Math.random. (used these in class06 lab)
* Date objects are another global object, can be found on 137. 