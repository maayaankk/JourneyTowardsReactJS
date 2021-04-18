# JourneyTowardsReactJS

![alt text](https://www.andreasreiterer.at/wp-content/uploads/2017/11/react-logo-825x510.jpg)



# What is react and why use it?
React. js is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. ... React allows developers to create large web applications that can change data, without reloading the page. The main purpose of React is to be fast, scalable, and simple.

# Create React app
npx create-react-app my-app <br/>
cd my-app <br/>
npm start 

# Types of React Components you should know
Functional Components: In simple words, Functional components are javascript functions. ...<br />
Class Components. ...<br />
Higher-Order Components. ...<br />
Dumb Components. ...<br />
Smart Components. ...<br />
Presentational Components. ... <br />
Container components.

# Functional Component 
The simplest way to define a component is to write a JavaScript function:

function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.

You can also use an ES6 class to define a component:
