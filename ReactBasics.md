# React Basics

Components - no components inside other components; not when you are defining them.

Virtual views in memory

    HTML is created from the JavaScript
    Version of the page is kept in memory and then compared for updating only the items that changed
    Does not enhance HTML (which is what other languanges use)
    Uses JavaScript to render HTML - tree reconciliation

Arrow Function Expression - has a shorter syntax than a function expression and does not have its own this, 
arguments, super, or new.target. These function expressions are best suited for non-method functions, and they 
cannot be used as constructors. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions 

Spread Operator {...name}

## Immutabiltiy and Mutation
### Why Immutability Is Important

There are generally two ways for changing data. The first method is to mutate the data by directly changing the values of a variable. The second method is to replace the data with a new copy of the object that also includes desired changes.

Data change with mutation
```
var player = {score: 1, name: 'Jeff'};
player.score = 2;
// Now player is {score: 2, name: 'Jeff'}
```

Data change without mutation
```
var player = {score: 1, name: 'Jeff'};

var newPlayer = Object.assign({}, player, {score: 2});
// Now player is unchanged, but newPlayer is {score: 2, name: 'Jeff'}

// Or if you are using object spread syntax proposal, you can write:
// var newPlayer = {...player, score: 2};
```

The end result is the same but by not mutating (or changing the underlying data) directly we now have an added benefit that can help us increase component and overall application performance.

## Spread Operator
```
let c = incominObject
let z = {...c; name: 'joe'}  // you can add new pairs after the object has been iterated with the spread operator
```
