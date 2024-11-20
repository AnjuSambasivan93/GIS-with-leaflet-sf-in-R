<h1> </h1>



<h2>Description</h2>
This project visualizes population data of New Zealand using interactive and static maps. It includes tasks such as creating base maps, adding city markers, generating heatmaps, and building choropleth maps using geospatial and population datasets. The project provides both static and interactive visualizations for better insights into population distribution across territories.

<h2> Language and Tools Used </h2>

#### Language:

- **R**: Used for data manipulation, visualization, and creating interactive maps.
  
#### Libraries:

- **leaflet**: For creating interactive maps.  
- **leaflet.extras**: To enhance leaflet maps with features like heatmaps.  
- **sf**: To work with geospatial data formats such as GeoJSON.  
- **ggplot2**: For creating static maps and advanced visualizations.  
- **plotly**: For converting static ggplot maps into interactive visualizations.  
- **dplyr**: For merging and cleaning datasets.  
- **RColorBrewer**: For color palettes used in visualizations. 

#### Environment:

- RStudio: The project was developed and tested in RStudio for efficient scripting and debugging.
  

  
<h2> Main Functions Used </h2>

- **leaflet()**: For creating base maps.  
- **addTiles()**: Adds map tiles to the leaflet map.  
- **addMarkers()**: Places markers on the map with popups showing population data.  
- **addHeatmap()**: Creates a heatmap for population density visualization.  
- **st_read()**: Reads geospatial data from GeoJSON files.  
- **geom_sf()**: Used in ggplot2 for creating choropleth maps.  
- **left_join()**: Merges geospatial and population datasets.  
- **ggplotly()**: Converts static ggplot maps into interactive visualizations.  
- **ggsave()**: Saves the generated plots to files.  

## Features

- Interactive maps with city markers.  
- Heatmaps visualizing population densities.  
- Advanced choropleth maps using log-transformed population data.  
- Customizable color palettes for enhanced visualization.

 ## Types of Maps Created

This project includes various types of maps to visualize population data in New Zealand:

### 1. Basic Map
- A simple map centered on New Zealand.
- Allows zooming and panning to explore the region.

### 2. Marker Map
- Displays markers for major cities (Auckland, Wellington, Christchurch).
- Includes popups showing the city name and population.

### 3. Heatmap
- Visualizes population density using a heatmap.
- Brighter or more intense colors represent higher populations.

### 4. Black-and-White Map
- A basic map showing New Zealand territories with black borders and a white background.

### 5. Choropleth Map
- A color-coded map showing population data for each territory.
- Different colors represent varying population sizes.

### 6. Advanced Choropleth Map
- An improved version of the choropleth map.
- Uses log-transformed population data for better comparison across regions.
- Includes a gradient color scale and detailed titles.

### 7. Interactive Choropleth Map
- An interactive version of the choropleth map created using `plotly`.
- Users can hover over regions to view population data and zoom or pan for exploration.

These maps offer both static and interactive ways to analyze New Zealand's population distribution.



