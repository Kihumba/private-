# Javascript - KBBs

## Knowledge
1. What is Javascript? Understand Javascript as a language for the web.
2. How is Javascript written? The Basic syntax governing Javascript (Targeting ES5)
3. Javascript syntax and concepts for
	- Variables and Constants
	- Control Flow Methods
		- Conditionals
			- If / else
			- Switch / Case
		- Looping
			- for
			- for-in
			- while
			- Do-while
	- Functions and Callbacks
		- Declaring functions
		- Closures as self calling functions
	- Data types
		- Primitive
			- Numbers
			- Strings
			- Booleans
			- Undefined (typeof undefined)
			- Null (typeof object)
			- Symbols (ES6)
		- Non-primitive
			- Objects
	- Prototype Oriented Programing. This is the O.O.P of Javascript
		- Creating Classes and prototyping
		- Adding properties and methods to a class
		- Class instances as Objects.
		- Extending already existing classes using `.prototype`
4. Data Structures in Javascript. Stacks, Queues and other data structures in other languages can be custom built in Javascript, but don’t exist by default. Listed are the defaults:
	- Object literals (using Objects)
	- Arrays
5. Using Javascript libraries in your full stack application.
	- Adding the libraries to your application
		- Front end - The SCRIPT tag in HEAD tag of  the DOM.
		- Server side scripts are imported or required into the scripts that depend on such libraries
	- Installing Javascript libraries
		- What are package managers?
		- What package manager is used in your stack for Javascript?
		- List of common package managers
			- npm \- Node.js
			- bower \- Universal, used with PHP, Python
			- RoR uses the gem file for managing all its dependencies both ruby and javascript.
	- Common libraries in Javascript
		- JQuery
		- Bootstrap
		- Materialize
		- Angular
6. Javascript as an asynchronous language
	- How are callbacks used?
	- Why are non-blocking processes necessary in Javascript.
7. What is a minified script?
	- What are the advantages of using Minified scripts (cutting overhead)


## Behaviors
1. When I need to write Javascript, i will write neat, conformal Javascript syntax, with comments, following the recommended style guides and keeping my code DRY in the process.
2. When I need to loop in Javascript, I will use the most appropriate Loop control flow (e.g for-in for objects, for for Arrays) to iterate through the collection.
3. When I need to encapsulate variables or control the scope of variables, I will place them in functions / closures where there are required.
4. When I need to create a reusable service or function, I will make use of a well defined class (literal function) having the prototypes and / or properties (as variables or methods) pertinent to it’s usage.
5. When I need to extend the functionality of an existing class I will create a prototype method, extending the already existing class, and implementing my custom method, to simplify the method’s reference when I need to use it.
6. When I need to import a Javascript library to my project, I will use the minified scripts to avoid the overhead that might come with the library (long variable names, comments, and whitespace).
7. When I need to import Javascript libraries into my full stack application, I will make use of the most appropriate package manager recommended for the stack I’m working with, for a seamless integration and application deployment.
8. When I make function calls that are asynchronous, I will make use of callback functions that process the results when these resource becomes available.


## Beliefs
1. I believe I can write DRY and well commented javascript, while adhering to the style guides, keeping my code base legible and easy to understand.
2. I believe that I will use the most appropriate control flow for conditions and loops based on the values to be compared and the type of collection to be iterated, respectively.
3. I believe I can create a class when I need a reusable resource, to avoid repetition.
4. I believe I can add functionality to an already existing class using Prototyping.
5. I believe I can isolate the scope of my variables for better security when I write sensitive methods that should be not edited in real-time.
6. I believe I can use external Javascript libraries in my full stack project handled by package managers akin to the full stack technology.
7. I believe I can take advantage of Javascript’s asynchronous nature by using callbacks to process resources in the background without distorting the user’s experience.
