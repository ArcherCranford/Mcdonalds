# Population Density vs McDonald's Locations: Guilford and Surrounding Counties

## Project Description
The point of this project is to track the relationship between population density and the number of mcdonald's built by a 9 selected counties in North Carolina. Most fast-food chains are built to satisfy a specfic amount of customers per sq. mile. McDonald's is a chain that tends to be frequently opened and has a low threshold for opening. According to google, a mcdonald's needs to have at least 10,000 people in a "service area" to open a franchise. This service area is a 3-5 mile radius or a population density of ~127 people per sq. mile. The scale in which I made the map (counties) throw off this a little. However, you can see from the map that areas like Guilford and Forsyth have a huge population density and have the most Mcdonalds. FOr a county like Caswell, with only one noteable town and a population density of 52.2, they only have one established Mcdonald's. 

## Major Features
- **Interactive Map**: Visualize population density and McDonald's locations using intuitive and responsive mapping.
- **County Data**: Clickable county polygons that display name and population density.
- **GeoJSON Integration**: Real-time rendering of GeoJSON data for counties and restaurant points.
- **Custom Styling**: Dark-themed CartoDB base map with dynamically styled overlays.

## Libraries and Tools
- [Leaflet.js](https://leafletjs.com/) for creating the interactive map.
- [Chroma.js](https://vis4.net/chromajs/) for generating color scales.
- [Font Awesome](https://fontawesome.com/) for custom map markers.

## Data Sources
- **County Data**: GeoJSON file containing population [Census.gov](https://census.gov/quickfacts/)
- **McDonald's Locations**: [Google Maps](https://www.google.com/maps/?entry=wc).
- [CartoDB Dark Matter](https://carto.com/) for the dark-themed base map tiles.

## Author
Archer Cranford
