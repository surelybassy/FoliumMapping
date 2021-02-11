# Folium Mapping
Project exploring rendering mapping data from UK cinemas

## Outline

Explore interactive mapping techniques with Folium, Python and Dash.


## The Data

Using Python and the Beautiful Soup library, the Data was scraped across multiple page from https://film.list.co.uk/cinemas/ into a Pandas Dataframe and exported to a CSV file.

## Mapping the Data

The data collected was imported into Python and mapped using the Folium library.

Below are several examples of the different settings and options available.

Interactive demos:

[Simple Mapping Example.](https://surelybassy.github.io/FoliumMapping/HTML_Files/map_points.html "Simple Mapping Example")

[Map with colour coded points.](https://surelybassy.github.io/FoliumMapping/HTML_Files/map_points_colours.html "Colour Coded Points")

[Points with pop-ups](https://surelybassy.github.io/FoliumMapping/HTML_Files/map_points_popups.html "Points with pop-ups")

[Maps with Clusters](https://surelybassy.github.io/FoliumMapping/HTML_Files/map_cluster.html "Maps with Clusters")

Example 1: Simple plotting of cinema coordinates on the map. Settings: tiles='CartoDB dark_matter'

![Map 1](FoliumMap1.png?raw=true "Map Example 1")

Example 2: Plotting cinema coordinates, colour coded by variables in the dataset. Settings: tiles='Stamen Watercolor'

![Map 2](FoliumMap2.png?raw=true "Map Example 1")

Example 3: Adding pop-up with information to each point. Settings: tiles='CartoDB positron'

![Map 3](FoliumMap3.png?raw=true "Map Example 1")

Example 4: Colour coded with Pop-ups. Settings: tiles='OpenStreetMap'

![Map 4](FoliumMap4.png?raw=true "Map Example 1")

Example 5: Clustering point by location. Settings: tiles='CartoDB dark_matter'

![Clustered Map](ClusterGif.gif?raw=true "Map Example 1")



