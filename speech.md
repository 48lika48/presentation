# Presentation Speech

## 0 React
React is one of the most popular libraries for creating complex Frontend applications. 
React is a tool for creating user interfaces. 
We can divide each page into small fragments. These fragments are called components.

## 1 React Components
A React component is a piece of code that represents part of a web page. 
A component can be declared in two ways - write a JavaScript function and using the ES6 class.
A component should never modify its properties. Such functions are called “pure”. Because they do not change their arguments and always return the same result for the same arguments.
React is very flexible, but it has one strict rule:
All React components should work as pure functions in relation to their properties.

## 2 Rendering of ReactDOM
Elements are the smallest building blocks of a React application. The React DOM takes care of updating the DOM to fit React elements itself.
Applications that are built using React only typically have one root DOM node. To draw a React element to the root DOM node, you need to pass them together to ReactDOM.render().
React elements are immutable. We know only one way to update the UI: creating a new element and passing it to ReactDOM.render().

## 3 JSX - JavaScript XML
JSX is a preprocessor that adds XML syntax to JavaScript. We can put HTML elements in the DOM without any createElement() or appendChild() methods.
Recommended using JSX with React. JSX converts HTML tags into react elements. JSX can be used on its own. This is not part of React.
After compilation, JSX expressions become regular JavaScript objects. React DOM uses the camelNotation.

## 4 State and Processing events
React components has a built-in state object. State is a tool that allows you to update the user interface based on events. 
We can find out the state of a component using the this.state construct.
We want to respond to events. This is done through functions are called event handlers. 

## 5 Asynchronous setState method
We can change the state using this.setState() if we pass this function an object representing the new state. The component on the page will always represent its current state. 
There are 3 things you need to know about setState().
*	Do not modify the state directly.
*	Status updates can be asynchronous.
*	Status updates merge.

## 6 Properties (props)
Props are arguments passed into React components. To send props into a component, use the same syntax as HTML attributes. React Props are read-only!
If your component has a constructor function, the props should always be passed to the constructor and also to the React.Component via the super() method.
Props allows components to communicate to each other. We can pass state to other components by using props.
Whatever you keep in yourself, that is “state”. To convey information to other people, you pass “props”.

## 7 Links (refs)
## 8 Thanks for attention
