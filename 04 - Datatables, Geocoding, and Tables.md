---------------- Table of Contents ---------------- 

1. [Concepts to Date](#midterm)
2. [Concepts for This Week](#thisweek)
3. [Day 1](#day1)
	2. [Class Features](#classfeatures)
		* [Points](#points)
		* [Line](#lines)
		* [Polygons](#polygons)
		* [Data Tables](#datatab)
		* [Joins](#joins)
4. [Assignment 2](#two)

---------------- Table of Contents ---------------- 
# <a id="midterm"></a>Concepts to Date
* **Raster** - https://www.caliper.com/glossary/what-is-raster-data.htm
* **Vector** - https://www.caliper.com/glossary/what-is-vector-data.htm
	* **Discussion of Both**: 
		* https://www.gislounge.com/geodatabases-explored-vector-and-raster-data/
		* https://gisgeography.com/spatial-data-types-vector-raster/
		* https://www.esri.com/content/dam/esrisites/en-us/media/pdf/teach-with-gis/raster-faster.pdf
		* https://gis.stackexchange.com/questions/57142/what-is-the-difference-between-vector-and-raster-data-models
		* https://id.land/blog/raster-vs-vector-data-the-ultimate-guide
		* https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* **Scale** - https://www.caliper.com/glossary/what-is-a-map-scale.htm
* Data Model - https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* Data Structure - https://support.esri.com/en-us/gis-dictionary/data-structure
* Cartesian Coordinate Systems - 
	* https://www.andrews.edu/~rwright/Precalculus-RLW/Text/01-01.html#:~:text=The%20Cartesian%20%2C%20or%20rectangular%20%2C%20coordinate,as%20(x%2C%20y)
	* https://support.esri.com/en-us/gis-dictionary/cartesian-coordinate-system#:~:text=%5Bcoordinate%20systems%5D%20A%20two%2D,by%20an%20x%2Cy%20coordinate
* Types of Layers
	* Thematic Layer - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map#:~:text=Isarithmic%20maps%2C%20also%20known%20as,of%20values%20of%20the%20field.
	* Coropelth - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* Proportional Symbol - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable.
	* Dot Density - https://www.axismaps.com/guide/dot-density
	* Isarithmic (heat) - http://wiki.gis.com/wiki/index.php/Isarithmic_map
* Shapefiles
# <a id = "today"></a>Concepts for This Week 
* Feature Classes
* Types of Feature Classes
* Data Table
# <a id="day1"></a>Tuesday 
## <a id ="classfeatures"></a>Feature Classes
From [here](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/overview/feature-class-basics.htm), we see that Feature Classes are: 
	Feature classes are homogeneous collections of common features, each having the same spatial representation—such as points, lines, or polygons—and a common set of attribute columns, for example, a line feature class for representing road centerlines. The four most commonly used feature classes are points, lines, polygons, and annotation (a term for map text).
So basically, we have a basemap which is a raster-based (mostly) file that is created through imaging tools like satellites, cars driving around, airplanes, drones, and just folks walking around. If we want to construct something from that raster layer that isn't obvious, like a point of interest, we have to add it ourselves. 

Generally, this is done by adding a vector layer to a map. In this course, we will be talking a bit about 3 specific Feature Classes: points, lines, and polygons. 

To add a feature class to a map, do the following (additionally, i thought [this tutorial](https://pro.arcgis.com/en/pro-app/latest/get-started/create-points-on-a-map.htm) was a bit too fast but also a bit more useful than anything else I could find): 
0. Start a new project with the map template.
1. Go to the "Catalog" which is on the right of the default layout: 
   ![](/images/whole.png)
2. Right click on the databases and find the .gdb file. 
3. Click on, "Feature Class"
4. 

For the following items, we'll be referencing: [this tutorial](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/overview/feature-class-basics.htm) and it has more on it than what i'm placing here. We'll circle back around as we get further in. 
### <a id ="points"></a>Points
- Points—Features that are too small to represent as lines or polygons as well as point locations (such as GPS observations).
### <a id ="line"></a>Line
- Lines—Represent the shape and location of geographic objects, such as street centerlines and streams, too narrow to depict as areas. Lines are also used to represent features that have length but no area, such as contour lines and boundaries.
### <a id ="polygons"></a>Polygons
- Polygons—A set of many-sided area features that represents the shape and location of homogeneous feature types such as states, counties, parcels, soil types, and land-use zones.
### <a id ="datatab"></a>Data Tables


## <a id = "geocaching"></a>Geocaching

## <a id ="two"></a>Thursday and Assignment 2
### Parameters of the Assignment:
1. Download the Geocaching App:
	1. https://www.geocaching.com/play/mobile
	2. SET UP ACCOUNT
		1. DO NOT PAY FOR IT
2. Find 5 Geocaches on RIT Campus
	1. Get their coordinates
	2. Convert them to decimal by dividing by 60 or going to: https://www.geocachingtoolbox.com/index.php?lang=en&page=coordinateNotation&status=result
	3. Take a selfie at the site.
3. Put the data into GIS.
	* Create a feature layer in the DB of a project file. 
	* Plot each point on a baselayer of your choosing. 
	* Plot a Polygon in a separate feature layer.
4. Produce a report with the following: 
	1. Page 1 has: 
		1. Geocache names and Coordinates
		2. Map of points with labels without a polygon.
		3. Map with a polygon instead of points. 
	2. Pages 2-6 has:
		1. Geocache Name Plus Coordinates
		2.  Map of Point with label
		3. Selfie Image
5. Send to PDF.
6. Designated Course Rep submits PDF by Sunday Night.