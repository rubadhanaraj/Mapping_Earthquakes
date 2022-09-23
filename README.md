# Mapping_Earthquakes
## Overview
The purpose of this project to create different layers of maps to visualise the earthquake data using Leaflet, an open-source JavaScript library,for mobile-friendly interactive maps and using JavaScript and HTML codes. The objective of this project is to 
* Create a branch from the main branch on GitHub.
* Add, commit, and push data to a GitHub branch.
* Merge a branch with the main branch on GitHub.
* Retrieve data from a GeoJSON file.
* Make API requests to a server to host geographical maps.
* Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
* Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
* Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
* Render maps on a local server.

## Results
1.The earthquake data and tectonic plates data are displayed on the basic map with street and satellite map layers. The tectonic plates data were added to the overlay object with the earthquake data.

![image](https://user-images.githubusercontent.com/108298416/191878046-f1204755-41f1-47e2-bd98-71667dec3436.png)

2.The major earthquake data for the past seven days were added to the map using d3.json(). The color and the radius of the circle markers has been set based on the magnitude of earthquake, and a popup marker for each earthquake that displays the magnitude and location of the earthquake were added using the GeoJSON layer, geoJSON().

![image](https://user-images.githubusercontent.com/108298416/191889851-a0ff8916-c668-40fb-beb5-02ae4ef6ec40.png)

3.Along with the satellite and street maps, a third map style was included in the previous map by adding a new tile layer for dark maps which can be toggled on by users according to their preference.

![image](https://user-images.githubusercontent.com/108298416/191890254-704b3655-47b1-4925-a28f-e1bc53c62631.png)

## Summary
In this project, Leaflet library was used to plot the data on a Mapbox style map through an API request. The interactive maps have been created by adding visualization for different map styles such as, street map, satellite map, dark map, naviagtion day map, navigation night map, etc,. 
* In earthquake data visualisation map, a legend was created based on the magnitude of earthquakes that provides information needed for the colors of the earthquakes to make sense to the viewer without having to click on each marker.

![image](https://user-images.githubusercontent.com/108298416/191891035-5dc15b80-bef6-4d20-a017-f81a1238d7d6.png)

* Overlay buttons were created for the viewers to toggle between different layers of maps.

![image](https://user-images.githubusercontent.com/108298416/191891288-e9b5a42b-9c18-492e-bb31-9b5d79b13af7.png)

