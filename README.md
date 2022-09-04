### Module 11 Challenge, UFO Sightings with JavaScript

#### Deliverable 2: A written report on the UFO analysis

## Overview of Project: 

The purpose of this project was to create a webpage with dynamic table, and making this table filterable by using multiple criteria at the same time. We were provided with data for UFO sightings, and we were needed to create a table with this given data. In this module we used JavaScript programming language, while HTML/CSS and Bootstrap were used to improve the looks of the webpage.

With this exercise I was able to learn more about the ES6+ version of JavaScript. I learnt about the syntax, components such as variables, objects, arrays, conditionals, loops, arrow functions and forEach function . I learnt that Dev Tools are used as the console for JavaScript command line interface. I also learnt about the how story boarding is important in fabricating a webpage. I learnt about Data Driven Documents (D3) which is a JavaScript library to add interactive and filtering ability to the tables. D3.js is also used to listen for the events. A link to Bootstrap’s content delivery network (CDN) was added to the HTML code to enhace the asthetics of the website. 

## Results: 

**•	The Web Page**

The JavaScript code was assembled to build a functional table with the ability to filter the data. However, a HTML page is required to test and showcase this table. Hence, I created the following web page in HTML/CSS. 

![Picture_1](https://github.com/gothwalritu/UFOs/blob/main/screenShots/2022-09-04.png)

**•	The Initials looks of the table and the search bars**

I used the different ids which were created in the app.js, as search parameters. I added “Date”, “City”, “State”, “Country”, and “Shape” as search filters with some place holder values in the search bars. Initially when the webpage opens, the table is fully loaded as shown below.

![Picture_2](https://github.com/gothwalritu/UFOs/blob/main/screenShots/2022-09-04%20(1).png)

**•	The Filtered results**

When I enter any relevant parameter in the search bar, the table is filtered automatically as it is noticing the change in the search bars and shows us the results pertaining to that search parameter. For example, if I want to see the results for the UFO sightings whose shape is a circle, then I get the following results.

![Picture_3](https://github.com/gothwalritu/UFOs/blob/main/screenShots/2022-09-04%20(2).png)

## Summary: 

### Drawback:

This webpage with the ability to filter the table, one assumption was made that user must know the specific keywords for date, city, state, country, shape to perform the search. And if there is no match for the keyword then there is no results in the filtered table.

### Recommendations:

1.	There could be a search bar for the month or a date range in which the UFO sightings occurred to avoid the necessity of entering a specific date.

2.	The capabilities of the functioning of the search bar definitely requires some improvement to catch most of the entered keywords. For example, it should not be case sensitive and should not be affected by the entered spaces in between the keywords. 

3.	If there are no results for the entered filter keywords, then some message should be displayed to inform the user that there are no results for these filters.
