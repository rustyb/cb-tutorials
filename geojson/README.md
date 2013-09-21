### Lab 2 - Colin Broderick

**Data Sources**

Shapefiles were aquired from the MapKibera project site - [http://mapkibera.org/](http://mapkibera.org/)

The transport shapefile was downloaded from the following [link](http://data.mapkibera.org/mapkibera/kibera/data/shapefile/transport.zip)

**Conversion to GeoJSON**

Command line was used for the conversion of the shapefiles to geojson. The following query was run in the shapefile directory:

    ogr2ogr -f GeoJSON -t_srs crs:84 nairobi.geojson Road.shp

**Github Repo - cb-tutorials**

Files were uploaded and are stored in this repository at [https://github.com/rustyb/cb-tutorials/tree/gh-pages/geojson](https://github.com/rustyb/cb-tutorials/tree/gh-pages/geojson)


