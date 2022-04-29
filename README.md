# SVG Polyline, Polygon and path elements

## Prerequisites

Understanding that SVG provides a number of elements with which basic shapes can be created and combined.

Including:

- the basic workings of the grid on which the shapes are placed on
- x and y coordinates are used to position an element on the grid
- a stroke is often necessary to display the outlining of a shape
- text can be manipulated the same way other elements can
- realizing SVG can scale without losing quality

## Essentials

- Repository from Github (Classroom) **svg-polyline-polygon-and-path**

## Starting point

Clean HTML and JavaScript file

## Preparation

Trainer:

- Give everyone access tot the repository via GitHub classroom
- Explain what these elements are and what you can do with them

Participant:

- Download repository
- Read README.MD
- Study the text from the provided links below if necessary

## Learning objective

Learning to create custom shapes and curved lines in SVG.

## Description

Polyline, polygon and path elements are used to create custom and more complex shapes in SVG. Polyline and polygon have there specific uses, but path is a powerful allrounder that can draw any of the other shapes and more. This power does come with some added complexity as we will see.

### Polyline

The polyline SVG element is an SVG basic shape that creates straight lines connecting several points. Typically a polyline is used to create open shapes as the last point doesn&#39;t have to be connected to the first point.

### Polygon

A polygon is similar to a polyline, in that it is composed of straight line segments connecting a list of points. For polygons though, the path automatically connects the last point with the first, creating a closed shape.A rectangle is a type of polygon, so a polygon can be used to create a rect element in cases where you need a little more flexibility.

Both polyline and polygon use a _points_ attribute to define the points where the lines need to be drawn to. The points attribute is a list of points, each number separated by a space or comma. Each point must contain two numbers: an x coordinate and a y coordinate.

### Path

The path element is the most powerful element in the SVG library of basic shapes. It can be used to create lines, curves, arcs, and more.Paths create complex shapes by combining multiple straight lines or curved lines.

The shape of a path element is defined by one parameter: _d_. The d attribute contains a series of commands and parameters used by those commands. Each of the commands is instantiated by a specific letter. For instance, the &quot;Move to&quot; command is called with the letter M.

All of the commands also come in two variants. An uppercase letter specifies absolute coordinates on the page, and a lowercase letter specifies relative coordinates (e.g., move 10px up and 7px to the left from the last point).

Coordinates in the d parameter are always _unitless_ and hence in the user coordinate system.

Note: complex figures and drawings are usually not defined manually with path, but rather a design tool like Sketch or Illustrator is used to create the drawing and generate generate the SVG paths.

## Result

After the assignment you will have used and created a graphic(s) and touched on the most basic concepts of SVG. You will understand how polyline, polygon and paths are used to draw custom shapes using points and predefined commands.

## Libraries

None, HTML natively supports SVG

## Materials

- _assignments/car.jpg

## Duration
To be determined

## Links

- [https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic\_Shapes#polyline](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Shapes#polyline)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic\_Shapes#polygon](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Shapes#polygon)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic\_Shapes#path](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Shapes#path)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Paths](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Paths)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-linecap](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-linecap)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-linejoin](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-linejoin)
- [https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/transform](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/transform)

- [https://css-tricks.com/transforms-on-svg-elements/](https://css-tricks.com/transforms-on-svg-elements/)
- [https://www.smashingmagazine.com/2019/05/svg-design-tools-practical-guide/](https://www.smashingmagazine.com/2019/05/svg-design-tools-practical-guide/)