# Landing Page

This project aims to give you real-world scenarios of manipulating the DOM. The functionality being used serves two purposes: to append dynamically added data to the DOM, and to show how javascript can improve the usability of an otherwise static site.

Open and view the Project using the .zip file provided or at my [Github Repository](https://github.com/madhur-taneja/Landing-Page).

The project is also hosted on [Github](https://madhur-taneja.github.io/Landing-Page/).

## Table of Contents

- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
	- [Instructions](#instructions)
- [Development](#development)
- [Features](#features)
- [Running the App](#running-the-app)
- [References](#references)

## Gettiing Started

The starter project can be downloaded from [here](https://github.com/udacity/fend/tree/refresh-2019/projects/landing-page).

The project will be evaluated by a Udacity code reviewer according to the Landing Page project [rubric](https://review.udacity.com/#!/rubrics/2658/view)

### Tools Required

No additional tools are required apart from a text-editor of your choice. 

### Installation

No additional installation is required for this project

### Instructions

* The starter code has some HTML and CSS styling to display a static version of the Landing Page project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.  

* To get started, open `js/app.js` and start building out the app's functionality  

* For specific, detailed instructions, look at the project instructions in the Udacity Classroom.

## Development

* First challenge is to build the navbar dynamically based on the sections of the page. This can be achieved by using the below mentioned methods of javascript
    > `for or forEach loop` </br>
      `document.getElementById` or  `document.querySelector` </br>
      `document.createElement` </br>
      `.setAttribute` </br>
      `.appendChild` </br>

* Next step would be to add functionality to distinguish the section in view. This can be achieved by using the `.getBoundingClientRect()` method of javascript. Active states have to be added to the sections as well as the corresponding nav-links.  

* Last part is to add the functionality to scroll to sections. This can be achieved by using the below mentioned methods of javascript
    >  scroll(), scrollBy(), and scrollIntoView()

## Features

* Active State change for sections and nav links as user scrolls the viewport
* Smooth scrolling using `scrollIntoView` when a nav link is clicked 

## Running the App

* Open the project through the `.zip` file provided and extract the files. 
  > Open `index.html` in the browser of your choice.

## References

* To check if an element is in Viewport or not from [vanillajstoolkit](https://vanillajstoolkit.com/helpers/isinviewport/) 
* To handle the scrolling part, I have used [scrollIntoView()](https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView)
