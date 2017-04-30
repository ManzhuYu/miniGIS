# MiniGIS
MiniGIS is a tiny GIS software package developed using python. In the folder, *.py files are the Python files and *.pyc files are the compiled python files. 
The ‘sample-data’ folder contains several shape file data folders; the ‘cities’ folder, which contains world city data; ‘countries,’ which contains world country data; the ‘Fairfax’ folder contains schools, highways, major utility lines and regions in Fairfax; and the ‘multi-parts-polyline’ folder contains two polylines with multi parts. 
The ReadShapeFile module reads different types of features, or layers, which include Points, Polylines, and Polygons. The Commons module provides common reusable functions.
The Dialogs Module provides the two dialogs to select layers.
The Events module provides mouse operated events handling.
Mini-GIS module includes the main function. A directory becomes a Python package if it contains __init__.py. It includes the following functions:
1.	The main functions for calling other parts
2.	Generate a window
3.	Input the datasets
4.	Visualize the data
5.	Show the window
Normally, this is the only part you need to understand fully if you get the package from elsewhere; otherwise, the interface description is enough to use a package. 
# Usage:
We can run the package in the following workflow: 
1)	Add the path to the sys path; or just double click the MiniGIS.py; or use IDLE to run the package. Here, use the third method to open MiniGIS.py.
2)	Click Run->Run module menu or the ‘F5’ button to run the package. It will bring up a window which has the title ‘MiniGIS.’ 
3)	Import shapefile in two ways: ‘Import shp’ and ‘Add shp layer’ in the File menu. 
4)	View the map using the menu under ‘View’ menu: zoom in, zoom out, zoom to extent, zoom to full window and close layer. 
Mini-GIS also supports drawing features of different types: point, polyline, circle and polygon. To draw a feature, click on ‘Edit’ to bring up a dialog box and select a layer. However, the current MiniGIS doesn’t support exporting these added features to the Shapefile.
The Mini-GIS can also calculate the intersections between two polyline layers.
