# Color Flip Project

# Objectives

- [_] Open the page in your web browser and examine it, then take a look at the index.html and main.js files in your editor.

- [_] Declare a variable named `firstColor` and assign it the literal string `"#00ffab"`

- [_] Declare a variable named `secondColor` and assign it the literal string `"#ffc500"`

- [_] Declare a variable named `useFirstColor` and assign it the boolean value `true`

- [_] Go read about the `document.body` property to understand what it is
  https://developer.mozilla.org/en-US/docs/Web/API/Document/body

- [_] Go read about the `style` property to understand what it is and check the examples to see how to set a specific style
  https://developer.mozilla.org/en-US/docs/Web/API/ElementCSSInlineStyle/style

- [_] Use the `document.body.style` property to change the background color to any color you'd like; you may want to consult the list of properties available to find the property name you need:  
  https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference

  You may also want to reference the list of colors found on this page:
  https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

- [_] When finished with the above, refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console.

- [_] Add an if statement that will check the value of `useFirstColor` and if true set the page's background color to the color value stored in `firstColor`, otherwise set the background color to the color value stored in `secondColor`.

  This if statement should replace your line that changed the background color to the color of your choosing in the previous objective.

- [_] Refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console. The page background color should be set to `#00ffab` (a mint green-ish color).

- [_] Modify the `useFirstColor` assignment, setting it to `false`. Refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console. The page background color should be set to `#ffc500` (a yellowish-orange color).

- [_] Define a function named `swapPageBackgroundColor`.

- [_] Move your if statement inside the function's code block.

- [_] Add another if statement above the current one inside the function's code block. This if statement should check the value of `useFirstColor` and if it is `true` set `useFirstColor` to `false`; otherwise it should set `useFirstColor` to `true`. This will essentially toggle the value of `useFirstColor` between `true` and `false` every time the function is called.

- [_] Outside of your function, at the end of the script file, declare a new variable named `colorButton` and assign it a reference to the button that is on the page.

- [_] Go read about the `addEventListener` method to get an idea of what it is and how to use it
  https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener

- [_] Use add an event listener to `colorButton`. It should listen for `click` events and execute the `swapPageBackgroundColor` function when a click event occurs.

- [_] Refresh the page to make sure your changes work without throwing any errors in the Developer Tools Console. When the button on the page is pressed it should swap the background color between the two colors defined in the JavaScript.

# Dive Deeper

Listed below are items for further exploration.

- [_] Don't worry to much right now if the documentation for addEventListener doesn't make too much sense. It will make more sense as continue to learn about objects and events. You should have a basic sense for what it does though.

- [_] Take a look at the other event types you can use as the first parameter passed to `addEventListener`  
  https://developer.mozilla.org/en-US/docs/Web/Events
