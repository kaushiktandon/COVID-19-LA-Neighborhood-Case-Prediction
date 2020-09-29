The current version of L.A. County neighborhoods as defined by the Los Angeles Times

### Shapefiles
The [shapefile](https://en.wikipedia.org/wiki/Shapefile) format stores the data as primitive geometric shapes like points, lines, and polygons. These shapes, together with data attributes that are linked to each shape, create the representation of the geographic data. The shapefile format consists of a collection of files with a common filename prefix, stored in the same directory.
#### Mandatory files
.shp — shape format; the feature geometry itself {content-type: x-gis/x-shapefile}
.shx — shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly {content-type: x-gis/x-shapefile}
.dbf — attribute format; columnar attributes for each shape, in dBase IV format {content-type: application/octet-stream OR text/plain}

#### Other files
.prj — projection description, using a well-known text representation of coordinate reference systems {content-type: text/plain OR application/text}
