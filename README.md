# Delhi-Restaurant-Route-Optimization

This project demonstrates route optimization for last-mile delivery using Python and Kepler.gl. It is a practice project that showcases how to efficiently plan delivery routes using geospatial data. The project utilizes a self-made CSV file containing restaurant data in Delhi.

name,address,latitude,longitude
Restaurant A,Address A,28.590664,77.070819
Restaurant B,Address B,28.591582,77.071500
...



Key Features
Data Preparation: Loads restaurant data from a CSV file and converts it into a GeoDataFrame.
Route Calculation: Uses the OSRM API to calculate the optimal route between restaurants.
Visualization: Visualizes routes and restaurant locations using Kepler.gl, providing an interactive map for better insights.
Requirements
Python 3.x
Pandas
GeoPandas
Shapely
Leafmap
Polyline
Requests
Kepler.gl
