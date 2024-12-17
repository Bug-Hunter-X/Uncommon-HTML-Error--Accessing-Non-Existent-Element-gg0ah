# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a subtle HTML error that can be easily overlooked. The bug lies in attempting to access and modify a DOM element that does not yet exist in the page's structure.

## Bug Description
The `bug.html` file contains a script that attempts to set the `innerHTML` of an element with the ID "nonExistentElement".  Since this element is not defined in the HTML, this will cause a JavaScript runtime error, potentially crashing the script or causing unexpected behavior. 

## Solution
The `bugSolution.html` file provides a corrected version where the script first checks for the existence of the element before attempting any operations.  This avoids the runtime error and ensures the script behaves predictably.

## How to Reproduce the Bug
1. Open `bug.html` in a web browser.
2. Observe the JavaScript error in your browser's developer console.

## How to See the Solution
1. Open `bugSolution.html` in a web browser.
2. Verify that no errors are thrown and that the appended text is correctly added to the existing element.