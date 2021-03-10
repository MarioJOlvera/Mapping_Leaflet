# Mapping with Leaflet

## Resume

<img src="Images/1-Logo.png"> 

The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

Getting our data set from the USGS GeoJSON Feed page:

<img src="Images/3-Data.png">

The data obtained will be in JSON format. As i.e.: 

<img src="Images/4-JSON.png">

Then, a map will be created using Leaflet that plots all of the earthquakes from our data set based on their longitude and latitude: 

- Our data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.
- Include popups that provide additional information about the earthquake when a marker is clicked.

<img src="Images/2-BasicMap.png">

Plotting a second data set on our map to illustrate the relationship between tectonic plates and seismic activity. We will need to pull in a second data set and visualize it along side our original set of data. (Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.)

<img src="Images/5-Advanced.png">
