# AnalyseEarthquake

The USGS earthquake data is retreived from in JSON format from the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). 
The data on tectonic plates are from <https://github.com/fraxen/tectonicplates>.


Thie script will do the following:

- Create a map using Leaflet that plots all of the earthquakes and tectonic plates based on their longitude and latitude.
- The markers will reflect the magnitude of the earthquake in their size and colour. Earthquakes with higher magnitudes should appear larger and darker in colour.
- Include popups that provide additional information about the earthquake when a marker is clicked.
- Create a legend that will provide context for your map data.
- Illustrate the relationship between tectonic plates and seismic activity
- Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.
- Add layer controls to our map.
