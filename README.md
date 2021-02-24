# Airports in the United States

## Description

This interactive web app is a choropleth map based on the number of airports within each state. There are also markers signifiying whether or not each airport is equipped with a control tower. 

## Data Sources and Acknowledgments

The United States geographic data used to create the choropleth map, was acquired from Mike Bostock of D3. The shapefile used to present the airport data was gathered from data.gov. The lab which I refrenced and built this map off of was originally designed in the context of Oregon, and was made available through my enrollment in the GEOG 458 course taught by Bo Zhao in the department of GIS at the University of Washington.

## Libraries and Functions 

Firstly, the base map was added to the map object using the `L.titleLayer` function from the **Leaflet** library within **javaScript**. Then, the **chroma.js** library was used along with the **ColorBrewer** to cholorize the markers that signified the control towers throughout the country. Next, a style class was assigned depending on whether or not the airport has a control tower. Furthermore, the **pointToLayer** function was used to create layers for the GeoJSON points, along with the **style**, **onEachFeature**, **filter**, and **coordsToLatLng** funtions, which were all used to display the respective markers along with popups. 

Secondly, I used the setColor funtion, to colorize the map based on the number of airports within each county.


