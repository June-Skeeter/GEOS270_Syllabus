---
layout: default
title: Project Ideas
parent: Final Projects
nav_order: 2
---

# Project Ideas
{: .no_toc }

The ideas listed below are meant as a starting point, you should flush them out and come up with a suitable approach to analyze the problem.  You are also free develop your own project idea.  I suggest you focused on BC/Vancouver just because we are more familiar with local data sources.  You are free to explore other geographical regions as well, but be advised that we may not be able to privide as much assistance with searching for data.


1. TOC
{:toc}


# More in Depth Census Analysis

You can use the concept explored in Module 2 (Access to Green Space/Nature vs. Wealth/Affluence) and/or Module 3 (Location vs. Affordability) as a starting point for a deeper analysis.  Incorporate different variables, look at different scales/resolutions/locations.  Don't repeat the assignments, come up with ways **improve** upon the methods and do a deeper analysis.


# Access to green space and bicycle infrastructure in Vancouver 
 
**Scenario**: Access to green space and bicycle infrastructure is important for quality of life in urban areas, promoting physical and mental health.  Yet, green space and bike infrastructure are often inequitably distributed around cities. Explore the distribution of green space and bicycle infrastructure in Vancouver in relation to wealth, housing density, transit, etc.  Check out the 
City of Vancouver Data Portal for data on parks, bicycle lanes, bike racks, trees, etc. that might be useful.  It could also be helpful to incorporate some census data.	
 
Possible Analysis to consider
* Geocoding (will be introduced in the coming weeks)
* Select by location/attribute
* Buffering to gauge accessibility 
* Intersections to count # bike racks, area of parks, length of bike lanes within census units 


# Possible Locations for a Ski Resort

Define a boundary region and download a DEM & other necessary data.  You can use google earth engine to download a DEM and get some other files from DataBc that might be important to consider (eg. Old Growth Forests)

Possible Analysis to consider   
* Slope, Aspect, & Reclassify
* Weighted Overlay or Raster Calculator
* Proximity Analysis


# Landslides in Burn Zones

Forest fires are also some of the worst natural disasters impacting the province.  Climate change and human activity are changing fire dynamics and leading to costlier fire seasons.  After severe fires, intense precipitation events can trigger landslides.  The burn severity data is available for 2015-2019 for BC.  Select a Fire Center (I suggest not doing Coastal Fire Centre).   Use DEM data (google earth) to calculate slope and combine with burn severity and precipitation (HectaresBC) to create landslide risk classification.  Your selected Fire Center can serve as your boundary file for the DEM download. *This could also be adapted to look at logging instead of fires!*

Possible Analysis to consider   
* Slope & Reclassify
* Weighted Overlay or Raster Calculator
* Proximity Analysis
* Flow Analysis


# Air Quality in BC 

Poor air quality is a significant health risk for vulnerable populations.  Over recent years there have been serious smoke events impacting air quality province wide.  Additionally, traffic and industrial activities exacerbate air quality issues in urban areas.  Use this [air quality data](https://github.com/June-Skeeter/BCAirQuality) to look at how air quality changes across the region annually/seasonlally or investigate some specific event(s) eg. a bad fire season.  Consider incorporating census data to see if there arae significant at risk populations (eg. youth and seniors) in places with air quality?  Note - Look at the data coverage before you decide which scale to analyze census data at.
 
Possible Analysis to consider  
* Import tabular (x,y) data 
* Calculating Fields
* Inverse Distance Weighting
* Zonal statistics 
* Tabular joins
  


# Mapping Police Violence
 
Use a dataset on [police violence](https://police-involved-deaths-ca.github.io/Data/) to map incidents of police violence in a specific region of your choice.  You can choose a province (eg. Saskatchewan), or a specific city (eg. Toronto).  Use census data to complement the analysis.  If you choose this project, you can reach out directly to me for more information on the data and guidance how to approach the analysis.

Possible Analysis to consider 
* Point in Polygon Analysis
* Kernel Density
* Linear Regression
* Data Normalization & Classification