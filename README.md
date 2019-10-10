# Atlan-Data-Science-Intern-Task
![Screenshot 2019-10-10 at 5 35 23 PM](https://user-images.githubusercontent.com/27502430/66567257-7012c700-eb84-11e9-8eb4-a2c6291f7370.png)

Atlan | Data Science Intern Challenge

Aim: Identify commercial centers using Points of Interest (POI) data

There's a lot of open data available about the demographics and geography of the planet. But this information is not necessarily supervised in any particular structure from which insights can be drawn.

This task requires you to create clusters of distinct commercial centers or markets using points of interest data of a city (the city could be yours). Points of interest (POI) data provides location information of different places along with their defining tags like school, type of outlets, type of building, etc.

POI data refers to the coordinates of any physical entity with a tag describing its type like commercial buildings, schools, hospitals, restaurants, etc.
 
Objective:

Get Points of Interest from open data sources like open street maps (OSM).
Understand how spatial location data works
Understand spatial vector data types and how to manipulate it using your language of choice.
Understand necessary GIS concepts like projections, spatial clustering, etc.
Figure out a way of clustering these points into commercial centers/markets. You can use standard size polygons also to cluster the points.
Find and label the most significant clusters, statistically and intuitively. 
Visualize the resultant commercial centres/markets. 

Data Source:

POI (OSM) data- https://www.openstreetmap.org/#map=11/28.6518/77.2219
You can use overpy (a python frontend for overpass API of OSM) to get OSM data for the desired city.

(Tip: you can use overpass-turbo to frame queries)

Submissions:

Point or polygon file with commercial centers/markets in ESRI shapefile. 
Documentation around the methodology, analysis, and final results that you want to share. Do use graphs and charts to substantiate your analysis. (Bonus points if you use GitHub pages / RPubs / etc. to share your documentation)
Script(s) and their documentation. (Bonus points for using Jupyter Notebook or GitHub ReadMe.)
Visualizations. (Bonus points if you use interactive dashboards)

## Data Collection
Location for differnt zone were collected. Plese refer to the initial section of Final_submission jupyter notebook for more detials.

## K Means
In order to cluster different data points according to thier lables, K means was used.
