# Mapping workshop for the Monitor
August 2, 2017

## Before and after images

1. Open up [JuxtaposeJS](https://juxtapose.knightlab.com), an easy-to-use tool built by Northwestern's Knight Lab. We'll be using two screenshots of maps created for the Urban Institute's [Our Changing City: Housing](http://apps.urban.org/features/OurChangingCity/housing/index.html) project about Washington, D.C. 

2. Click "Make a slider now."

3. In left image, paste in this url: http://www.storybench.org/nieman/ui2003.png

4. In right image, paste in this url: http://www.storybench.org/nieman/ui2013.png

5. Delete Apr. 2005 and Nov. 2013 labels.

6. Click "Update preview."

![Alt text](http://www.storybench.org/nieman/ui2013web.jpg)

## Introduction to mapping

Using [Google My Maps](https://www.google.com/mymaps), we’ll quickly map some addresses and then plot "shapefiles" of water parks in Boston.

### Mapping points

7. Download point data of TKTKTKT [here](). 

8. Import this [CSV]() into [Google My Maps](https://www.google.com/mymaps). 

9. Style the points by selecting "uniform" and then customize their icon and color.

#### *What is this data?*

(This is pulled from **City of Boston's Analyze Boston data portal** found at [https://data.boston.gov/dataset/tot-sprays](https://data.boston.gov/dataset/tot-sprays). 

311 service complaints data, by the way, is a huge list, with everything from rodent complaints to noise complaints to illegally parked cars. 

So, we will filter it down [here](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data) in the Filter tab by **complaint type: lead, status: open, created date: after 2.1.2017.** Then we'll download a CSV in the Export tab.)

### Mapping buildings/shapes

10. Find Boston water playgrounds through the City of Boston's Analyze Boston [data portal](https://data.boston.gov/dataset/tot-sprays).

11. Import the [KML file](http://bostonopendata-boston.opendata.arcgis.com/datasets/5409b7735d384798b2a360aa47c9b128_0.kml) into [Google My Maps](https://www.google.com/mymaps). 

12. Style the public housing buildings by "borough."

13. Set labels as “development.”

#### *What is this data?*

(This is pulled from **City of Boston's Analyze Boston data portal** found at [https://data.boston.gov/dataset/tot-sprays](https://data.boston.gov/dataset/tot-sprays). 

Download the KML file.

(KML is essentially a list of shapefiles. Shapefiles are polygons – or, more specifically, a list of coordinates outlining a polygon. A triangle has three coordinates. A square has four. A state like Colorado will have fewer than Rhode Island.) 



