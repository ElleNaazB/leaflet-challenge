## This project maps earthquake data using modern web technologies. Here are the steps involved:

1. Obtains the dataset:

Accesses earthquake data provided by the USGS, which is available in various formats and updated every 5 minutes. By visiting the USGS GeoJSON Feed page and selecting a dataset such as "All Earthquakes from the Past 7 Days," a JSON representation of the data is obtained. The URL of this JSON is then used for visualization.

2. Imports and visualizes the data using Leaflet:

Utilizes the Leaflet JavaScript library to create an interactive map that displays all the earthquakes from the selected dataset according to their longitude and latitude.
Configures data markers on the map to reflect the magnitude of the earthquake by their size and the depth of the earthquake by their color. Larger markers denote higher magnitudes, and darker colors indicate greater depths.
Includes popups on each marker to provide additional information about the earthquake when clicked.
Adds a legend to the map to provide context for the data displayed, explaining the significance of the marker sizes and colors.
This approach leverages the capabilities of Leaflet to offer a dynamic and informative visualization of seismic activities, enhancing the understanding of earthquake distribution and intensity over a given period.
