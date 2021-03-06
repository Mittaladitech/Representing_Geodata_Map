# Representing_Geodata_Map
Simple Python code to load some geographical location and fetch loc coordinates and parse them into Google MAP

Using the Google Places API with a Database and Visualizing Data on Google Map

In this project, we are using the Google geocoding API
to clean up some user-entered geographic locations of
university names and then placing the data on a Google
Map.

In the first phase we take our input data in the file
**(where.data)** and read it one line at a time, and retrieve the
geocoded response and store it in a database *(geodata.sqlite)*.
Before we use the geocoding API, we simply check to see if
we already have the data for that particular line of input.


**Run the geoload.py program.**  This program will read the input
lines in where.data and for each line check to see if it is already
in the database and if we don't have the data for the location,
call the geocoding API to retrieve the data and store it in
the database.

**Simply open where.html in a browser** to see the locations.  You
can hover over each map pin to find the location that the
gecoding API returned for the user-entered input.  If you
cannot see any data when you open the where.html file, you might
want to check the JavaScript or developer console for your browser.

![Map](https://github.com/Mittaladitech/Representing_Geodata_Map/blob/master/image/Screenshot%20(697).png)
