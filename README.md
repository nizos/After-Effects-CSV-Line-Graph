# After Effects CSV Line Graph

## Features

* Uses data from CSV file.
* Renders up to 3 series per graph.
* Up to 200 data points per series.
* Easy slider controls for:
  * Graph: size & position.
  * Animation: start & end time.
  * Callouts: Number of callouts to show, callout color, opacity, size & position.
  * Gridline: Number of gridlines to show, gridline width, color & opacity.
  * Axis labels: Number of labels to show, interval, color & opacity.
  * Series line: Line width, color, opacity, animation start & end time.
  * Axis: Start & end values for X & Y Axis.

## Screenshot

![alt text](https://github.com/nizos/After-Effects-CSV-Line-Graph/blob/master/Screenshot/Line%20Graph%20Screenshot.png "Screenshot of an example line graph using the project")

Render example:
https://youtu.be/knmlqEKm7m0

## Troubleshooting

### CSV data changes not showing

This might be due to the original csv data being already imported. To correct this, do the following:  

1. Download a new copy of the project.
2. Replace the CSV file before opening the project.
3. Open the project and start the render.

If this does not solve the problem for you, try the following:

* Make sure that the first line in the CSV file contains the column names (Time, Value).
* Try using the same time format used in the original CSV files.
* Open a new issue and I will have a look at it.
