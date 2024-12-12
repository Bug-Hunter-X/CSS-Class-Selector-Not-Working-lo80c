# CSS Class Selector Not Working

This repository demonstrates an uncommon CSS issue where a class selector fails to apply styles to an element, even when the class is correctly applied. The issue is likely related to specificity, inheritance, or a conflict with other CSS rules.

The `bug.css` file contains the buggy CSS code, and the `bugSolution.css` file offers a solution.

## Bug Description
The CSS class selector `.my-class` is supposed to style elements with that class. However, in the `bug.css` file, the styles are not applied despite the element having the class correctly assigned.

## Bug Solution
The solution in `bugSolution.css` addresses this issue, and provides a working implementation.

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in your browser. 
3. Observe the unexpected styling on the element with the class `.my-class`. 
4. Open `bugSolution.html` to see the corrected styling.