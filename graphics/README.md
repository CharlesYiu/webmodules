# linesForHtml
simple script for drawing lines on html webpages
# Documentation
## shapify(element)
element: the element to store the lines
returns a shape class
## shape.refresh()
redraws shape
## shape.toggleDebug()
toggles debug
## shape.x
x position of the shape (the anchor of the shape is 0, 0)
## shape.y
y position of the shape (the anchor of the shape is 0, 0)
## shape.lineWidth
width of the line
## shape.lineColor
color of the line
## shape.appendLine(name, a, b)
name: the name of the line
a: the x and y of point a ({'x': x, 'y': y})
b: the x and y of point b ({'x': x, 'y': y})
## shape.removeLine(name)
name: the name of the line
removes the line
