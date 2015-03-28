FlightJournal

Displays an animated history of the flights I've taken between 2005 and 2014.

This page was built using [Mapbox](http://www.mapbox.com) and specifically their [Flight Paths Example](https://www.mapbox.com/mapbox.js/example/v1.0.0/animating-flight-paths/) as a template.

Beginning in 2005 I kept a record of my flights via [FlightMemory.com](http://www.flightmemory.com).  After retrieving my list from there, I converted between airport codes and latitude/longitude using data from [Openflights.org](http://www.openflights.org/data.html).  Each flight is saved as a pair: [[departure_lat,departure_lon], [arrival_lat,arrival_lon]] in flightpairs2005-2014.js. 