# Uncommon HTML Bug: Incorrect getElementById Method

This repository demonstrates a subtle bug related to accessing HTML elements using JavaScript.

## The Bug

The `bug.html` file contains a simple HTML page with a div element.  The JavaScript code attempts to access this div using `document.getElementByIdx()`, which is an incorrect method.  The correct method is `document.getElementById()`. This results in a runtime error because the method does not exist.

## The Solution

The `bugSolution.html` file demonstrates the correct method for accessing the div element using `document.getElementById()`.