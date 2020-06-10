# Operators and Loops Notes
## Comparison Operators Evaluating Conditions
- Is Equal to (==)
    - compares two values to see if they're the same
- Is Not Equal to (!=)
    - Compares two values to see if they are not the same.
- Strict Equal to (===)
    - Compares two values to check that both the data type and value are the same.
- Strict Not Equal to (!==)
    - Compares two values to check that both the data type and value are not the same.
- Greater Than (<)
    - Checks number on the left is greater than the number on the right.
- Less Than (<)
    - Checks if number on the left is less than number on the right.
- Greater Than or Equal to (>=)
    - Checks number on the left is greater than or equal to the number on the right.
- Less Than or Equal to (<=)
    - Checks number on left is less than or eual to  the number on the right
## Comparison Operator Anatomy
(score >= pass)
- "score" = operand
- "pass" = operand
- ">=" = comparison operator
- "()" = enclosing brackets

## Logical Operators
- && = logical and
    - tests more than one condition
    - ((2<5) && (3>=2)) returns true
- || = logical or
    - tests at least one condition
    - ((2<5) || (2>1)) returns true
- ! = logical not
    - operator takes a single Boolean value and inverts it.
    - !(2<1) returns true
<br>

((5 < 2) && (2 >= 3))
- (5<2) = expression 1
- (2 >= 3) = expression 2
- && = logical operator
- ((5 < 2) && (2 >= 3)) = expression 3

## Loops
> Loops check a condition. If it returns true, a code block will run. The condition will be checked again and if still true, the code block will run again. It repeats until the condition returns false.
### Common Types of Loops
- For
    - Runs code specific amount of times. The condition is usually a counter which is used to tell how many times the loop should run.
- While
    - Don't know how many times loop should run. Condition doesnt have to be a counter, and code will continue to loop for as long as the condition is true.
- Do While
    - Similar to while loop but it will always run the statements in curly braces at least once, even if condition is false.

<pre>
for (var i = 0; i < 10; i++) {
    document.write(i);
}
</pre>

- "for" = keyword
- "{}" = curly bracket
- "document.write(i);" = code to execute during loop
- "for (var i = 0; i < 10; i++) = condition(counter)

## Loop Counters
