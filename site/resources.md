Resources
=========

## Complete list of training notebooks

### Data Access

* [**python-awips: How to Access Data**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/python-awips-HowToAccessData.ipynb)   
  This notebook covers the relevant methods for accessing EDEX and investigating what data is available. For this example we look at the "grid" data type and investigate the Global Forcast System (GFS) model. We will talk quite a bit about the DataAccessLayer utility, and its [online documentation](http://unidata.github.io/python-awips/api/DataAccessLayer.html#) might be a helpful reference.

* Siphon (TDS intro)

  _add description_

* Siphon (catalogs basic)

  _add description_

* Siphon (catalogs filtering)

  _add description_

* Siphon (remote_open)

  _add description_

* Siphon (remote_access)

  _add description_

* Siphon (subset)

  _add description_

### Data Analysis
* Numpy (basics)

  _add description_

* Numpy (csv data)

  _add description_

* Scipy

  _add description_

* [Pandas (basics)] (https://github.com/Unidata/pyaos-ams-2021/blob/master/notebooks/pandas.ipynb)

  This notebook is an introduction to timeseries analysis and plotting using pandas.

* xarray (data access)

  _add description_

* xarray (indexing)

  _add description_

* xarray (interpolation)

  _add description_

* xarray (aggregations)

  _add description_

* xarray (calculations)

  _add description_

* Unit-aware operations (Pint)

  _add description_

* MetPy (basic calculations)

  _add description_

* MetPy (calculations for soundings)

  _add description_

* MetPy (unit-aware calculations)

  _add description_

* MetPy (with xarray)

  _add description_

### Meteorological Background Material
* Cross Section Analysis

  _add description_

* Isentropic Analysis

  _add description_

### Visualization
* Cartopy (basic)

  _add description_

* Cartopy (intermediate)

  _add description_

* Declarative Plotting

  _add description_

* **Matplotlib: Basics**  
  This notebook covers the basics of how to use [matplotlib.pyplot](https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.html).  It describes the two main parts of the plot: the figure and axes.  The notebook walks through how to create simple line and scatter plots, how to modify the axes and titles, how to draw multiple data sets on the same graph, and how to alter the display settings for the data.

* **Matplotlib: Intermediate**  
  This notebook builds upon the Matlibplot: Basics notebook and details how to create more complicated plots.  It starts by describing how to draw multiple plots in one figure.  It also covers the scatter function and how it can be used to control the colorization of individual scatter points.  Finally, the notebook gives an introducton to imshow, contour, and contourf and how they can be used to visualize data.

* MetPy (SkewT)

  _add description_

* [**python-awips: Working with the Maps and Topography Databases**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/python-awips-WorkingWithMapsTopoDatabases.ipynb)  
  This notebook covers how to use the AWIPS Maps Database to access GIS objects, which are returned as Shapely geometries (Polygon, Point, MultiLineString, etc.) and can be easily plotted by Matplotlib, Cartopy, MetPy, and other packages.  It shows how to use maps and topo data types to obtain GIS data from the AWIPS databases.  Finally, it walks through the steps of plotting data to create a very informative map of a County Warning Area.
  
* [**python-awips: Working with Models**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/python-awips-WorkingWithModels.ipynb)  
  This notebook creates a colorized plot for the continental US of model data (grib).  It explains how to access the model data from an EDEX server and limit the data returned by using model specific parameters. The notebook covers how to use both pcolormesh and contourf to create colorized plots, and compare the differences between the two.

* [**python-awips: Working with Satellite Data**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/python-awips-WorkingWithSatelliteData.ipynb)  
  This notebook investigates what satellite data is available from an EDEX server.  It describes how to define map properties in a function that can be used to plot multiple images.  It then walks through how to retreive Mesoscale GOES satellite grid data from an EDEX server.  Finally, it uses matplotlib pcolormesh to plot the colorized images with a colorbar.

* [**python-awips: Working with Surface Obs**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/python-awips-WorkingWithSurfaceObs.ipynb)  
  This notebook creates a colored temperature plot for North America using AWIPS METAR observations (datatype *obs*), similar to existing products in GEMPAK and CAVE. We will be accessing the data through an EDEX server and limiting what's returned based geographic extend, and specific parameters we're interested in.  We'll also be creating a color mapping and colorizing the surface data based on our mapping.  Finally we use matplotlib to plot and display the output.

* [**python-awips: Working with Upper Air Obs**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/python-awips-WorkingWithUpperAirObs.ipynb)  
  This notebook shows how to retreive upper air vertical profile data from EDEX server.  It uses EDEX to get the pressure, temperature, dewpoint lines and wind profile data for the Upper Air observation.  Finally, it describes how to plot a Skew-T/Log-P plot with Hodograph using Matplotlib and Metpy.

### Notebook Enhancements
* [Notebook widgets](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/notebook_enhancements/NotebookWidgetsTraining.ipynb)

  This notebook explores various interactive [Jupyter Widgets](https://ipywidgets.readthedocs.io/en/stable/user_guide.html) and how they might be used to create dynamic visulizations and user interaction in a Jupyter Notebook.

## Links to other various Python resources
