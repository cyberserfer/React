# Switching based on an event
## This code shows how to switch between 2 colors based on the the click of a button

```
import React from 'react';
import ReactDOM from 'react-dom';

const green = '#39D1B4';
const yellow = '#FFD712';

class Toggle extends React.Component {
  constructor(props){
    super(props);
    this.state = { color: green };
    this.changeColor = this.changeColor.bind(this); 
    //You must include this binding to make the changeColor avaialable.
    //If you forget to bind this.changeColor and pass it to onClick, this will 
    //be undefined when the function is actually called.
  }
  
  // this is the logic that switches that color
  changeColor() {
    const newColor = this.state.color == green ? yellow : green;
    this.setState({ color: newColor });
  }
  
  render() {
    return (
      <div style={{background: this.state.color}}>
        <h1>
          Change my color
        </h1>
        <button onClick={this.changeColor}>
  				Change color
				</button>
      </div>
    );
  }
}

ReactDOM.render(<Toggle />, document.getElementById('app'));
```
