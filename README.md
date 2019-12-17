<p align="center">
  <img width="900" height="200" src="/pics/header.png">
</p>  

#### Table of Contents

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)  
[Challenge Overview](#challenge-overview)  
[Challenge Objectives](#challenge-objectives)  
[Challenge Summary](#challenge-summary)  
[Limitations](#limitations)


## Project Overview
In this module, we built a table using data stored in a JavaScript array. We also created filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.
We customized our webpage using Bootstrap, and equip our table with several fully functional filters that allows users to interact with our visualizations  

## Resources  
- **Data Source:** [data.js](/static/js/data.js) 
- **Software:** VS Code

## Objectives  
- Explain the strengths and weaknesses of JavaScript “standard” and JavaScript version ES6+. 
- Describe JavaScript syntax and ideal use cases. 
- Build and deploy JavaScript functions, including built-in functions. 
- Convert JavaScript functions to arrow functions. 
- Build and deploy forEach (JavaScript for loop). 
- Create, populate, and dynamically filter a table using JavaScript and HTML.  

## Summary  
<p align="center">
  <img width="900" height="400" src="/pics/webpage.png">
</p>
<p align="center">
  <img width="900" height="400" src="/pics/filter.png">
</p>
## Challenge Overview
In this challenge, we created additional filters for the webpage. The advanced filtering capability allows users to filter the data by multiple factors.  

## Challenge Objectives  
- Create, update, and deploy JavaScript functions to provide additional table filters.
- Update and deploy forEach (for loop) to loop through the filters and update them with user input.
- Update and populate the dynamic filters and table using JavaScript and HTML.  

## Challenge Summary

## Instructions  
Include five total filters in the table:
- Date
- City
- State
- Country
- Shape  

To create these additional filters, keep the following points in mind:
- You will need to create a new function that will replace your handleClick(); function. This function saves the element, value, and the id of the filter that was changed. 
- Create an if-else statement to add filter data from input, or clear the filter if no input data exists.
- Additionally, create a function named filterTable(); that will perform the following actions: 
Set the filtered data to the table.
- Loop through all of the filters and keep any data that matches the filter values.
- Rebuild the table by calling the buildTable(); function created earlier.
- Finally, using d3.selectAll();, attach an event listener to pick up changes that are made to each filter.

## Submission
Make sure your repo is up to date and includes the following:
A README.md file containing a short description of your project
The completed code saved in the proper folder structure. Hint: Make sure your JavaScript file is saved as app.js 
A clean website with a functioning filter table  

## Limitations  
JavaScript is a well-established coding language that was designed to enhance HTML. It’s the backbone of many popular visualization libraries, such as Plotly, and is often used to create custom dashboards. JavaScript also provides a high level of customization: the dashboards built to deliver visual data, such as maps or graphs, can be as simple or complex as needed.  

ECMAScript, also referred to as “ES,” is a scripting language designed to help standardize JavaScript. This means that ES provides guidelines and rules for JavaScript to follow, such as how a function should be created to run correctly, also known as the **proper syntax.**  

Because ES has provided standardization for JavaScript, it also brings updates to the language. There have been many updates to ES over the years, though the sixth update was a major one. It’s commonly known as “ES6+”, “ES2015” or “ECMAScript 2015.” This update included many updates to the syntax, which streamlined the code and made it easier to both read and write. Additional, quality of life improvements were implemented as well, such as adding Python-like generators and for...of loops. Even functions were updated and streamlined!  

Later editions of ECMAScript brought about new additions as well, but they are for more advanced uses of the language. In this module, our focus was on basic JavaScript and ES6 capabilities such as arrow functions. Both are still used today.  

There are guidelines and requirements for writing JavaScript. But because JavaScript can be added to an HTML page, there are more guidelines and requirements than for languages that can only live in a .js file or Jupyter notebook such as Python.  

A recommendation for further development...
