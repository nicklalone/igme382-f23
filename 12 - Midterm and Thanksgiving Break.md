---------------- Table of Contents ---------------- 

1. [Week 03](#w3)
2. [Week 04](#w4)
3. [Week 05](#w5)
4. [Week 06](#w6)
5. [Week 07](#w7)
6. [Week 08](#w8)
7. [Week 09](#w9)
8. [Week 10](#w10)

---------------- Table of Contents ---------------- 
## <a id="w3"></a>Week 03 - Using GIS 
**Data**
* **Data Model** - https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* **Data Structure** - https://support.esri.com/en-us/gis-dictionary/data-structure

**Types of Data**
* **Raster** - https://www.caliper.com/glossary/what-is-raster-data.htm
* **Vector** - https://www.caliper.com/glossary/what-is-vector-data.ht

**Concepts About the Makeup of Maps**
* **Map Scale** - https://education.nationalgeographic.org/resource/map-scale/
* **Map Projections** - https://www.gislounge.com/map-projection/
* **Generalization** - https://support.esri.com/en-us/gis-dictionary/generalization

**Layers** 
* **Types of Layers**
	* **Thematic** - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map
	* **Coropelth** - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* **Proportional Symbol** - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable
	* **Dot Density** - https://www.axismaps.com/guide/dot-density
	* **Isarithmic (heat)** - http://wiki.gis.com/wiki/index.php/Isarithmic_map
## <a id="w4"></a>Week 04 - Datatables and Coding
* Geodatabases - 
* Feature Classes - 
	* Types of Feature Classes - 
		* Line - 
		* Point - 
		* Polygon - 

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
## <a id="w6"></a>Week 06 - Storymaps
1. At least 10 locations (on a map of some kind) with images that either you own, or are creative commons.
2. A timeline with pictures of said highlights.
3. At least 3 text blocks.
4. What your favorite part of the trip was. 
5. What you learned from the trip and why.
6. Where you will go next and why.
## <a id="w7"></a>Week 07 - Remote Sensing
Please organize yourselves so you can answer these questions: 

1. What is remote sensing?  
    “Remote sensing is the process of detecting and monitoring the physical characteristics of an area by measuring its reflected and emitted radiation at a distance”      

2. Please cite 5 pieces detailing what remote sensing is.  
    Please include: 2 Web Resources, 2 academic resources (peer reviewed), and 1 Youtube video.

* The process of detecting and monitoring the physical characteristics of an area by measuring its reflected and emitted radiation at a distance (What is remote sensing and what is it used for?, [usgs.gov](https://www.usgs.gov/faqs/what-remote-sensing-and-what-it-used))
  
* “Remote sensing is the acquiring of information from a distance.” (What is Remote Sensing?, [nasa.gov](https://www.earthdata.nasa.gov/learn/backgrounders/remote-sensing))
  
* Cracknell, A. P. (2007). Introduction to Remote Sensing. CRC press.

* Khorram, S., Koch, F. H., Van der Wiele, C. F., & Nelson, S. A. (2012). Remote Sensing. Springer Science & Business Media.
    
* What is Remote Sensing?: [https://www.youtube.com/watch?v=xIsUP1Ds5Pg](https://www.youtube.com/watch?v=xIsUP1Ds5Pg)
  
3. What is Active remote sensing?

Active Remote Sensing is when a remote sensor uses its own method of energy/radiation to help map out and analyze regions.  
  
4. Please cite 5 pieces detailing what Active remote sensing is.  Please include: 2 Web Resources, 2 academic resources (peer reviewed), and 1 Youtube video.

* Active Remote Sensing([Active Remote Sensing - an overview | ScienceDirect Topics](https://www.sciencedirect.com/topics/earth-and-planetary-sciences/active-remote-sensing#:~:text=Important%20Terms-,Active%20remote%20sensing,in%20this%20case%20nonfire%20area)).) 
* Passive vs Active Sensors in Remote Sensing ([URL](https://gisgeography.com/passive-active-sensors-remote-sensing/))    
* Kairu, E. N. (1982). An introduction to remote sensing. GeoJournal, 251-260.
* Andersen, H. E., Reutebuch, S. E., & McGaughey, R. J. (2006). Active remote sensing. In Computer Applications in Sustainable Forest Management: Including Perspectives on Collaboration and Integration (pp. 19). Dordrecht: Springer Netherlands. [URL](https://link.springer.com/content/pdf/10.1007/978-1-4020-4387-1_3.pdf)
* Canada Centre for Remote Sensing. "Fundamentals of Remote Sensing." Natural Resources Canada, Year of Publication, ([URL](https://natural-resources.canada.ca/sites/www.nrcan.gc.ca/files/earthsciences/pdf/resource/tutor/fundam/pdf/fundamentals_e.pdf.)) 

5. What is Passive remote sensing?
“Passive sensors detect energy emitted or reflected from an object, and include different types of radiometers and spectrometers. Most passive systems used in remote sensing applications operate in the visible, infrared, thermal infrared, and microwave portions of the electromagnetic spectrum.”

6. Please cite 5 pieces detailing what Passive remote sensing is. Please include: 2 Web Resources, 2 academic resources (peer reviewed), and 1 Youtube video.  

* Passive Sensors, NASA Earthdata: [https://www.earthdata.nasa.gov/learn/backgrounders/passive-sensors](https://www.earthdata.nasa.gov/learn/backgrounders/passive-sensors)

* Passive vs active sensors in remote sensing:
[https://gisgeography.com/passive-active-sensors-remote-sensing/](https://gisgeography.com/passive-active-sensors-remote-sensing/)

* What is Active and Passive Remote Sensing? [youtube](https://www.youtube.com/watch?v=vzfGMMEEz5w&ab_channel=GeospatialWorld)

* Navalgund, Ranganath & V, Jayaraman & Roy, Parth. (2007). Remote sensing applications: An overview. Current science. Vol. 93. [https://www.researchgate.net/publication/255616101_Remote_sensing_applications_An_overview](https://www.researchgate.net/publication/255616101_Remote_sensing_applications_An_overview)

* Louw, A. S., Fu, J., Raut, A., Zulhilmi, A., Yao, S., McAlinn, M., Fujikawa, A., Siddique, M. T., Wang, X., Yu, X., Mandvikar, K., & Avtar, R. (2022). The role of remote sensing during a global disaster: COVID-19 pandemic as case study. Remote sensing applications : society and environment, 27, 100789. [https://doi.org/10.1016/j.rsase.2022.100789](https://doi.org/10.1016/j.rsase.2022.100789)
    
7. What kind of data does remote sensing include?
* [https://youtu.be/vzfGMMEEz5w?si=oWCvm4YWbhrHtPY8](https://youtu.be/vzfGMMEEz5w?si=oWCvm4YWbhrHtPY8)Spectral data collected from satellites, aircraft, and handheld sensors
    

* Radar, sonar, lidar, and echo-sounder methods collect reflected wavelengths that are usually displayed in % reflectance in relation to micrometers (µm) 
*  ![](https://lh6.googleusercontent.com/m208JxP_4fJ66m1bkCHWO5YpIVo4QtANNE9xfqXE4aRebTk9YX9zulnhThkbDdZPjhi9AEs_KmugLYy8KSxIgZKIn2qib8RDwiEuJJA8qIPdJXfiqdq_EJ2RJgrIv1bWdzsBXFWdYGX-hS6nxUn-Yfo)

* The bands of wavelengths collected depend on the collection method, but usually include shorter wavelength Ultra-Violet (UV) to longer wavelength Near InfraRed (NIR) and Thermal InfraRed (TIR)
 ![](https://lh3.googleusercontent.com/yCeLHy_8AoMfeIejCHB2TddV4MwbenpC-9mjAtHelY0KVuA-fSSINuQ7p7vU-c-ka3aLzRKOdWp5D69XS00gtdIy6E5O1tDY-6Vt-qj0NocROZ7hcnwR1uqbmQY_pCTyXSK2p9ZU_9sh-GYSQKdGTUY)
Other forms of collected data come from photography, push broom sensors (device for obtaining images with [spectroscopic](https://en.wikipedia.org/wiki/Electromagnetic_spectrum) sensors), and scanning mirrors

Mårtensson, Ulrik. (2011). “Introduction to Remote Sensing and Geographical Information Systems”. Department of Physical Geography and Ecosystems Sciences. (pp. 5-8). [https://www.nateko.lu.se/sites/nateko.lu.se.sv/files/remote_sensing_and_gis_20111212.pdf](https://www.nateko.lu.se/sites/nateko.lu.se.sv/files/remote_sensing_and_gis_20111212.pdf)

“Ge111A Remote Sensing and GIS Lecture”. Caltech. (pp.4-12). [https://web.gps.caltech.edu/classes/ge111/Docs/ge111_GIS_rev.pdf](https://web.gps.caltech.edu/classes/ge111/Docs/ge111_GIS_rev.pdf)    


8. In what circumstances are feet a remote sensor?
 In an earthquake, when the floor is wet, detecting temperature changes, finding where the floor is(uneven surface)

9. If I were to design a remote sensor for some phenomenon, what would that thing be tasked at sensing?

		Stand name: Wayward Sons
		Appearance: a series of satellites that orbit the user
		Stand abilities: remote sensing
		Wayward sons use remote sensing to determine the exact distance anything is from the user
		Fish finder from space. Who needs the NASA budget anyway. 

10. Why is it needed?
	* To find out where things are without actually going there 
	* Measure/detect over very large surface areas, where manually recording would be impossible.
	 * It provides a global perspective on current natural events happening around the world
	* Surveying large swaths of natural resources at once, monitoring dynamic changes of desertification, flood, drought, and landforms from a distance (satellite images). Veress, Benjamin, and Jozsi Szigethy, editors. Horizons in Earth Science Research. Volume 24. Nova Science Publishers, [2023].
	* It provides a consistent source of data over time allowing for long term monitoring and analysis
	* Cost efficiency through automating data collection

## <a id="w8"></a>Week 08 - Game Cartography

Game Maps - Why are they useful?
Map as Medium
Map as Tool
Dungeons and Dragons
Divergence 
## <a id="w9"></a>Week 09 - Disaster Maps
ESRI's Deal: 
		1. https://www.esri.com/en-us/disaster-response/overview
		
There are a few givens to consider with regard to maps and disaster. We will state these givens now: 

1. We refer to the event that creates the disaster a hazard. These hazards can be natural, manmade, and technological.
2. Disasters begin long before the hazard. 
3. Vulnerability and risk are not equal across the population. 

But what does this have to do with maps? 

1. 3 Kinds of Maps

We can say that there are 3 kinds of maps we have for disaster. Those maps are: 

1. A Map of the Local Area.
City planning is a process that does not check in with emergency management. The reason this matters is that most of your vulnerabilities and weaknesses originate here.

Why?

2. A Map of Risk and Vulnerability.

What is risk?
![](/images/Risk_Index_Calculation.svg)
Does this matter?

Let's talk about the following image: 

![](/images/notnat.jpeg)

What does this mean?

![](/images/nosuchmodel.png)
https://justsolutionscollective.org/calling-it-a-natural-disaster-ignores-whats-really-to-blame/ 

But don't take my word for it.

https://www.undrr.org/news/sendai-framework-6th-anniversary-time-recognize-there-no-such-thing-natural-disaster-were

4. A Map of Disaster Damage in Situ.

## <a id="w10"></a>Week 10 - Ethics and Maps
* redistricting
* gdpr
* surveying
* redlining
* indoor
