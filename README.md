Scatta
==========

This reusable, flexible D3 plot template can be pasted into your HTML and modified as needed. I use it for several data visualization projects, e.g. [this one](http://nikhil-nathwani.com/viz/roi/roi.html).

##How it looks by default
Below you'll see how this template looks without any additional customization. The next section explains how you may easily customize the formatting and look of it. 

![scattaDefault](http://i.imgur.com/ZyvpsNR.png)

##How to customize the template
Catering this template to your specific needs is simple. It is controlled by just 5 sets of variables assigned at the start of the script tag in "scatta.html":

1) **Overall graph size** can be adjusted by modifying the "w" and "h" variables.

2) **Axis formatting** is accomplished by specifying the leftmost and rightmost values on the axis ("x0" and "xN" for the x-axis, "y0" and "yN" for the y-axis), and where in the graph the axes should be drawn ("xAxisLoc" and "yAxisLoc").

3) **Tick marks** are controlled by the "tX" (for the x-axis) and "tY" (for the y-axis) parameters, respectively.

4) **Graph/axis titles** are specificed by the "graphTitleText", "xAxisLabelText", and "yAxisLabelText" variables.

5) **Padding between titles and the graph** is controlled by the "padding" parameter.

And of course, various style attributes can be adjusted by tinkering with the "scatta.css" file.
