# Folium_Pokemon
Locate and giving a location marker of pokemon spawn using Folium package

### Import Pandas
- We use pandas to read the csv file, so much easier than use csv package :)
- "df" means dataframe.
- Total rows (data) on this csv is 314.105 and i only use from 5546 - 6789 ( 1243 rows ), you can change the data range as you like

#### Import Folium
- We use folium for map marker

You can check the standart syntax here :
#### https://python-visualization.github.io/folium/quickstart.html#Getting-Started

- For the location, i use Latitude and Longitude from dataframe for sync the pokemon and map
- You can set zoom-start freely, in this case i use 12
- Tiles is map model, in this case i use 'openstreetmap'. openstreetmap look like a real map
 You can check more map model here :
#### https://python-graph-gallery.com/288-map-background-with-folium/

- 'asd' just a name for looping start. i start from 5546 because my data is start from 5546 and + i for continue looping.
- i use icon_url that already sync with the dataframe. You can check it out

For example :
#### https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/12.png

The just follow the syntax i use. the syntax is standart from folium 

## Hope my work will help you !
### Thankyou 
