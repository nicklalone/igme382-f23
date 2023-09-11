---------------- Table of Contents ---------------- 

1. [Concepts to Date](#midterm)
2. [Concepts for This Week](#thisweek)
3. [Day 1](#day1)
	1. [We Finally Get Started](#getstart)
		1. [Introducing ArcGIS Pro](#intro)
		2. [UI Tutorial](#UItut)
		3. [Let's Explore Wellington](#welling)
		4. [How does it all work?](#howwork)
4. [Day 2](#day2)
	1. [Let's Think About Rochester](#rochome)
		1. [Getting Started](#getstart)
		2. [What features do we want to highlight?](#highlight)
		3. [Doing it](#doing)

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
# <a id = "today"></a>Concepts for This Week 
* Types of Layers
	* **Thematic** - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map
	* **Coropelth** - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* **Proportional Symbol** - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable
	* **Dot Density** - https://www.axismaps.com/guide/dot-density
	* **Isarithmic (heat)** - http://wiki.gis.com/wiki/index.php/Isarithmic_map
* **Map Scale** - https://education.nationalgeographic.org/resource/map-scale/
* **Map Projections** - https://www.gislounge.com/map-projection/
* **Generalization** - https://support.esri.com/en-us/gis-dictionary/generalization

# <a id="day1"></a>Tuesday 
## <a id ="getstart"></a>We Finally Get Started
So for the past couple of weeks, we've been stuck in a bit of a torpor. I didn't have permissions to show GIS in class unless I brought a windows machine to class. This led to a week of delaying new instruction. Now, I have the permissions for us to really begin running. 

What I thought i'd do this week is relatively simple: 

1. Introduce Map Concepts
2. Introduce the ArcGIS UI
3. Prompt everyone to explore with an assignment. 

So on Tuesday, we will explore GIS, on Thursday, we'll get ready for an assignment. 

### New Concepts

**Data**
* **Data Model** - https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* **Data Structure** - https://support.esri.com/en-us/gis-dictionary/data-structure

**Types of Data**
* **Raster** - https://www.caliper.com/glossary/what-is-raster-data.htm
* **Vector** - https://www.caliper.com/glossary/what-is-vector-data.ht

Concepts About the Makeup of Maps:
* **Map Scale** - https://education.nationalgeographic.org/resource/map-scale/
* **Map Projections** - https://www.gislounge.com/map-projection/
* **Generalization** - https://support.esri.com/en-us/gis-dictionary/generalization

**Layers**: 
* **Types of Layers**
	* **Thematic** - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map
	* **Coropelth** - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* **Proportional Symbol** - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable
	* **Dot Density** - https://www.axismaps.com/guide/dot-density
	* **Isarithmic (heat)** - http://wiki.gis.com/wiki/index.php/Isarithmic_map

### <a id ="intro"></a>Introducing ArcGIS Pro
If the stuff we talk about in class doesn't work for you, give this tutorial a shot: 
* Part 1: https://www.youtube.com/watch?v=BbUctneHfKc&t=1558s&ab_channel=GeoDeltaLabs
* Part 2: https://www.youtube.com/watch?v=t7ZnT5NgqlM&ab_channel=GeoDeltaLabs

I also like this collection from RIT's own Brian Tomaszewski: 
* https://www.youtube.com/watch?v=zrFm5HzwPNw&list=PLtrmEEvdGsNqsQ5ZpOapSmVQklIG9Bu5W&ab_channel=GIScience

### <a id ="uitut"></a>UI Tutorial
Ribbons
![[/images/whole.png]]
Ribbons
Map Explorer
Database Editor
Python Editor / Jupyter Notebook
Table of Contents

![[/images/map.png]]
Navigate
Layer
Selection
Inquiry
Labeling
Offline

![[/images/analysis.png]]
Geoprocessing
Tools
Portal
Workflows
Raster

![[/images/edit.png]]
Clipboard
Manage Edits
Snapping
Selection
Tools
Elevation
Corrections
Data Reviewer

![[/images/help.png]]
Customize
Help
Performance
Contact Us

![[/images/imagery.png]]
Ortho Mapping
Alignment
Analysis
Image Classification
Mensuration
Tools
Share
Motion Imagery

![[/images/insert.png]]
Project
Layer Templates
Link Analysis
Measurements
Styles
Favorites

![[/images/share.png]]
Package
Share As
Status
Manage
Save As
Output

![[/images/view.png]]
View
Link
Windows
Thumbnail
Accessibility
Annotation
Device Location
Scene
View Clipping
Navigation

### <a id ="welling"></a>Let's Explore Wellington
You can find the data for this here: 

### <a id ="howwork"></a>How does it all work?
Types of datafiles
Difference between online vs pro

# <a id="day2"></a>Thursday 

## We Apply What We Got Started


### <a id ="rochome"></a>Let's Think About Rochester (or your hometown)


### <a id ="getstart"></a>Getting Started


### <a id ="highlight"></a>What features do we want to highlight?


### <a id ="doing"></a>Doing it

