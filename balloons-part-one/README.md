# Hello World DOM Revisited Project

# Objectives

- [_] Open the page in your web browser and see what happens, then take a look at the index.html, main.css, and main.js file in your editor.

- [_] Get a reference to the element that has an id of `"balloons"` and assign it to a variable named `balloons`

- [_] Go read about the `ParentNode.firstElementChild` property to understand what it does and how to use it  
  https://developer.mozilla.org/en-US/docs/Web/API/ParentNode/firstElementChild

- [_] Use the `firstElementChild` property of `balloons` to get a reference to its first child element and assign it to a variable named `balloon`.

- [_] Use the `style` property of `balloon` (as done in previous projects) to set a style property. Change the background color of the element to `red`.

- [_] When finished with the above, refresh the page to make see your changes and make sure there are no errors in the Developer Tools Console.

- [_] Note that using `style` is a convenient way to set one style property, but it is not the best way to manage styles. The "separation of concerns" principle dictates that our page markup should be in its own HTML file, our page styles should be in their own CSS file, and our page logic/functionality should be in a separate Script file.

- [_] Go read about the `Element.classList` property to understand what it does and how to use it  
  https://developer.mozilla.org/en-US/docs/Web/API/Element/classList

- [_] Use the `classList.remove` method of `balloon` to remove the "deflate" class that is currently on that element.

- [_] When finished with the above, refresh the page to make see your changes and make sure there are no errors in the Developer Tools Console.

- [_] Go read about the `toggle` method to understand what it does and how to use it  
   https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/toggle

- [_] Create a function named `toggleBalloonInflation`. The function should toggle the class named `over-inflate` on the element stored in the `balloon` variable.

- [_] Refresh the page in the browser and open the Developer Tools console and manually call the `toggleBalloonInflation` function a few times.

- [_] Add a `click` event handler (as done in previous projects) on the window object and attach the `toggleBalloonInflation` function to it.

- [_] When finished with the above, refresh the page to make see your changes and make sure there are no errors in the Developer Tools Console.

- [_] Notice that when we click in the page only one balloon is affected. What if you want to click on a specific balloon and only have the click event fire for that balloon, how would you do that?

- [_] Go read about the `Event` interface to understand what it is  
  https://developer.mozilla.org/en-US/docs/Web/API/Event

- [_] Modify the `toggleBalloonInflation` function to accept one argument named `event` and add a statement to log the event variable contents to the console.

- [_] When finished with the above, refresh the page to make see your changes and make sure there are no errors in the Developer Tools Console. Examine the event object that was logged.

- [_] Go read about the `Event.target` property to understand what it is  
  https://developer.mozilla.org/en-US/docs/Web/API/Event/target

- [_] Modify the `toggleBalloonInflation` function so that instead of using the `balloon` variable it now should use the target of the event passed in as the first argument to toggle the class.

- [_] When finished with the above, refresh the page to make see your changes and make sure there are no errors in the Developer Tools Console. Now when either balloon is clicked the class toggle should only happen on the one clicked.

# Dive Deeper

Listed below are items for further exploration.

- [_] If you haven't clicked through to the documentation of the `add` and `remove` methods availalbe on via the `classList` property be sure to visit the documentation on those methods and read through it for a complete understanding of what you can do with these methods.  
  https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/add
  https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/remove

- [_] The `classList` property returns a `DOMTokenList` object. Read more about the properties and methods available via this object.  
  https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList

- [_] Take a deeper dive into events by going through the "Introduction to Events" guide on MDN:  
  https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events
