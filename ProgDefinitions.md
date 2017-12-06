# Programming Definitions

***arrow function expression*** - shorter syntax than a function expression and does not have its own this, arguments,
super, or new.target. These function expressions are best suited for non-method functions, and they cannot be used as constructors.

***expression*** -  a combination of one or more explicit values, constants, variables, operators, and functions that the 
programming language interprets. JavaScript has the following expression categories:

  Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.) 
  String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.) 
  Logical: evaluates to true or false. (Often involves logical operators.) 
  Object: evaluates to an object. (See special operators for various ones that evaluate to objects.)"

***object literal*** - comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code. Object literal property values can be of any data type, including array literals, functions, and nested object literals. Here is another object literal example with these property types:
```
var Swapper = {
    // an array literal
    images: ["smile.gif", "grim.gif", "frown.gif", "bomb.gif"],
    pos: { // nested object literal
        x: 40,
        y: 300
    },
    onSwap: function() { // function
        // code here
    }
};
```

***promise*** - represents the eventual result of an asynchronous operation. It is a placeholder into which the successful result value or reason for failure will materialize.

***statements*** - comprises the body of the function.
```
function name([param[, param[, ... param]]]) {
   statements
}
```
