# React interview notes
### 1. React JS:
React. js is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components.
### 2. Javscript:
JavaScript is a text-based programming language used both on the client-side and server-side that allows you to make web pages interactive. Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.
### 3. Features of React:
* **Jsx** - A syntax extension to javascript. Html + javascript
* **Components** -  Building blocks of React app, can have multiple components, splits the user interface into independent, reusable parts that can be processed separately.
* **Virtual DOM** - Lightweight representation of the real DOM in the memory, When the state of an object changes, virtual DOM changes only that object in the real DOM, rather than updating all the objects.
* **One way  data binding** - Keeps everything modular and fast. A unidirectional data flow, you often nest child components within parent components.
* **High Performance** - React updates only those components that have changed, rather than updating all the components at once. This results in much faster web applications.
### 4. How web browsers read JSX directly?
Web browsers can only read regular JS objects and JSX is not a regular JavaScript object. For a web browser to read a JSX file, babel ransforms it into a regular JavaScript object.
### 5. What is the virtual DOM?
DOM - Document Object Model. Represents an HTML document with a logical tree structure. Each branch of the tree ends in a node, and each node contains objects.
### 6. Why React?
* **Easy creation of dynamic applications** - React makes it easier to create dynamic web applications because it provides less coding and provides more functionality
* **Improved performance** - React uses virtual DOM, which makes web applications perform faster. Updates only those components in the real DOM, whose states have changed, rather than updating all the components
*  **Reusable Components** - they can be reused through the application, which, in turn, dramatically reduces the development time of an application
*  **Unidirectional data flow** - The data flows in a single direction so it becomes easier to debug errors
*  **Dedicated tools for easy debugging** - Facebook has released a chrome extension that we can use to debug React application for faster & easier debugging.
### 7. ES5 Vs ES6:
|ES5|ES6|
----|----
|Supports primitive data types that are<br /> string, number, boolean, null, and undefined|Symbol is introduced in addition to that|
|One way to define varibale var|Two eays to define varibles const let|
|both function and return keywords are used to define a function|Arrow function,a new feature introduced in ES6 don't require<br /> the function keyword to define the function|
|var require = require('react');|import React from 'react'|
## Controlled vs Uncontrolled components
## Higher order component
## useeffectlayout vs useEffect
## useRef
## When to use react hooks
## lifecycle order
## lifecycle and their hook alternatives
## componentDidMount vs useEffect
## How to reduce bundle size in react
## Improve performance using hooks
## useReducer
## React.memo vs useMemo
## setState
