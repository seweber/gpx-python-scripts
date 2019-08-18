# GPX Python Scripts
The repository contains Python 3 scripts for processing GPX tracks, licensed under the Apache License 2.0.

## Dependencies

The scripts depend on the following Python libraries which can be installed via pip: numpy, mayavi, keyring, tqdm, blessings

## Scripts

### download-gpx-from-garmin.py

Download and combine GPX tracks from Garmin Connect. This script makes heavy use of the Python libraries garminexport and gpxpy. The submodules link to their repositories.

### visualize-gpx.py

Plot GPX tracks on top of 3D maps, generated from sattelite images and geographic elevation data.

This script is still under development, useful resources are
- https://pypi.org/project/elevation/
- https://geohackweek.github.io/raster/05-pygeotools_rainier/
- https://mycarta.wordpress.com/2014/05/08/visualize-mt-st-helen-with-python-and-a-custom-color-palette/
- http://geoexamples.blogspot.com/2014/02/3d-terrain-visualization-with-python.html
- https://www.geodose.com/2018/03/create-elevation-profile-generator-python.html
- http://geologyandpython.com/dem-processing.html