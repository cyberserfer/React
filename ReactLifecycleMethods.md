# React Lifecycle Methods

## Mounting Lifecycle Methods

There are three categories of lifecycle methods: mounting, updating, and unmounting. 

Mounting lifecycle methods:

A component "mounts" when it renders for the first time. This is when mounting lifecycle methods get called.

There are three mounting lifecycle methods:

    componentWillMount
    render
    componentDidMount

When a component mounts, it automatically calls these three methods, in order. Lifecycle events only execute the first time that a component renders.

## Updating Lifecycle Methods

There are two categories that we haven't yet discussed: updating and unmounting lifecycle methods. This lesson covers both.

What is updating?

The first time that a component instance renders, it does not update. A component updates every time that it renders, starting with the second render.

There are five updating lifecycle methods:

    componentWillReceiveProps
    shouldComponentUpdate
    componentWillUpdate
    render
    componentDidUpdate

Whenever a component instance updates, it automatically calls all five of these methods, in order.
