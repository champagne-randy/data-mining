# Tutorial from W3Schools

* [feGaussianBlur filter](https://www.w3schools.com/graphics/svg_fegaussianblur.asp)




## SVG Blur Effets - <defs> and <filter>

All internet SVG filters are defined within a `<defs>` element. The `<defs>` element is short for definitions and contains definition of special elements (such as filters).

The `<filter>` element is used to define an SVG filter. The `<filter>` element has a required id attribute which identifies the filter. The graphic then points to the filter to use.




## Example 1: SVG fliter - <feGaussianBlur>

Code explanation:

* The id attribute of the `<filter>` element defines a unique name for the filter
* The blur effect is defined with the `<feGaussianBlur>` element
* The in="SourceGraphic" part defines that the effect is created for the entire element
* The stdDeviation attribute defines the amount of the blur
* The filter attribute of the `<rect>` element links the element to the "f1" filter





