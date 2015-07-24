# Programming-Language

## About program

Programming Language is simple program but powerful enough to express any calculations. It will also carry out a simple abstraction based on functions.
More about this game you can find at this link <a href="http://eloquentjavascript.net/11_language.html">game</a>

## Sample Code

do(define(x, 10),
   if(>(x, 5),
      print("large"),
      print("small")))

## Keywords

* if - Conditional Statements
* while - loops through a block of code while a specified condition is true
* do - loops through a block of code once, and then repeats the loop while a specified condition is true
* define - defining of variable with name and value
* set - defining new value of variable
* fun - Function construction

## Operators

* true - logical (boolean) true
* false - logical (boolean) false
* '+', '-', 'x', '/', '==', '<', '>' - simple arithmetical operators, return a result of corresponding arithmetical function
* plus - the same as '+', math result of adding one number to another
* minus - the same as '-', math result of subtraction of one number from another
* multiply - the same as '*', math result of multiplying of one number by another
* divide - the same as '/', math result of dividing of first number by second one
* compare - the same as '==', comparison operators are used in logical statements to determine equality or difference between variables or values
* less - the same as '<', returns 'true' if first number is less than second, otherwise returns 'false'
* print - prints argument to console
* module - returns absolute value of number (unsigned number)
* random - returns random number between min and max number
* array - returns new array of data
* length - returns 'length' of specified array
* element - returns corresponding element in specified cell of specified array

## Run test

1. npm install
2. Run Tests in console
   npm test
3. Run Tests in browser
   npm run test-in-browser
   Open browser at http://localhost:9966/