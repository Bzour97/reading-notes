# Chart.js & Canvas

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

To see how to use chart.js we’re going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally we’ll use a bar chart to show profit over the period.

## Setting up
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:

< !DOCTYPE html >

< html lang="en" >
    < head >

        < meta charset="utf-8" / >
        <title>Chart.js demo</title>
        < script src='Chart.min.js' >< /script >
    < /head >
    < body >
    < /body >
< /html >
 
## Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

< canvas id="buyers" width="600" height="400" >< /canvas >

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

< script >
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
< /script >

(We can actually pass some options to the chart via the Line method, but we’re going to stick to the data for now to keep it simple.)

Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’:

var buyerData = {
	labels : ["January","February","March","April","May","June"],

	datasets : [

		{

			fillColor : "rgba(172,194,132,0.4)",

			strokeColor : "#ACC26D",

			pointColor : "#fff",

			pointStrokeColor : "#9DB86D",

			data : [203,156,99,251,305,247]

		}

	]

}

If you test your file in a browser you’ll now see a cool animated line graph.

### For more info [Click here](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) & [Here](https://www.chartjs.org/docs/latest/)

## The < canvas > element

< canvas id="tutorial" width="150" height="150" >< /canvas >

At first sight a < canvas > looks like the < img > element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas > element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

### For more info [Click here](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

## Drawing shapes with canvas

Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.

### For more info [Click here](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

## Applying styles and colors

In the chapter about drawing shapes, we used only the default line and fill styles. Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.

Colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color

Sets the style used when filling shapes.

strokeStyle = color

Sets the style for shapes' outlines.

color is a string representing a CSS < color >, a gradient object, or a pattern 
object. We'll look at gradient and pattern objects later. By default, the stroke 
and fill color are set to black (CSS color value #000000).

### For more info [Click here](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

## Drawing text

After having seen how to apply styles and colors in the previous chapter, we will now have a look at how to draw text onto the canvas.

Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

### For more info [Click here](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)