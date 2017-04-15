# Tutorial from W3Schools

* [Intro to SVG](href: https://www.w3schools.com/graphics/svg_intro.asp)



## What is SVG?

SVG stands for Scalable Vector Graphics
SVG is used to define vector-based graphics for the Web
SVG defines the graphics in XML format
SVG graphics do NOT lose any quality if they are zoomed or resized
Every element and every attribute in SVG files can be animated
SVG is a W3C recommendation
SVG integrates with other W3C standards such as the DOM and XSL



## SVG Advantages

Advantages of using SVG over other image formats (like JPEG and GIF) are:

SVG images can be created and edited with any text editor
SVG images can be searched, indexed, scripted, and compressed
SVG images are scalable
SVG images can be printed with high quality at any resolution
SVG images are zoomable (and the image can be zoomed without degradation)
SVG is an open standard
SVG files are pure XML
The main competitor to SVG is Flash.


The biggest advantage SVG has over Flash is the compliance with other standards (e.g. XSL and the DOM). Flash relies on proprietary technology that is not open source.



## Creating SVG Images

SVG images can be created with any text editor, but it is often more convenient to create SVG images with a drawing program, like [Inkscape](https://inkscape.org/en/).



## SVG Code explanation

An SVG image begins with an <svg> element
The width and height attributes of the <svg> element define the width and height of the SVG image
The <circle> element is used to draw a circle
The cx and cy attributes define the x and y coordinates of the center of the circle. If cx and cy are omitted, the circle's center is set to (0, 0)
The r attribute defines the radius of the circle
The stroke and stroke-width attributes control how the outline of a shape appears. We set the outline of the circle to a 4px green "border"
The fill attribute refers to the color inside the circle. We set the fill color to yellow
The closing </svg> tag closes the SVG image
Note: Since SVG is written in XML, all elements must be properly closed!








