The current version of L.A. County neighborhoods as defined by the Los Angeles Times

### Shapefiles
The [shapefile](https://www.earthdatascience.org/workshops/gis-open-source-python/intro-vector-data-python/) format stores the data as primitive geometric shapes like points, lines, and polygons. These shapes, together with data attributes that are linked to each shape, create the representation of the geographic data. The shapefile format consists of a collection of files with a common filename prefix, stored in the same directory.
#### Mandatory files
.shp — the file that contains the geometry for all features

.shx —  the file that indexes the geometry

.dbf — the file that stores feature attributes in a tabular format

#### Other files
.prj — the file that contains information on projection format including the coordinate system and projection information. It is a plain text file describing the projection using well-known text (WKT) format
