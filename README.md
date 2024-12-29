# CSS Pseudo-element Content Issue Within Media Queries

This repository demonstrates a common CSS bug related to using pseudo-elements (:before, :after) within media queries. The issue arises when the `content` property of the pseudo-element is not correctly defined or is missing within the media query itself.

## Bug Description
The provided CSS code snippet uses a pseudo-element (:before) within a media query. However, when the media query condition is met, the pseudo-element does not display because the `content` property is either missing or incorrectly defined within the media query's scope.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.css` and `bugSolution.css` to observe the difference.
3. View the HTML file with a browser that supports responsive design.
4. Resize the browser window to trigger the media query to see the effect.