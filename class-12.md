# create stunning animated  
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
They’re easier to look at and convey data quickly, but they’re not always easy to create.
 ## Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 
## The <canvas> element
At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes.
The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content,
to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. 
fillStyle = color
Sets the style used when filling shapes.
strokeStyle = color
Sets the style for shapes' outlines.
*The canvas rendering context provides two methods to render text:*
fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
