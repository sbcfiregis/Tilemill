1) Download Tilemill from https://tilemill-project.github.io/tilemill/
2) Create new project and name
3) Make sure to do all geoprocessing, clipping, & reprojecting in GIS program before next step
4) In bottom left corner, click __Layers__ > __Add Layer__ > Navigate to your shapefile (Note: must be in WGS 84: EPSG-4326)
5) Next to "Datasource" click __Browse__ > Navigate and highlight to your saved .shp > Click __Save & Style__
6) In the right pane with the markup code language, change the color and width settings by editing the numbers

(Note: the #djdfjgk notation is hex value colors and can be found by googling hex values)

If you have a preferred style to use each time, make sure to save these settings in a text document for reference. Helpful details are: zoom levels, any popup boxes, and processing times

7) Once you have the desired styling and pop-up features, make sure to __Comment Out__ the Countries basemap by putting __/* and */__ before "Map" and after the closing } for Map 


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
