# Programming With Javascript

## Writing a Script
<ol>
<li>Define the Goal<li>
<ul> Define the task you want to achieve</ul>
<li>Design the Script</li>
<ul> Split the goal into a series of tasks that are going to be involved in solving this puzzle. Can be represented using a flowchart.</ul>
<li>Code Each Step</li>
<ul>Each step needs to be written in a programming language that the computer understands.</ul>

## Declaring and Calling Functions That Need Info
> Sometimes a function needs specific info to perform its task. In such cases, when you declare the function you give it parameters. Inside the function, the parameters act like variables.
<pre>
function getArea(width, height) {
    return width * height;
}
</pre>
- width and height are both parameters and usedd like variables within the function
### Arguments as Values
getArea(3, 5);
- The function below is called, the number 3 will be used for the width of the wall, and 5 will be used for the height.
### Arguments as Variables
<pre>
wallWidth = 3;
wallHeight = 5;
getArea(wallWidth, wallHeight)
</pre>
- No need to specify actual valueswhen calling a function - you can use variables in their place.
## Getting a Single Value Out of a Function
> Some functions return information to the code that called them. For example, when they perform a calculation, they return the result.
<pre>
function calculateArea(width, height) {
    var area = width * height;
    return area;
}
var wallOne = calculateArea(3, 5);
var wallTwo = calculateArea(8, 5);
</pre>
## Getting a Multiple Values Out of a Function
> Functions can return more than one value using an array. For example, this function calculates the area and volume of a box.
<pre>
functio getSize(width, height, depth) {
    var area = width * height;
    var volume = width * height;
    var sizes = [area, volume];
    return sizes;
}
var areaOne = getSize(3, 2, 3)[0];
var volumeOne = getSize(3, 2, 3)[1];
</pre>
- areaOne holds the area of a box that is 3 x 2. Area is the first value in the sizes array.
- volumeOne holds the volume of a box that is 3 x 2 x 3. Volume is the second value in the sizes array.
## Expressions
> An expression evaluates into a single value.
- There are two types of expressions:
    - Expressions that just assign a value to a variable.
        - In order for a variable to be useful it needs a value. This is done using the assignment operator(=).
            - "var color = 'beige';" the value of color is now beige.
        - var is given a special value of undefined. It will change when you assign a value to it.
    - Expressions that use two or more values to return a single value
        - You can perform operations on any number of individual values to determine a single value.
            - "var area =3 * 2;" the value of area is now 6.
        - The expression 3 * 2 evaluates to 6. An assignment operator is used so the result of 3 * 2 is stored in the variable called area.
## Operators
> Expressions rely on operators; they allow programmers to create a single value from one or more values.
- Assignment Operators
    - color = 'beige'
    - Assigns a value to a variable
- Arithmetic Operators
    - area = 3 * 2
    - Perform basic math
- String Operators
    - Combine two strings
    - greeting = 'Hi' + 'Molly';
- Comparison Operators
    - Compare two values and return true or false
    - buy = 3 > 5;
- Logical Operators
    - Combine expressions and return true or false
    - buy = (5 > 3) && (2 < 4);
        - the value of buy is now true

## Arithmetic Operators
<pre>
Addition (+), adds one value to another, 10+5=15
Subtraction (-), subtracts one value from another, 10-5=5
Division (/), divides two values, 10/5=2
Multiplication (*), multiplies two values, 10*5=50
Increment (++), Adds one to the current number, i=10; 11
                                                i++;
Decrement (--), subtracts one from the current number, i=10; 9
                                                        i--;
Modulus (%), divides two numbers and returns the remainder, 10 % 3 = 1
