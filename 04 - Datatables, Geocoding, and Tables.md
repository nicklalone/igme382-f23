---------------- Table of Contents ---------------- 

1. [Concepts to Date](#midterm)
2. [Concepts for This Week](#thisweek)
3. [Day 1](#day1)
	2. [Class Features](#classfeatures)
		1. [Points](#points)
		2. [Line](#lines)
		3. [Polygons](#polygons)
		4. [Data Tables](#datatab)
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
* Database Files (GDB) - 
# <a id = "today"></a>Concepts for This Week 
* Geodatabases - 
* Feature Classes - 
	* Types of Feature Classes - 
		* Line - 
		* Point - 
		* Polygon - 
* Data Table - 
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
2. Click on the databases and find the .gdb file within. You'll be right clicking on it but let's unpack this a bit first. 
   
   What the gdb file is is essentially a database of things relevant to your project. Those things are objects like system tables but also the data your map contains. This includes but is not limited to: Feature classes and datasets, mosaic data, raster data, and various tables.
   
   They can also do things like store geometric networks as well as network maps, various kinds of parcel fabrics (think video game skins...kinda, but they're poly's for rendering 3D), terrains, topologies, and various kinds of networks. 
   
   Now that we've started this, let's dig a bit in. 
 ![](/images/04/1.PNG) 
3. Click on, "Feature Class" and we're going to be going through a wizard that will help us start the feature class. And you might wonder, what is a feature class? Well, it's basically you setting up an object.
 
![](/images/04/2.PNG)

4. This is the wizard. It should be relatively straight forward, I hope?! Let's walk through it a bit. First things first, let's get a look at the what the wizard wants (it's the one ring, it's always the one ring).

![](/images/04/3.PNG)
5. So, with naming schemas for variables, i'm sure you've been told a lot during your programming courses. This is no different. If you've not taken any programming courses, know this: there are limits to names, especially as we get into projects with hundreds, if not thousands of feature classes. We'll have a whole week or so on data management though so that's something to look forward to!
   
   So, with, "Feature Class Type" this is where the big guns come out. What are you making? Do you make a polygon to represent builtings? Do you make a dot because the object is too small? What? Well, in this case we're just going to place a few points here and there. 

![](/images/04/4.PNG)
6. Here, we'll be working in and around what amounts to a data table. I want you to do 2 things here: 1. Change OBJECT ID to Name and 2. Add a field called, "LatLong." After this, you can hit next and explore the rest of it, but we'll just be doing defaults. 

![](/images/04/5.PNG)
7. Alright! We made our first feature class. As you can see, I am an adult who names things how they should be named. What i'd suggest is to use what the feature class will be showing as the name. So like, for the assignment, we might consider something like, "Geocaches". But there's some fun to do here. 
   
   Go to the "Edit" tab in the Ribbon. 

![](/images/04/6.PNG)
8. So we have a feature class which created a table for us to flesh out...but we don't have any objects! So, the table is empty. If we add some things to the table, nothing really happens. But if we click on this, "Create" button, what happens? What's that on the side?

![](/images/04/7.PNG)

9. We got a whole thing here. Let's take a closer look: 

![](8.png.md)

So what's happening here? Well, it's relatively simpker

For the following items, we'll be referencing: [this tutorial](https://pro.arcgis.com/en/pro-app/latest/help/data/geodatabases/overview/feature-class-basics.htm) and it has more on it than what i'm placing here. We'll circle back around as we get further in. 

One thing for your professor to recommend is about shape files. The format is weird because it stores geometry and that's it. It's kind of an unnecessary thing given that the geodatabase already stores enough for that; however, it still needs to draw the vector data. So, most likely we won't have a way away from it. This is a long, ranty webpage but it's informative: http://switchfromshapefile.org/
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