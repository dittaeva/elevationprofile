Usage
=====

A simple app to calculate elevation profiles

Raster files should be added in data directory

Test using curl:

curl -H "Content-type: application/json" -X POST http://localhost:5000/elevationprofile.json -d @example/example.geojson

curl -H "Content-type: text/plain" -X POST http://localhost:5000/elevationprofile.wkt -d @example/example.wkt

Example use
===========

A web service running this code is available at [kresendo.no](http://verktoy.kresendo.no/hoydeprofil.html), and [turkompisen.no](http://turkompisen.no) an example of an application using it.
