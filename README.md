# Get Sentinel-1 SAR estimates of snowmelt runoff onset

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.15213849.svg)](http://dx.doi.org/10.5281/zenodo.15213849)

This repository contains notebooks and tools adapted from Gagliano (2022) (https://github.com/egagli/sar_snowmelt_timing) to get Sentinel-1 SAR backscatter timeseries' over a defined time period/bounding box for multiple SNOTEL station locations to identify snowmelt runoff onset via backscatter minima. Tools in this repository were used in tandem with SNOTEL data that was processed and analyzed with snotelprocessr (https://github.com/allydetre/snotelprocessr).

See the examples folder for the main script that gets the backscatter timeseries and generates plots for each station-year, and in addition to scripts that generate 1 km^2 bounding boxes (GEOJSONs), get USGS 3DEP DEMs for each GEOJSON, lat/lon to UTM coordinate conversion. 
