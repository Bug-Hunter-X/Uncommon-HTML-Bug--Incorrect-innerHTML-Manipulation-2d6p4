# Uncommon HTML Bug: Incorrect innerHTML Manipulation

This repository demonstrates a subtle yet important bug related to manipulating the `innerHTML` property of HTML elements.  While seemingly straightforward, directly replacing `innerHTML` can lead to unexpected behavior and potential inconsistencies across different browsers.

## The Bug

The `bug.html` file showcases the problematic approach. Replacing `innerHTML` directly can interfere with existing event listeners and potentially lead to rendering issues in some browsers. 

## The Solution

The `bugSolution.html` file presents a more robust and browser-compatible solution that uses `createElement` and `appendChild`. This approach ensures cleaner manipulation of the DOM and avoids potential inconsistencies.