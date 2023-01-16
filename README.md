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
      
  2. Components
      React website is composed from small components.
      Reusable components.
      
      Each component is a javascript functions that takes 
      data(state/props) and returns representation of UI in javascript (JSX).
      
      
      
      
