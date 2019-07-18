__1)__ Download Tilemill from https://tilemill-project.github.io/tilemill/

__2)__ Create new project and name

__3)__ Make sure to do all geoprocessing, clipping, & reprojecting in GIS program before next step

__4)__ In bottom left corner, click __Layers__ > __Add Layer__ > Navigate to your shapefile (Note: must be in WGS 84: EPSG-4326)

__5)__ Next to "Datasource" click __Browse__ > Navigate and highlight to your saved .shp > Click __Save & Style__

__6)__ In the right pane with the markup code language, change the color and width settings by editing the numbers

(Note: the #djdfjgk notation is hex value colors and can be found by googling hex values)

If you have a preferred style to use each time, make sure to save these settings in a text document for reference. Helpful details are: zoom levels, any popup boxes, and processing times

__7)__ Once you have the desired styling and pop-up features, make sure to __Comment Out__ the Countries basemap by putting __/* and */__ before "Map" and after the closing } for Map 


/*Map {
  background-color: #b8dee6;
}

#countries {
  ::outline {
    line-color: #85c5d3;
    line-width: 2;
    line-join: round;
  }
  polygon-fill: #fff;
}*/

__8)__ Be sure to click __Save__ > __Export__ > __MBTiles__

__9)__ Zoom into your data and use __Shift+drag__ to roughly outline your data area.  Then click the center of data to place center pin

__10)__ Fill in the __Name, Filename, and Zoom__ fields.  it is helpful to populate __Filename__ with zoom levels, date, etc (dpa19_4_Federal_13_18_20190717)

(Note: you will need to test file sizes by changing zoom levels as this determines how many tiles will be created by zoom level)  For smaller filesizes, try to stay below zoom level 18

__11)__ Allow the export to complete (usually 5-90 minutes depending on file size).  View and __Save__ file in the __Export__ button
