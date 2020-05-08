- Choropleth Maps display divided geographical areas or regions that are coloured, shaded or patterned in relation to a data variable. 
- This is an interactive global choropleth map on Share of Adults who are obese (1975–2016) using Python libraries and package — Pandas, Geopandas and Bokeh.  
-  Natural Earth https://www.naturalearthdata.com/ is a public domain map dataset that provides geospatial data at various resolutions.
- To render a world map the shapefile with world coordinates was downloaded from https://www.naturalearthdata.com/downloads/110m-cultural-vectors/ by clicking on the 
green button 'Download Countries v4.1.0'  
- Data was downloaded from https://ourworldindata.org/   

- Geopandas can read almost any vector-based spatial data format including ESRI shapefile using read_file command which returns a GeoDataframe object.  
- In order to incorporate data visualization interactivity, we will use Bokeh library. 
Bokeh consumes GeoJSON format which represents geographical features with JSON. 
GeoJSON describes points, lines and polygons (called Patches in Bokeh) as a collection of features.
