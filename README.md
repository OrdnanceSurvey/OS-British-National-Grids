# OS British National Grids
A free set of grids at various resolutions for Ordnance Survey’s National Grid


![Grids](https://raw.githubusercontent.com/OrdnanceSurvey/OS-British-National-Grids/main/grids.PNG?token=ABO7BDMCWF5XYTRNMQNO2XLADRWT6)

## GeoPackage
A single, zipped GeoPackage (os_bng_grids.gpkg) containing each grid as a separate layer:
- 100km
- 50km
- 20km
- 10km
- 5km
- 1km

The Coordinate Reference System is British National Grid (EPSG:27700)

Unzipped it is 196MB

## Attribution
Every grid cell is attributed with its 'tile_name'

The 5km grid also contains '1km_grid_ref' which relates to the 1km grid cell at the South-West corner of each cell 
e.g. 'tile_name' = "SP19SW" and 'tile_grid_ref' = "SP1090"

## Coverage
These grids cover the full British National Grid extent (0,0 700000,1300000) 

## Usage
Unzip the GeoPackage and it is ready to use!

As an example, you can drag and drop it straight into QGIS.

These grids can be used for visualisation, data selection (filtering OS data), and we're sure you'll find novel ways to put them to good use. If you do, we'd love to hear about it.

## Licence

If you use our grids please acknowledge OS.

This repo is licensed under the terms of the [Open Government Licence (OGL) v3.0](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). Please see [./LICENCE.txt](./LICENCE.txt).

Contains OS data © Crown copyright and database right 2021.

<img src="http://www.nationalarchives.gov.uk/images/infoman/ogl-symbol-41px-retina-black.png"
     alt="OGL Symbol"
     align="left" />
