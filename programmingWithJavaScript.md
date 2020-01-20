## Learning from Read 07 Progrmming with Java Script

HTML Elements - add to the content of a page to describe structure
- Ex. -p class="fruit">peach-/p-
- class is the attribute name
- fruit is the attribute value

CSS Rules - indicate how the contents of one or more elements should be displayed in the browser
- Ex. .fruit {color: pink;}
- .fruit is the selector
- {color: pink;} is the declaration block
- color is the property name
- pink is the property value

A Script is a series of instructions that a computer can follow to achieve a goal.  Similar to a cook following a recipe.

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it
- Start with the big picture of what you want to achieve, and break that down into smaller steps
    - 1.  Define the goal/task you want to achieve
    - 2.  Design the sscript by splitting the goal/task out into a series of steps
    - 3.  Code each step, but spend the time designing your script before you actually start writing code

Vocabulary - The words that computers understand
Syntax - How you put those words together to create instructions computers can follow

### Expressions
1.  Expressions that just assign a value to a variable = var color = 'beige';
2.  Expressions that use two or more values to return a single value = var area = 3 * 2;

### Operators
- Assignment operators - assign a value to a variable - ex. color = 'beige';
- Arithmetic operators - perform basic math - ex. area = 3 * 2;
- String operators - combine two strings - ex. greeting = 'Hi ' + 'Molly';
- Comparison operators - compare two values and return true or false - ex. buy = 3 > 5;
- Logical operators - combine expressions and return true or false - ex. buy = (5 > 3) && (2 < 4);

### Arithmetic Operators
- Addition = +
- Subtraction = -
- Division = /
- Multiplication = *
- Increment = ++
- Decrement = --
- Modulus = % - divides two values and returns the remainder

Order of execution is similar to normal math - multiplication and division first then left to right on addition and subtraction

## Functions
Functions let you  group a series of statements together go perform a specific task

- Not all functions run when you load the page.  If you want one to load later, you need to name it.
    - Calling is when you ask it to perform it's task
    - A code bloxk is where the steps are packaged for the task
    - Parameters are when pieces of information are needed to be passed to the function to run
    - Return value is an output you are expecting from the task
Ex. HTML - <!DOCTYPE html> <html> <head> 
Before the closing </body> tag, you can see the link to the JavaScript file. The JavaScript file starts with a variable used to hold a new message, and is followed by a function called updateMessage(). 
<ti tle>Basic Function</title> <link rel ="stylesheet" href="css/c03.css" /> </head> <body> <hl>TravelWorthy< /hl> <div id="message">Welcome to our site!< /div> <script src="js/basic-function.js"></script> < / body> </html> 

Ex. JS - var msg = 'Sign up to receive our newsletter for 10% off!'; function updateMessage() { var el = document.getElementByld('message'}; el .textContent = msg; } updateMessage(}; 
l

### Components of a Function
- Ex. function sayHello () {
    document.write('Hello')
}

- function is the function keyword
- sayHello is the function name
- Everything within the curly braces is the code block

### Calling a Function
- To run the function that is above in the Components of a Function, you need to call the function
    1.  The function can store the instructions for a specific task
    2.  When you need the script to perform that task, you call the function
    3.  The function executes the code in that code block
    4.  When it has finished, the code continues to run from the point where it was initially called

    First to run will be the function line.  Second will be the function call of sayHello().  Third, the document.write result

### Declaring functions that need information
    - Ex. function getArea (width, height) {
        return.width * height
    }

    - (width, height) - parameters
    - width * height - the parameters are used like variables within the function

### Calling functions that need information
- getArea(3, 5) - arguments as values
- wallWidth = 3, wallHeight = 5, getArea(wallWidth, wallHeight) - arguments as variables

### Getting a single value out of a function

- Ex. function calculateArea(width, height) {
    var area = width * height
    return area
}
var wallOne = calculateArea (3, 5)
var wallTwo = calculateArea (8, 5)