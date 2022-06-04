# Mapping Earthquakes

## Overview
The purpose of this project was to extract GeoJSON data from the U.S. Geological Survey (USGS) and create interactive maps of earthquake and tectonic plate location of earthquake all over the globe.  

## Results
Using JSON, I was able to create three interactive map layers and plotted the earthquake and tectonic plate data.  The earthquakes are marked by circles, and the size of the circles are related to the magnitude of that particular earthquake.  The three map layers are derived from Mapbox API's.  In the upper right corner of the map, the user can select which layer he/she would like to view, and can even toggle through the data he/she would like to see plotted.  In the lower right corner of the map, the user can see a legend to more easily identify the magnitude of the earthquake.  Lastly, a marker will appear on the map any time a user clicks on an earthquake circle.  This marker displays the location and magnitude of the selected earthquake.  

### Streets View
<img width="1292" alt="Screen Shot 2022-06-03 at 2 45 17 PM" src="https://user-images.githubusercontent.com/99417460/171971471-9885a23e-e999-4915-a830-03d0a8d749c6.png">
This map layer is derived from the Mapbox Streets API.

### Satellite View
<img width="1439" alt="Screen Shot 2022-06-03 at 2 46 14 PM" src="https://user-images.githubusercontent.com/99417460/171971536-cdd757b3-d089-420a-a369-dbfb24ad4c44.png">
This map layer is derived from the Mapbox Sattelite-Streets API.

### Night View
<img width="1440" alt="Screen Shot 2022-06-03 at 2 46 29 PM" src="https://user-images.githubusercontent.com/99417460/171971558-1c0f4b7c-65cf-4451-8a36-6c55cdb5807d.png">
This map layer is derived from the Mapbox Navigation-Night API.

## Summary
In conclusion, this project has a map with three separate layers the user can select.  The user is able to toggle the desired information he/she wishes to view from, whether that be earthquakes, tectonic plates, or major earthquakes, or any variance of the three.  

