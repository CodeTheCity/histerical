# histerical
Codethecity 5 team Histerical Time Machine (History of our Streets)

Whether you’re a tourist, researcher or lifetime local resident there’s a wealth of history in our streets to capture your imagination. Union Street hasn’t always been there and as the city plans its next big development we wanted to know what went before. The project led us down three streams of work: a database of historical facts, a web-based GUI with Google Maps, and a 3D rendering of the city’s history.

This repository contains a number of CSVs which form a basic relational database containing information about the city which can be used in either the 2D or 3D version of the product. 

The RESTful API helps generate a JSON file from a series of CSVs which formed the basis of the database. The JSON file is then used by the 3D render to import the data and plot it against the map of Aberdeen.

A similar file will help to generate data which can be plotted for against Google Maps in order to call the data based on pinned locations.

NOTE: some of the files noted above may actually be found in [this repo](https://github.com/CodeTheCity/history_jam) - either additionally or alternatively.
