# Tutorial from W3Schools

* [feoffset filter](https://www.w3schools.com/graphics/svg_feoffset.asp)




## SVG Drop Shadows - <defs> and <filter>

All internet SVG filters are defined within a `<defs>` element. The `<defs>` element is short for definitions and contains definition of special elements (such as filters).

The `<filter>` element is used to define an SVG filter. The `<filter>` element has a required id attribute which identifies the filter. The graphic then points to the filter to use.




## Example 1: SVG fliter - <feOffset>

Code explanation:


* The id attribute of the `<filter>` element defines a unique name for the filter
* The filter attribute of the `<rect>` element links the element to the "f1" filter




## Example 2: SVG fliter - <feOffset>

Code explanation:


* The stdDeviation attribute of the `<feGaussianBlur>` element defines the amount of the blur




## Example 3: SVG fliter - <feOffset>

Code explanation:


* The in attribute of the `<feOffset>` element is changed to "SourceAlpha" which uses the Alpha channel for the blur instead of the entire RGBA pixel




## Example 4: SVG fliter - <feOffset>

Code explanation:


* The `<feColorMatrix>` filter is used to transform the colors in the offset image closer to black. The three values of '0.2' in the matrix all get multiplied by the red, green and blue channels. Reducing their values brings the colors closer to black (black is 0)





