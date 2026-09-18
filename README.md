### 1. What are props in React?
Props stand for properties and are a way to pass data and configuration to a React component, allowing components to be more flexible and reusable

### 2. What happens when React renders a string versus a function?
When React.createElement receives a string as its first argument, it creates a DOM node with that tag name (e.g., 'div', 'h1'). When it receives a function or React component, React executes that function/component to render it. Both are treated similarly by the API, allowing components and DOM elements to be used interchangeably in the component tree.

### 3. What is the key concept behind React's component design?
React combines the model, view, and view model into a single component, encapsulating all logic for a small piece of functionality in one place

### 4. How can you pass additional information to a React component?
You can pass additional information to a React component by providing an object with properties when creating the element, which can then be accessed via the props parameter in the component function

### 5. What is the difference between passing a string versus a function/component to React.createElement?
If you pass a string to React.createElement, it will render that string as a DOM node (like 'div', 'h1', 'p'). If you pass a function or React component, React will try to render that component by executing the function.

### 6. In vanilla React (without JSX), what is one way to return multiple sibling elements from a component using React.createElement?
By passing them as array to the parent element.

### 7. What happens when React.createElement receives a string as its first argument?
It outputs that string as DOM Node.

### 8. How do you access properties passed to a React component created with React.createElement?
Through the props parameter in the component function.