## BEST_JUICE_RUN-ANALYTICAPP

## Overview
This analytic application created using Best juice run company data shows the usage of JavaScript in creating interactive dashboards.

## Features on Page 1
 
✿ **Panel Container Widget**

- _**Numeric point charts & dynamic Filters**_ -for displaying KPI Indicators Gross Margin and Quantity sold for the set date filters.
  
✿ **Tab Strip Container Widget**
- _**Tab 1**_ - Gross Margin Tab contains a dropdown box and buttons for selecting a particular period month /year. The selected data is displayed in horizontal charts.
- _**Tab 2**_ -Quantity Sold Tab contains a dropdown box for selecting the product category. The selected product category data is displayed in a table.


## Creation of global script variables 
- txtname variable is set to the value of year selected in button 2013,2014,2015 and all from page 1.
- year variable is used to filter the data in the table on page 2.
- viewmode variable is passed as an URL Parameter.
  
## Features on Page 2
  - The table displays all accounts values for the selected button from page 1. This is done by checking the value of the script variable txtaname and displaying the data for script variable year.
    

## Features on Page 3 
- **Leader Board**- representing the top 3 locations with high gross margins.  Also displays the rankings of the rest of the locations with their gross margins. This is by calling a script function. 

## Creation of script object function SF_Generate
- the function is used to generate the results of the leaderboard and rankings on page 3. I have used console.log function to get the details of the array i.e the values of the table used to generate the rankings. This table contains the details of the locations and grosss margin sorted in descending order and is hidden.


