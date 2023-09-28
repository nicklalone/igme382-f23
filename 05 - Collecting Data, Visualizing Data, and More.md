---------------- Table of Contents ---------------- 

1. [Outline and Intent for this week](#outline)
2. [Day 1 - Tuesday](#day1)
	* [Feature Classes](#feature)
	* [Reference Map](#ref)
	* [Thematic Map](#theme)
	* [Map Design](#mapd)
1. [Day 2 - Thursday](#day2)
	* [Assignment 3](#ass3)
		* [Case Studies](#cs)
		* [Emerging Topics](#et)
		* [Thematic Maps](#tm)
	* [How to do all that...](#howto)
	* [Other tutorials](#others)

---------------- Table of Contents ---------------- 
# <a id = "outline"></a>Outline
Over the past few weeks, we've been sort of skirting in and around GIS, mapping technologies, and really the entirety of the course as I do all of the work I wasn't allowed to do in preparation for the course. This week marks the start of 2 things: 
1. Getting this course to where it needs to be. 
2. Getting y'all into geospatial technologies. 
So what does that mean?
Well, first, we're going to have what should be a heavy week in comparison to this course thus far. Second, this week is what this course will feel like moving forward. 

The goals of this week are relatively simple: 
1. Learn what the variety of specific applications GIS can be used for.
2. How to get that data that GIS uses...
3. Find out how to use the layout tools of ArcGIS Pro to build maps than can be exported from ArcGIS Pro.
4. Show me you can apply cartographic concepts such as visual variables and statistical display strategies to map production.

# <a id="day1"></a>Tuesday - What Kinds of Data, How do We Get it? How do we apply it?
Today, we're just going to go through some background terms and ideas. To wit, the terms we're worried about are these: 
1. Shapefiles: 

These are a collection of files that contain what we can refer to as spatial datasets or vector-based information. This is something of a legacy format but given its uses, will probably be around for quite some time. As-is, these predate geodatabse files which has all of the data tables, curves, raster files, and annotations you've made on a map. 

Because they've been around for forever and because there is no alternative, they are still widely used. As noted these files ONLY contain vector data, no curves. There are a number of different pieces to this 2GB limited file type. These include:

 * Shapefiles
	* filename.shp - containing the coordinates
	* filename.dbf - containing the attributes
	* filename.shx - containing linkages, other info
	* filename.prj - optional, containing projection information
	* filename.sbn - an optional indexing file 
  
3. Geodatabases:
A number of years ago, ESRI created the Geodatabase. This filetype is exactly what it sounds like, it is a collection of data with regard to a project or map. These database files contain: tables, shapefiles, rasters, annotations, and the true curves of rasters. Unlike the 2GB limit for shapefiles, there is a 2 TB limit not for the database itself, but per feature class. Also, unlike shapefiles, Enterprise geodatabases have no limits but they must be created in ArcGIS. This is a lot like how PDFs used to be before Adobe made that format less proprietary. 

So PER feature class, we added a feature class in class last week. So, we only added a few points; however, we can add as much information as we'd like to these, as long as it falls under a couple terrabytes. We can visualize this information a bit more: 

4. Feature Classes <a id="feature"></a>/ Databases:
![[/images/pi2.png]]

Now, we're going to talk a bit about 2 different kinds of maps: reference and thematic.

6. Reference Map<a id="ref"></a>:
These maps are just for reference. We used to use these all the time. Road maps, maps that show us where cities are, where forests or parks might be. We use these to figure out what human things are around us be they trees, parks, roads, paths, buildings, and more. 

8. Thematic Map<a id="tm"></a>:
Remember the pandemic? We'll be dealing with the after effects of it for ages in as much as we're still dealing with the after effects of 9/11/2001. Thematic maps were omnipresent during the pandemic. You saw them all the time. For example: https://hub.jhu.edu/magazine/2020/summer/coronavirus-tracker-map-lauren-gardner/

We can also think about stuff like temperature maps or anything where data about something residing somewhere can be visualized through some schema. 

10. Map Design: 
We will talk about this on Thursday but I wanted to mention gestalt theory as well as the work in and around road signs and cartographic signs.
### <a id="mapd"></a>Map Design
Gestalt Theory, it's back...or it's new!
# <a id="day2"></a>Thursday - Getting to know geospatial data queries
### <a id="ass3"></a>Assignment 3:
3 Tasks: 
1. Task 1 – Find and discuss a GIS case study.
2. Task 2 – Explore an emerging topic in GIS.
3. Task 3 – Build a Thematic Map

So let's go through some stuff. 
### <a id="cs"></a>Case Studies!
### <a id="et"></a>Emerging Topics!
### <a id="tm"></a>Thematic Maps!

### <a id="others"></a>How to do all that
Open up GIS, let's see what's inside...

### <a id=""></a>Tutorials and additional content: 
* ArcGIS Pro Select By Attribute - [YouTube](https://www.youtube.com/watch?v=2sH3K_neshc)
* Labeling Features - https://support.esri.com/en-us/knowledge-base/how-to-label-selected-features-in-arcgis-pro-000019992
* Navigation and Feature Selection - https://esribelux.com/2020/03/16/easier-navigation-and-feature-identification-in-arcgis-pro/
* [Selecting by Attributes and Location in ArcGIS Pro](https://learninglink.oup.com/protected/files/content/file/588a0d47d911611300e523ec-1485442397769-CH7---Selecting-Features-ArcGIS-Pro.pdf)
* https://hackernoon.com/arcgis-pro-vs-arcmap-why-you-should-move-to-arcgis-pro
* [ArcMap vs ArcGIS Pro - Comparing these two GIS applications from Esri](https://www.youtube.com/watch?v=4_OOOQbLZDU&ab_channel=eGISAssociates)
* 