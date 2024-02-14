# state_map
This script creates a state map of the US using Python and GeoPandas. 
Two states, Alaska and Hawaii have been removed from the map.

Requires shape file. Though it looks like we are using only the .shp file, all files need to be loaded as GeoPandas takes information from all files.

Change the path for the Shape file if you plan to use this code.

The script plots a full map and adds another layer of visited states above it.
The states of choice can be saved in a list and those states can be plotted as required. 
Here, I have plotted the states I have visited in different years. 
