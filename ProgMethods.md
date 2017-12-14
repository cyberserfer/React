# React Programming Methods

***push*** - The push() method adds one or more elements to the end of an array and returns the new length of the 
array. Syntax: ```arr.push([element1[, ...[, elementN]]])```
```
var numbers = [1, 2, 3];
numbers.push(4);

console.log(numbers); // [1, 2, 3, 4]

numbers.push(5, 6, 7);

console.log(numbers); // [1, 2, 3, 4, 5, 6, 7]
```

***this.setState*** - Any time that you call this.setState(), this.setState() AUTOMATICALLY calls .render() as soon as the state has changed. Think of this.setState() as actually being two things: this.setState(), immediately followed by .render(). That is why you can't call this.setState() from inside of the .render() method! this.setState() automatically calls .render(). If .render() calls this.setState(), then an infinite loop is created.
```
this.setState({ color: newColor });
```
