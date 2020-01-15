## Comparison Operators
- == is seeing if two things are the same. Just compares the value. Ex. 'hello' vs 'goodbye'
- === compares the value and the data type.  Ex. '3' does not equal 3.
- != opposite of == is saying that it does not equal whatever you are comparing.  'White' does not equal 'black'
- !== opposite of === is saying that it does not equal and is comparing the value and the data type.

- > = greater than
- < = lesser than
- >= greater than or equal to
- <= lesser than or equal to

## Logical Operators

((5<2) && (2>=3))
Expression 1 = 5>2 - Expression 2 = 2>=3 - Expression 3 = &&
- && = logical and tests more than one condition
- || = logical or tests at least one condition
- ! = takes a single Boolean value and inverts it

## Loops
- For
    - Most common loop
    - If you need it to run a specific number of times
    - The condition is usually a count which is used to tell how many times the look should run

- While
    - Not sure how many times it needs to run
    - Can be something other than a counter
    - Will continue to look as long as the condition is true

- Do While
    - Very similar to While loop
    - Major difference - it will always run the statements inside the curly braces at least once, even if the condition evaluates to false

for (var i = 0; i < 10; i++) {
    document.write(i);
}

- for = keyword
- (var...) = condition (counter)
- document.write(i); = code to execute during loop

Condition (counter)
- var i = 0 This is the Initialization.  It creates a variable and sets it to 0.  Only used the first time it runs.
- i < 10; This is the Condition.  It will run until it his the specific number.
- i++ This is the Update.  Every time the loop has run the statements in the curly braces, it adds one to the counter.

### Example
var i = l ; This will set counter to 1
var msg = ' ' ;  Message 
This will store 5 times table in a variable 
while (i < 10) { 
    msg += i + ' x 5 = ' + (i * 5) + '<br />'; i++; 
}
document.getElementByid('answer').innerHTML = msg;

- An example of awhile loop. It writes out the 5 times table. Each time the loop is run, another calculation is written into the variable called msg.
- This loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run.
- Inside the code block there are two statements:
    1. The first statement uses the+= operator, which is used to add new content to the msg variable. Each time the loop runs, a new calculation and line break is added to the end of the message being stored in it. So+" works as a shorthand for writing: msg = msg + 'new msg' (See bottom of the next page for a breakdown of this statement.)
    2. The second statement increments the counter variable by one. (This is done inside the loop rather than with the condition.) 
