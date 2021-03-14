# Chart.js:
* A great way to get started with charts is with Chart.js, a JavaScript plugin 
that uses HTML5’s canvas element to draw the graph onto the page.

1. Setting up:
* The first thing we need to do is download Chart.js. Copy the Chart.min.js out of 
the unzipped folder and into the directory you’ll be working in.

2. Drawing a line chart:
* To draw a line chart, the first thing we need to do is create 
a canvas element in our HTML in which Chart.js can draw our chart
* Next, we need to write a script that will retrieve the context of the canvas
* Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of 
our chart and datasets to describe the values on the chart. 

3. Drawing a pie chart:
* first, we need the canvas element.
* we need to get the context and to instantiate the chart
* Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler,
we just need to supply a value and a color for each section.

4. Drawing a bar chart.
 ## canvas:
* At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

## Fallback content:
* The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

## Required canvas tag :
As a consequence of the way fallback is provided, unlike the <img> element, the <canvas> element requires the closing tag (</canvas>). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

## The rendering context:
The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts,
  which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering
  context. Other contexts may provide different types of 
  rendering; for example, WebGL uses a 3D context based on OpenGL ES.
