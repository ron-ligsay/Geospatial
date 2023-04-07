geopandas

Major pieces of Software of geopandas that uses

pandas - data analysis

shapely - geometric shapes
 - GEOS

 fiona - reading and  writing files
  - OGR

pyproj - cartographic projections
 - PROJ.4

descartes - mapping
geopy - geocoding
rtree - spatial analysis
pysal - coloring maps
numpy - math

## Installing GeoPandas
brew install gdal
brew install geos
brew install spatialindex

pip3 install pillow
pip3 install pysal
pip3 install geopandas
pip3 install https://github.com
pip3 install rtree

Requires Microsoft Visual C++ 14.0 is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
Requires Python version 3.5 or later.


## Shapefile
Shapefile is a popular geospatial vector data format for geographic information system (GIS) software. A shapefile is a simple, nontopological format for storing the geometric location and attribute information of geographic features. Shapefiles are composed of three files: a main file with a .shp extension, a file with a .shx extension, and a file with a .dbf extension. The main file stores the geometry and spatial location of the features, the .shx file stores the index of the main file, and the .dbf file stores attribute information of the features in the shapefile.

shapefile is the actual geometry of your data. It is a file with a .shp extension. It is a binary file that stores the geometry of the features. It is the main file of the shapefile.
  .shp - stores the geometry of the features
  .dbf - database - stores the attribute information of the features (name, state, gpd, etc.)
  .prj - projection - stores the projection information of the features (gives all the assumpotions making the earth or the map)
  .shx - shape index - stores the index of the features in the shapefile

You can look them up on esri.comm/arcgisdestop - ArcGIS Desktop 9.3 Help /shapefiles/shapefile file extensions