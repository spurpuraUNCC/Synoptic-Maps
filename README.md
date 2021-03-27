# Synoptic-Maps
These files create a 4 panel of maps including 250 hPa (upper left), 500 hPa (upper right), 
850hPa (lower left), and surface maps (lower right). The 250 hPa map calulates and plots 
height,jet stream (colorfill), wind barbs, and divergence. The 500 hPa map calulates 
voticity(colorfill) and is plotted alongside the heights and wind barbs. At 850 hPa, the 
relative humidity (colorfill), temperature (blue), heights, wind barbs are plotted. On the 
surface map, MSLP, temperature (red), dew point (blue), and wind barbs are plotted. 

The 'Synoptic 4 Panel using Thredds' code uses netCDF to siphon in the data from thredds
and then calculates and plots the parameters. The 'Synoptic 4 panel using downloaded files'
code uses xarray to bring in the data from the GRIB files. All of the maps were created using
RUC and RAP model data.
