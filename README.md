# Mapping_Earthquakes
## Overview 
In this project,  We are helping Basil and sadhana create a geographical map with GeoJSON earthquake data from a URL. We will use the Leaflet.js Application Programming Interface (API) Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter. Each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

In addition, we will see the earthquake data in relation to the tectonic plates’ location on the earth.
Our project consists of three technical analysis deliverables. You will submit the following:

### Deliverable 1: Add Tectonic Plate Data

1- We will add a second layer group variable for the tectonic plate data.

2- In Step 2, we will add a reference to the tectonic plate data to the overlay object.

3- In Step 3, using d3.json() callback method, we will make a call to the tectonic plate data using the GeoJSON/PB2002_boundaries.json data from this GitHub repository (Links to an external site.) for the tectonic plate data.

4- Inside the d3.json() method do the following:
o We will pass the tectonic plate data to the geoJSON() layer.
o Then we will style the lines with a color and weight that will make it stand out on all maps.

5- We will add the tectonic layer group variable you created in Step 1 to the map

6- Next, we will add the tectonic layer group variable to the map.

![Map_majorEarthquake](https://user-images.githubusercontent.com/103543959/189176608-33592b30-2675-4d69-ac55-743a71a79ec2.png)


### Deliverable 2: Add Major Earthquake Data

1- We will add the major earthquake data as a third layer group.

2- We will add the major earthquake data to the overlay object.

3- We will set the color and diameter of each earthquake.

4- The major earthquake data is passed to the geoJSON() layer.

![tectonic_map](https://user-images.githubusercontent.com/103543959/189176560-49483916-dd9c-48a3-8454-b0325f81c707.png)


### Deliverable 3: Add an Additional Map

1-	We will first create a third map tile layer(Dark).

2-	We will add the third map to the overlay object

![Dark_map](https://user-images.githubusercontent.com/103543959/189176243-ad611ef3-72da-4355-9da8-844e8d284b42.png)
