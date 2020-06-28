# Color Flip Project

# Objectives

- [_] Open the page in your web browser and examine it, then take a look at the index.html and main.js files in your editor.

- [_] Go read about arrays to get an idea of what they are, how to access values stored in them, and how to find their length.  
  https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays

- [_] Declare a variable named `colors` and assign it an array with the following literal string elements: `"white", "hotpink", "lightgreen", "deepskyblue", "coral"`

- [_] Declare a variable named `colorIndex` and assign it the number `0`

- [_] Define a function named `stepPageBackgroundColor`.

- [_] Inside the function's code block do the following:

  - [_] Add `1` to `colorIndex`

  - [_] Use an if statement to check if `colorIndex` is greater than or equal to the number of items in the `colors` array and if it is reset it's value back to 0;

  - [_] After the if statement, set the page's background color to the color that is stored in the `colors` array, using the current index number stored in the `colorIndex` variable.

- [_] Outside of your function, at the end of the script file, declare a new variable named `colorButton` and assign it a reference to the button that is on the page.

- [_] Use add an event listener to `colorButton`. It should listen for `click` events and execute the `stepPageBackgroundColor` function when a click event occurs.

- [_] Refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console. When the button on the page is pressed it should swap the background color between the two colors defined in the JavaScript.

# Dive Deeper

Listed below are items for further exploration.

- [_] Read through the Arrays tutorial and browse the Array object documentation  
  https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
