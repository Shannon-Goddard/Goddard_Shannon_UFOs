# Goddard_Shannon_UFOs  



## Summary
In this module, we’ll build a table using data stored in a JavaScript array. We’ll also create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.
We’ll customize our webpage using Bootstrap, and equip our table with several fully functional filters that will allow users to interact with our visualizations  

## Objectives
By the end of this module, we will be able to: 
- Explain the strengths and weaknesses of JavaScript “standard” and JavaScript version ES6+. 
- Describe JavaScript syntax and ideal use cases. 
- Build and deploy JavaScript functions, including built-in functions. 
- Convert JavaScript functions to arrow functions. 
- Build and deploy forEach (JavaScript for loop). 
- Create, populate, and dynamically filter a table using JavaScript and HTML.




## Challenge Summary
In this challenge, we will create additional filters for the webpage. The advanced filtering capability will allow users to filter the data by multiple factors.  

## Objectives  
The goals of this challenge are to:
- Create, update, and deploy JavaScript functions to provide additional table filters.
- Update and deploy forEach (for loop) to loop through the filters and update them with user input.
- Update and populate the dynamic filters and table using JavaScript and HTML.

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
