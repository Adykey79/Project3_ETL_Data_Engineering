# Project 3 - ETL and Data Engineering
---
**Brief Description**: This project applies basic ETL and Data Engineering principles to perform a cursory stock analysis of a small portfolio of five stocks:
> - *Part 1: Database Design* - ETL workflows are used to ingest the data and tranform it prior to loading into a database (SQLite).
> - *Part 2: Data and Delivery* - The data is read from the database created in the above step and visualized using Pandas Dataframe<br>

**Inputs**: The challenge takes in as input one of the many sample datasets that the [USGS GeoJson Page](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) provides. This is intended to be used as a programatic interface for applications.<br>

**Outputs**: The challenge provides the following outputs as described below:
> - *Earthquake Plot Map*: Using Leaflet, a map that plots all the earthquakes from the sample dataset based on their longitude and latitude.    
> - *Plot Legend*: A legend that provides more context on the above data including the depth and the corresponding color. 
> - *Popups*: Popups that provide additional information about the earthquake when its associated marker is clicked.<br>

**References**:
> - GeoJson Documentation, https://doc.arcgis.com/en/arcgis-online/reference/geojson.htm, accessed April 2024.
> - GeoJson in Leaflet - Custom Features, https://bookdown.org/sammigachuhi/book-leaflet/using-geojson-in-leaflet.html, accessed April 2024.
> - Leaflet JS Reference - Map Events, https://leafletjs.com/reference.html#map-event, accessed April 2024. 
