# What is React? 
JavaScript library used for building single page applications. Uses a declarative approach: you define the state of your application and React handles the updates. When the state changes, React automatically updates the UI to reflect the new state.

# Why do I like React?
- Uses JSX syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
- It uses Virtual DOM instead of Real DOM considering that Real DOM manipulations are expensive.
- Uses reusable/composable UI components to develop the view. Enhances code maintainability, reusability, and readability for easier debugging. 
- I get to focus on the logic and functionality of the application while React handles the complicated DOM manipulations and rendering. 

# What is the difference between Element and Component?
An element is a plain object cannot be mutated once it is created. A component is a function which can take props and returns a JSX tree as an output. 

# What is the difference between state and props? 
The state entity is managed by the component itself and can be updated. Unlike props, state can be modified by the component and is used to manage the internal state of the component. Moreover, changes in the state trigger a re-render of the component and its children. The components cannot become reusable with the usage of state alone.

On the otherhand, props are passed to a component by its parent component and are read-only, meaning that they cannot be modified by the own component itself. Also, props can be used to configure the behavior of a component and to pass data between components. The components become reusable with the usage of props.

# What is "key" prop and what is the benefit of using it in arrays of elements?
A key is a special attribute you should include when mapping over arrays to render data. Key prop helps React identify which items have changed, are added, or are removed. Keys should be unique among its siblings.

# What is Virtual DOM?
The Virtual DOM (VDOM) is an in-memory representation of Real DOM. The representation of a UI is kept in memory and synced with the "real" DOM. It's a step that happens between the render function being called and the displaying of elements on the screen. This entire process is called reconciliation.

