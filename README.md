Citi Bike Maps Project using leaflet.js

For this project, the Citi Bike API was used to build a map of all the Citi Bike stations and their status in New York City..


1)The citiBike stations information end point is used to get information about the stations and locations.  [Citi Bike station information endpoint](https://gbfs.citibikenyc.com/gbfs/en/station_information.json) 

Each marker is placed at the latitude and longitude returned by the request.
When someone clicks a marker, a popup displays the station name and capacity.
These responses include the name, station, and capacity of each station.



2. A function named `createMap` is used which takes `bikeStations` as an argument. This function creates both the tile layer and an overlay with the pins for each station.

3. A second function named `createMarkers` is used which takes the`response` as an argument.

    * A D3 call response loop through the stations, and then creates a marker to represent each station.

    * Each marker will have a popup to display the name and capacity of its station.


The following image shows the map that results from the above:

Github Pages deployment for Citi Bike Project:
https://bhagi2960.github.io/Citi-Bike-Project/
