A class in more advanced topics of GIS using [QGIS](http://www.qgis.org/). 

Slides are available [here](http://www.datapolitan.com/DOT_GIS/20160610_Intermediate_GIS/#1).

## Goals
<!--![img](images/goals_outcomes.jpg)-->
+ Review basic geospatial and cartographic concepts
+ Further develop the ability of students to think spatially
+ Demonstrate and apply methods for processing geospatial data within a GIS
+ Understand the structure and use of relational databases for spatial analysis
+ Introduce best practices in acquiring, cleaning, and visualizing spatial data

## Outcomes
+ Participants will understand the fundamentals of creating more accurate and visually compelling maps
+ Participants will better understand the spatial data processing, analysis, and visualization workflow in QGIS
+ Participants will be able to connect to a spatial database (PostGIS) using QGIS
+ Participants will be practiced in composing SQL statements to perform basic geoprocessing tasks


## Outline for the Class

+ Introductions
+ Review of basic concepts
	+ What is geographic data
	+ What is GIS
+ Practical Exercise 1
	+ Open a basemap in QGIS
	+ Import a shapefile in QGIS
	+ Import CSV data to QGIS
	+ Review projections
	+ Basic styling in QGIS
+ Introduction to spatial databases
	+ When have you used a spatial database?
	+ What is a spatial database? (like a shared file server)
	+ A quick and simple introduction to the relational model 
	+ Sharing data with datbases
	+ Introduction to schemas (as relate to datatypes in SHP)
	+ Performance benefits of databases
+ Practical Exercise 2 (connecting to a database and manipulating data in QGIS)
	+ Connect to a PostGIS database
	+ Selecting data in QGIS (injuries in a particular boro)
	+ Export selected features as shapefile
+ Practical Exercise 3 (bicycle injuries in NYC)
	+ Buffering features
	+ SRID map units
	+ Reprojecting data in QGIS
	+ Select by location (intersection of buffered injury points with bike lanes)
	+ Spatial joins (count of injuries by community district within boro)
	+ More advanced styling in QGIS (style result by number of injuries)
	+ Calculating fields and normalizing results
+ Introduction to SQL
	+ A basic introduction to SQL
	+ Select query for features in single table
	+ Introduction to PostGIS and spatial SQL
	+ Introduction to PostGIS functions
+ Practical Exercise 4 (basic spatial SQL functions)
	+ Union features in database
	+ Spatial join (count injuries by boro)
	+ `GROUP BY` features spatially (injuries by community district)
+ Practical Exercise 5 (Putting it all together)
	+ Working with 311 Service Requests for DOT, filter results by boro, join complaints by community district, create and style a choropleth map in Print Composer
	+ Create a kernal density map in Print Composer
	+ Present maps to the class
+ Wrap-up
	+ Discussion of data formats
	+ Introduce PostGIS documentation and other resources
	+ Quick demonstration of model builder in QGIS
	+ Discuss geocoding of addresses in QGIS
+ Q & A/Evaluations
+ Dismissal

<!--![img](images/outline_2.jpg)-->

