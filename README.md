# JavaScript Homework - JavaScript and DOM Manipulation

A webpage for UFO sightings that uses JavaScript, HTML, and CSS, and D3.js. Website is at


## Background

WAKE UP SHEEPLE! The extra-terrestrial menace has come to Earth and we here at `ALIENS-R-REAL` have collected all of the eye-witness reports we could to prove it! All we need to do now is put this information online for the world to see and then the matter will finally be put to rest.

There is just one tiny problem though... our collection is too large to search through manually. Even our most dedicated followers are complaining that they are having trouble locating specific reports in this mess.

That's why we are hiring you. We need you to write code that will create a table dynamically based upon a [dataset we provide](StarterCode/static/js/data.js). We also need to allow our users to filter the table data for specific values. There's a catch though... we only use pure JavaScript, HTML, and CSS, and D3.js on our web pages. They are the only coding languages which can be trusted.


## Summary
This project creates an interactive website, specifically using D3.js to collect HTML form elements in the form of DOMs (Document Object Models) and adds event triggers to elements on the page filtering the given dataset demonstrating the use of Javascript. The dataset is a sample set of UFO sightings in the U.S. (the first two weeks of January 2010 only).

For this assignment, only the Basic page (Level 1) was completed and submitted. 
* The Basic site allows the user to enter a date in the date field and filter the table according to that date and display it once the "Filter Table" button is pressed or the Enter key is pressed on the keyboard. 

### Level 1: Automatic Table and Date Search (Required)

* Used the StarterCode/index.html to create a basic HTML page file provided.

* Used the UFO dataset provided in the form of an array of JavaScript objects, wrote code that appends a table to your web page and then adds new rows of data for each UFO sighting.

  *Columns displayed in the table:* 
  
  * date/time 
  * `city
  * state
  * country
  * shape
  * comment

* Used a date form in the HTML document and wrote JavaScript code that will listen for events and search through the `date/time` column to find rows that match user input.

![Summary](https://github.com/KGore12/javascript-challenge/blob/main/image/level-1_preview.png)

### Dataset

* [UFO Sightings Data](StarterCode/static/js/data.js)
