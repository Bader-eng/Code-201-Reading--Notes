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

4. Drawing a bar chart:
