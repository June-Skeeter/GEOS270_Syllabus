---
layout: default
title: Helpful Data Sources
parent: Final Projects
nav_order: 1
---

# Helpful Data Sources

Here are are a few place you can look for data.  There are plenty other out there, if you search google.

1. TOC
{:toc}

## Simply Analytics

With [Simply Analytics](https://resources.library.ubc.ca/page.php?id=1044), you can download Cenus Data for Canada **and/or** the United States.  You can also download buissines locations.

## Google Earth Engine

[Google Earth Engine](https://developers.google.com/earth-engine/datasets/) has lots of datasets, we've only covered two; using Landsat8 to calculate NDVI and and working with DEMs (see code below).  If you'd like to work with something we haven't worked with I'm happy to help facilitate downloading it, just send me an email.  *Do not wait until the last minute* to contact me asking for help with a download.
* This code can be used to download a DEM from google earth, similar to what we did in [Module 2](https://june-skeeter.github.io/Module2_GEOS270/docs/Application_Part2.html#calculating-ndvi-with-google-earth-engine), just make sure to upload an appropriate boundary file first.

```javascript
var dataset = ee.ImageCollection('NRCan/CDEM').mean();
var elevation = dataset.select('elevation');
var elevationVis = {
  min: -50.0,
  max: 1500.0,
  palette: ['0905ff', 'ffefc4', 'ffffff'],
};


Map.centerObject(Boundary)
Map.addLayer(Boundary)
Map.addLayer(elevation, elevationVis, 'Elevation');

// Export to Google drive
Export.image.toDrive({
  image: elevation,
  description: 'DEM',
  scale: 25,
  region: Boundary
});
````

## Data BC

[Data BC](https://data.gov.bc.ca/) has many different datasetes.  You can search for them by key terms.  Some useful data sets might include:

* Old Growth Forests *- legal - current*
* Freshwater Atlas Stream Network
* Freshwater Atlas Rivers
* Freshwater Atlas Coastlines
* BC Wildfire Fire Centres
* Fire Burn Severity - Historical



* Some downloads from this site require you to filter by [Map sheets](https://open.canada.ca/data/en/dataset/055919c2-101e-4329-bfd7-1d0c333c0e62)

## Municipal Data Sources

The [City of Vancouver Data Portal](https://opendata.vancouver.ca/pages/home/) has a lots of data for the city: parks, zoning, bike lanes, transit etc.  Only for the **City** Vancouver.  [Surrey](https://www.surrey.ca/services-payments/online-services/open-data), [Richmond](https://www.richmond.ca/discover/maps.htm), [Burnaby](https://www.burnaby.ca/services-and-payments/maps-and-open-data), etc. have their own.  [Metro-Vancouver](http://www.metrovancouver.org/data#k=), which is inclusive of all thse cities has more data.  Most large municipalities have some sort of data portal.
* eg.  Google: "Toronto open data" and see what comes up.
