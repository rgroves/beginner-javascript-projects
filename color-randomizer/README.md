# Color Flip Project

# Objectives

- [_] Open the page in your web browser and examine it, then take a look at the index.html and main.js files in your editor.

- [_] Declare a variable named `colors` and assign it an array with the following literal string elements: `"white", "hotpink", "lightgreen", "deepskyblue", "coral"`

- [_] Declare a variable named `colorIndex` and assign it the number `0`

- [_] Read about the `Math.random` method to understand what it does and how to call it  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

- [_] Read about the `Math.floor` method to understand what it does and how to call it  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor

* [_] Define a function named `randomizePageBackgroundColor`.

* [_] Inside the function's code block do the following:

  - [_] Declare a variable named `randomIndex`

  - [_] Define a do...while loop and inside it's code block do the following:

    - [_] Generate a random number from 0 to the number of items in the color array and assign it to `randomIndex`.

    - [_] Add the while condition, which should check if the value of `randomIndex` is the same as the value of `colorIndex` and if so continue to run the loop until they are different. This prevents getting a duplicate color when the user clicks the button.

  - [_] After the do...while loop, set `colorIndex` to the same value as `randomIndex`

  - [_] Set the page's background color to the color that is stored in the `colors` array, using the current index number stored in the `colorIndex` variable.

* [_] Outside of your function, at the end of the script file, declare a new variable named `colorButton` and assign it a reference to the button that is on the page.

* [_] Add an event listener to `colorButton`. It should listen for `click` events and execute the `randomizePageBackgroundColor` function when a click event occurs.

* [_] Refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console. When the button on the page is pressed it should swap the background color between the two colors defined in the JavaScript.

# Dive Deeper

Listed below are items for further exploration.

- [_] Read through the Math.random documentation comletely, there are good examples of various common ways this method is used  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

- [_] Read about the `Math` object and the various methods it makes available  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math
