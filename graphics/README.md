# Using scripts
```Html
<script src="https://raw.githubusercontent.com/charlesyiu/webmodules/main/graphics/[filename]"></script>
```
(Remember to change "[filename]" to the filename of the script)
# Documentation
## [lines.js](https://github.com/charlesyiu/webmodules/blob/main/graphics/lines.js)
#### shapify(element)
element: the element to store the lines
returns a shape class
### shape
#### x
x position of the shape (the anchor of the shape is 0, 0)
#### y
y position of the shape (the anchor of the shape is 0, 0)
#### lineWidth
width of the line
#### lineColor
color of the line
#### appendLine(name, a, b)
name: the name of the line
a: the x and y of point a ({'x': x, 'y': y})
b: the x and y of point b ({'x': x, 'y': y})
#### removeLine(name)
name: the name of the line
removes the line
#### refresh()
redraws shape
#### toggleDebug()
toggles debug
