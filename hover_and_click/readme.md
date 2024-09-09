# Hover and Click Example

This project demonstrates basic interactivity using HTML, CSS, and jQuery to change the background color of `div` elements when they are hovered over or clicked. It also shows how to attach event handlers in jQuery and use CSS for simple styling.

## Features

1. **Hover Interaction**: When the user hovers over a `div` element, the background color changes to green. When the mouse leaves, the color changes to orange.
2. **Click Interaction**: Clicking on any `div` changes its background color to yellow.
3. **jQuery Integration**: The event handling logic (hover and click) is written using jQuery to simplify DOM manipulation and event binding.

## File Structure

- **index.html**: The main HTML file that contains three `div` elements for demonstration. 
  - Each `div` has initial styles such as width, height, background color, and rounded corners.
  - JavaScript event handlers are defined within this file.

## Code Explanation

1. **HTML**: Basic structure with a `div` for each "Thing" element (e.g., Thing 1, Thing 2, Thing 3). Each `div` will change color based on user interaction.
   
2. **CSS**: Provides styles for the `div` elements, including dimensions, background color, and the `cursor: pointer` property to indicate the element is clickable.

3. **JavaScript (jQuery)**: 
   - **Hover Effect**: Changes the background color to green when the mouse enters the element and to orange when the mouse leaves.
   - **Click Event**: Changes the background color to yellow when clicked.
   - The jQuery code is wrapped in the `$(document).ready()` function to ensure that the DOM is fully loaded before executing any script.

## How to Run

1. Clone or download the repository.
2. Open the `index.html` file in a browser.
3. Interact with the `div` elements by hovering over them or clicking on them to see the background color change.

## Dependencies

- **jQuery v3.5.1**: The code uses jQuery to handle DOM events. The jQuery library is included via CDN in the HTML file.
