# Landing Page Project

This project aims to give you real-world scenarios of manipulating the DOM. The functionality being used serves two purposes: to append dynamically added data to the DOM, and to show how javascript can improve the usability of an otherwise static site.

## Table of Contents

- [Instructions](#instructions)
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
    - [Development](#development)
- [References](#references)


## Instructions

> The starter project can be downloaded from [here](https://github.com/udacity/fend/tree/refresh-2019). It has some HTML and CSS styling to display a static version of the Landing Page project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.  

> To get started, open `js/app.js` and start building out the app's functionality  

> For specific, detailed instructions, look at the project instructions in the Udacity Classroom.

> The project will be evaluated by a Udacity code reviewer according to the Landing Page project [rubric](https://review.udacity.com/#!/rubrics/2658/view)


## Gettiing Started

### Tools Required

No additional tools are required apart from a text-editor of your choice. 

### Development

* First challenge is to build the navbar dynamically based on the sections of the page. This can be achieved by using the below mentioned methods of javascript
    > `for or forEach loop` </br>
      `document.getElementById` or  `document.querySelector` </br>
      `document.createElement` </br>
      `.setAttribute` </br>
      `.appendChild` </br>

* Next step would be to add functionality to distinguish the section in view. This can be achieved by using the `.getBoundingClientRect()` method of javascript. Active states have to be added to the sections as well as the corresponding nav-links.  

* Last part is to add the functionality to scroll to sections. This can be achieved by using the below mentioned methods of javascript
    >  scroll(), scrollBy(), and scrollIntoView()

## References

* To check if an element is in Viewport or not from [vanillajstoolkit](https://vanillajstoolkit.com/helpers/isinviewport/) 
* To handle the scrolling part, I have used [scrollIntoView()](https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView)