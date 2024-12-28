# Uncommon HTML Bug: Accessing Non-Existent DOM Properties

This repository demonstrates a subtle bug in HTML/JavaScript related to accessing properties of DOM elements that do not exist. The bug doesn't throw an error, but results in undefined values, which can lead to unexpected behavior in the application. 

The `bug.html` file contains the buggy code, while `bugSolution.html` offers a corrected version with proper null checks.  The issue is that accessing a non-existent property returns `undefined` silently, leading to potential runtime issues. The solution implements a check for the existence of the element and its property before use.