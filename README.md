# Javascript interview questions and answers:

#Javascript interview questions and answers:

1.Explain Destructuring in ES6.

Ans: Destructuring was introduced in ES6 as a way to extract data from arrays and objects into a single variable. It is possible to extract smaller fragments from objects and arrays using this method. The following is an example.

2.What is the output ?

let greeting =['Good','Morning'];  
let [g1, g2] = greeting;  
console.log (g1, g2);

2.What is JSX?

3.Differentiate between real DOM and virtual DOM?

4.What is the difference between == and === operators in JavaScript?

5.What is the difference between “var” and “let” keywords in JavaScript?

6.What is the output let x = false - true; console.log(x)

Ans: -1;

7.What is the difference between querySelector and getElementById?

Ans:querySelector is a more versatile method that allows you to select elements using CSS-like selectors, while getElementById specifically selects an element with the specified ID.
8.How can you prevent the default behavior of an event in JavaScript?

9.What is the difference between localStorage and sessionStorage in JavaScript?

Ans:localStorage persists data even after the browser window is closed and is accessible across different browser tabs/windows of the same origin.
sessionStorage stores data for a single browser session and is accessible only within the same tab or window.

10.Why should I use Redux?

11.What are the components of Redux?

Ans: 

Store: Holds the state of the application.

Action: The source information for the store.

Reducer: Specifies how the application's state changes in response to actions sent to the store.

12.Mention some features of Next JS.

Ans: 1. Server-Side Rendering (SSR) 2. Static Site Generation (SSG) 3. File System-Based Routing 4. API Routes

12.What is the use of render() in React?

14.What is a higher-order component in React?

Ans:A higher-order component acts as a container for other components. This helps to keep components simple and enables re-usability. They are generally used when multiple components have to use a common logic. 

15.What are the basic rules of hooks and tell me some name of hook?

Ans: Hooks have some rules: They must be used only at the top level of a function
component, hooks mustbe called in the same order every time the component
renders, and they cannot be called conditionally.

16.What is the difference between useCallback and useMemo hooks?

Ans:
useCallback is used to memoize functions, preventing unnecessary re-creation of
functions on re-renders. useMemo is used to memoize values, caching the result of
expensive calculations and avoiding recomputation.
