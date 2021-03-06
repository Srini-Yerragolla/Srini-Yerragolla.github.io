# srini.github.io
This is my first project for my H517 Data Visualization class at IUPUI. 
Please see the visualization here: https://srini-yerragolla.github.io/

Introduction
In 1854, a cholera outbreak swept over the Soho district in London. The outbreak reached its peak on the first week with more than 150 deaths, causing widespread panic in the neighborhood which lead to the flight of its residents. At that time, the cause of cholera was not scientifically established, and people believed that toxic vapors resulting from the decay of organic matters was the cause of cholera, among other diseases. Dr. John Snow (1813 - 1858) was skeptical of this theory. To investigate other causes, Snow made his famous map of the Soho district, plotting the location of deaths alongside street water pumps in the neighborhood. At that time, the data acquisition and visualization tools at Snow's disposal were severely limited by today’s standards. Nevertheless, Snow's visualization was arguably the first clear evidence that linked cholera transmission to contaminated water supply.

This project is aims to create an interactive version of Dr. Snow's visualization. The data used here comes from Snow's original map and data.

Design

The visualization is divided into two parts. The left side shows a map of the Soho district in London, plotting the location of deaths, as well the location of street water pumps. The right side of the visualization shows the graph with total number of deaths per day, the male/female victims, and the victims of various age groups. 
The map
The map occupies the left side of the visualization. It plots the location of deaths along with the location of street pumps. The user can zoom in/out of the map using the mouseover.

Icons:
The icon for a victim is a circle by color for a female magenta and male blue. A circle is significantly different in terms of visual features from a triangle. Thus, it should be easy for the analyst to distinguish between a male and a female victim, or to conduct a quick visual search based on gender. Pumps are depicted with red circle, workhouse in yellow and brewery in brown color.

The color of a victim's icon is used to represent the age of the victim. The color scale goes as follows:
 
Graphs:
The graph is rendered on the right side of the visualization.

The graphs are rendered on the right side of the visualization.
Setup (For local viewing open in Chrome browser)  http://127.0.0.1:888ll or 
GitHub Server- open in Google Chrome browser https://srini-yerragolla.github.io/

Project1 References:
https://en.wikipedia.org/wiki/1854_Broad_Street_cholera_outbreak#
https://d3js.org/








