# CSO_Mapping
CSO Mapping in Kenya
https://geopsy.github.io/CSO_Mapping/
Is a map of Children Services Providers in Kenya

#Code Documentation
We used HTML, CSS and JavaScript
We added the basemap as Leaflet css files, while point and polygon data was added as js files.
The counties shapefile contained county name, Population, Covid 19 cases, and covid cases per 100000 persons.
Safe shelter, which are points contained the sheleter name, geographic location, director and contacts.
Both shapefiles were converted to GeoJson file format before they were passed as variables.
Next the center and zoom level were set.
In order to symbolize the levels differently we defined a function to get color depending on number of covid cases, after which we specified the legend and features to appear on the legend.
Next we defined a js function to read the GeoJson files passed earlier on as variables
We added a container to control all layers.
Legend placement was set using css
Finally we set a div element to style the map.
