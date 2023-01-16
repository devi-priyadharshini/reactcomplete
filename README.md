# reactcomplete
React Complete - https://www.udemy.com/course/complete-react-developer-zero-to-mastery/

Before React - Every time user navigates, the content (HTML, css, javascript) is fetched from server.
Example: When user goes to website the Home page(HTML, css and javascript) is fetched. 
If user clicks About page in the website, the browser sends request to server to get the About Page(HTML, css and javascript). 

SPA - SPA stops browser from fetching the content each time from the server. Instead, it allow the user to download all the files - HTML,css and javascript of complete website. The downloaded javascript in the users device, will then handle the user interaction and determine what content should be displayed.

Angular.js from Google is a well known framework for building SPA. It uses Component concept for creating website.
Angular Drawback - Data flow from one component to another component is a chaos. 

React for Escape - Facebook addressed the issue Angular faced - "Data Flow" by following a certain principles. 
Angular framework was rewritten in 2014 in the mean time people used React for Front End Development.

React Concepts/Principles - 4:
  
  1. Declarative and not Imperative
      Imperative - DOM Manipulation through Javascript
      Ex: When user logged into Facebook account, programmer use
      DOM api's (document.xxxmethod) to update the HTML elements 
      wherever needed in the browser. 
      
      Declarative - Give info about the updated state.
      React will look into the modified state and update the HTML to 
      reflect state modifications in DOM. 
      
      "Declare the state and react will reflect it in the browser"
      Key Principle : Dont manipulate the DOM in react.
      
  2. Component Architecture
        React website is composed from small components/react components.
      Reusable components. 
      
      Each component is a javascript functions that takes 
      data(state/props) and returns representation of UI in javascript (JSX) - HTML syntax.
      This Jsx is converted into native Javascript objects by using Babel compiler.
     
     Componet -> takes State -> Returns JSX
     
     React.js uses the state and the components to create a virtual DOM.
     i.e,  
     function React(state, components) {} => Virtual DOM, java script version of DOM. Not real browser DOM.
     React uses this virtual DOM to update browsers DOM.
     
  3. Unidirectional Data Flow
       - React components will render based on state.
            If user modifies the state in the website, the DOM is not updated directly. 
       The state is updated instead.
       Whenever there is a change in the state, the component is rerendered reflecting the user modifications.
       
      Data Flow:
      Website rendered -> user interaction -> react tells about the change -> data updated in state -> react rerenders     
     
        This is equivalent to Source Binding in WPF. Source changed, Control Changed. Control will not update the state directly.)
      
     - Data is undirectional and restricts to moves from top to bottom.
     
     
 4. React JS is only a UI Library and not a framework. Can be used as View or Front End development for any stack.
 In Short, React is a library which creates a virtual DOM(Core react.js) and updates the browser DOM(reactDom.js).
 In react, all that needed is 2 libraries - react.js and reactDom.js.
 
 Libraries similar to React - Angular and Vue.
 
 Think in React:
 
 1. Decide on Components. 
 2. Decide the state and where we can have the state in virtual DOM
 3. What part of virtual DOM should be changed when a state is changed. 
  
  
  
  
  
      
      
      
      
