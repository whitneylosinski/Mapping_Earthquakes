# Mapping Earthquakes

<hr>

<strong>Deployed Project URL:  </strong> https://whitneylosinski.github.io/Mapping_Earthquakes/
<hr>

### Project Purpose
The purpose of this project was to create an interactive geopraphical map from GeoJSON data, showing the locations and magnitudes of all earthquakes occuring over the past 7 days along with the outer boundaries of the tectonic plates.  The goal was to visually illustrate the relationship between frequency, magnitude and location of seismic activity near major fault lines.

The project showcases how to use API requests to get geographical maps, how to retrieve and plot GeoJSON data using d3.json, and how to use the Leaflet JavaScript library to create layers and overlays on the map.

### Project Resources
Data: </br>
- All earthquakes in past 7 days: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson </br>
- Major earthquakes in past 7 days: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson </br>
- Tectonic Plate coordinates: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json </br>
- Map styles: Mapbox API

Tools: JavaScript ES6, HTML/CSS, D3.js, Leaflet

## Project Steps
1. Make API requests to the mapbox server to host the different map styles.
2. Create the map object with the appropriate zoom and center location defined.
3. Create the base layer of the map which holds the other map layers.
4. Add map layers and overlays for Earthquakes, Major Earthquakes and Tectonic Plates using the Leaflet JavaScript library.
5. Add a control for the user to select which map layers are visible.
6. Retrieve the earthquake GeoJSON data for all earthquakes in the past 7 days using d3.json().
7. Style the data markers so they are circles with the size and color of the marker being relational to the magnitude of the earthquake.
8. Add a Popup for each data point displaying the earthquake magnitude and location.
9. Create the Earthquakes GeoJSON layer to plot the retrieved data and add the layer to the map.
10. Retrieve the major earthquake GeoJSON data using d3.json().
11. Style the data markers so they are circles with the size and color of the marker being relational to the magnitude of the earthquake.
12. Add a Popup for each data point displaying the earthquake magnitude and location.
13. Create the Major Earthquakes GeoJSON layer to plot the retrieved data and add the layer to the map.
14. Add a legend to the map to let the user know what the colors of the markers indicate.
15. Retrieve the tectonic plate GeoJSON data using d3.json().
16. Create the Tectonic Plates GeoJSON layer to plot the retrieved data and add the layer to the map.

### Project Results

