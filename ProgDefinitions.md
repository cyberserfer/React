# Programming Definitions

***arguments object*** - a local variable available within all (non-arrow) functions. You can refer to a function's arguments within the function by using the arguments object. This object contains an entry for each argument passed to the function, the first entry's index starting at 0. The arguments object is not an Array. It is similar to an Array, but does not have any Array properties except length.
```
arguments[1] = 'new value'; // set argument

arguments[0] // refer to argument
arguments[1]
```

***arrow function expression*** - shorter syntax than a function expression and does not have its own this, arguments,
super, or new.target. These function expressions are best suited for non-method functions, and they cannot be used as constructors.

***Components*** - user interfaces are described using components. 

    like functions
    Has property and state
    Reusable and composable
    Can manage a private state (unlike true functions)
    
Always start component names with a capital letter.

```For example, <div /> represents a DOM tag, but <Welcome /> represents a component and requires Welcome to be in scope.```

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
