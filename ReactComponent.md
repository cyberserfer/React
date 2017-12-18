# React Components

Function Component - simplest form of function. Receives props (properties) and returns what looks like HTML

Class Component - more featured function. Maintains a private state which gets updated when changed. Can only change their
internal state and not their properties.

Props - fixed value

State - can be changed

*Presentational component* will always get rendered by a *container component*.

Stateless Functional Component - A component class written as a function.

Normal way to display a prop:
```
export class MyComponentClass extends React.Component {
  render() {
    return <h1>{this.props.title}</h1>;
  }
}
```

Stateless functional component way to display a prop:
```
export const MyComponentClass = (props) => {
  return <h1>{props.title}</h1>;
}
```

Normal way to display a prop using a variable:
```
export class MyComponentClass extends React.component {
  render() {
  	let title = this.props.title;
    return <h1>{title}</h1>;
  }
}
```

Stateless functional component way to display a prop using a variable:
```
export const MyComponentClass = (props) => {
	let title = props.title;
  return <h1>{title}</h1>;
}
```
