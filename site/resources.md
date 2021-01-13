Resources
=========
<!--

When adding your link to a bullet, make sure to use the following format:

* [**title**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/<rest-of-path>.html)<space><space>
  Add description here

Note the two empty spaces after the closing parenthesis (i.e. <space><space>).
This is critical, as lines that end with two empty space characters will be rendered as a <br> html element.
The end result is a tighter vertical spacing between the opening line of the bullet point (the link) and the notebook description.

-->
## Complete list of training notebooks

### Data Access

* [**python-awips: How to Access Data**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/python-awips-HowToAccessData.ipynb)  
  This notebook covers the relevant methods for accessing EDEX and investigating what data is available. For this example we look at the "grid" data type and investigate the Global Forcast System (GFS) model. We will talk quite a bit about the DataAccessLayer utility, and its [online documentation](http://unidata.github.io/python-awips/api/DataAccessLayer.html#) might be a helpful reference.

* [**Pandas and Numpy (csv data)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/pandas_and_numpy_csv.ipynb)  
  This notebook uses pandas and numpy to read and manipulate data from a csv file.

* [**Siphon (catalogs basic)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/siphon-catalog-basics.ipynb)  
  This notebook covers the basics for using the library Siphon to interact with THREDDS Catalogs. Topics covered include reading remote THREDDS Catalogs, moving from one catalog to another, and interacting with THREDDS Catalog Datasets. 

* [**Siphon (catalog filtering)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/siphon-catalog-filtering.ipynb)  
  This notebook provides tips and tricks for filtering datasets contained within a THREDDS Catalog based on time when the dataset names include date and time information.

* [**Siphon (remote_open)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/siphon-RemoteOpen.ipynb)  
  This notebook demonstrates the Siphon `remote_open` function, which opens a TDS Catalog remote dataset for random access, and provides examples of interacting with the returned file-like object.

* [**Siphon (remote_access)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/siphon-RemoteAccess.ipynb)  
  This notebook covers opening, inspecting, subsetting, and plotting a TDS dataset using Siphon's `remote_access` method.

* [**Siphon (subset)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/siphon-Subset.ipynb)  
  This notebook demonstrates how to use Siphon to subset and download data using the NetcdfSubset service (NCSS). NCSS supports coordinate-based subsetting, i.e. selecting data by latitude, longitude, time, etc.
  
* [**Xarray Data Access**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/dataAccess/xarray_data_access.ipynb)  
  This notebook demonstrates how to access local NetCDF and GRIB files and remote OPENDAP files with xarray, as well as briefly how to connect NetCDF data loaded from Siphon into xarray.

### Data Analysis
* [**Numpy (basics)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/numpy.ipynb)  
  This notebook highlights pythonic programing with numpy arrays as opposed to lists.

* [**Pandas (basics)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/pandas.ipynb)  
  This notebook is an introduction to timeseries analysis and plotting using pandas.

* [**Indexing with xarray**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/xarray_indexing.ipynb)  
  This notebook discusses the various methods for indexing and selecting subsets of data in xarray.
  
* [**Interpolation and regridding with xarray**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/xarray_interpolation.ipynb)  
  This notebook discusses interpolating and regridding data in xarray and the companion package xesmf.
  
* [**Xarray aggregation operations**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/xarray_aggregations.ipynb)  
  This notebook demonstrates how to easily apply aggregation operations (mean, sum, variance, etc.) to data in xarray objects.
  
* [**Calculations in xarray**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/xarray_calculations.ipynb)  
  This notebook describes calculations other than aggregations that can be easily performed with xarray data (including some verification metrics from xskillscore)

* [**Unit-aware operations (Pint)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/units.ipynb)  
  This notebook is an introduction to unit support in MetPy via Pint.

* [**MetPy (basic calculations)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/metpy_basics.ipynb)  
  This notebook provides a basic introduction to meteorological calculations using MetPy.
* [**MetPy and Soundings: Calculations**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/metpy-soundings-calculations.ipynb)  
  This notebook demonstrates how MetPy can be used to compute common sounding derived parameters, such as the Lifting Condensation Level, convective available potential energy (CAPE), and convective inhibition (CIN).

* [**MetPy with xarray**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/analysis/metpy_and_xarray.ipynb)  
  MetPy provides a fair number of helpful utilities to make working with gridded atmospheric science datasets easier in xarray (in the areas of coordinates/coordinate reference systems, units, and calculations). This notebook also acts as a big-picture introduction to using xarray, with directions to the more focused xarray notebooks where applicable, so this might be the best one to start out with among the xarray notebooks!

### Meteorological Background Material
* Cross Section Analysis

  _add description_

* [**Isentropic Analysis**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/isentropic_introduction.ipynb)  
  Provides a basic description and example of Isentropic analysis techniques.

### Visualization
* [**Cartopy (basic)**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/Cartopy-Intro.ipynb)  
  This notebook covers the basic of CartoPy, a package which is useful for creating maps. Examples of creating a basic map, adding map features, and plotting data are covered in this notebook. The [CartoPy Example Gallery](https://scitools.org.uk/cartopy/docs/latest/gallery/index.html) would be another useful resource for users.

<!-- * Cartopy (intermediate)

  _add description_ -->

* [**Declarative Plotting**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/Declarative-Example.ipynb)  
  This notebook provides an overview on how to use the declarative syntax within MetPy to create satellite, surface, upper-air, and model data maps. MetPy's METAR parsing functionality is also utilized in this tutorial, along with data smoothing methods. Another useful resource for those interested in learning more about the declarative syntax is the [declarative tutorial on MetPy's website](https://unidata.github.io/MetPy/latest/tutorials/declarative_tutorial.html)

* [**Matplotlib: Basics**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/matplotlib-basics.ipynb)  
  This notebook covers the basics of how to use [matplotlib.pyplot](https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.html).  It describes the two main parts of the plot: the figure and axes.  The notebook walks through how to create simple line and scatter plots, how to modify the axes and titles, how to draw multiple data sets on the same graph, and how to alter the display settings for the data.

* [**Matplotlib: Intermediate**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/matplotlib-intermediate.ipynb)  
  This notebook builds upon the Matlibplot: Basics notebook and details how to create more complicated plots.  It starts by describing how to draw multiple plots in one figure.  It also covers the scatter function and how it can be used to control the colorization of individual scatter points.  Finally, the notebook gives an introducton to imshow, contour, and contourf and how they can be used to visualize data.

* [**MetPy SkewT**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/visualization/MetPy-SkewT.ipynb)  
  This notebook demonstrates how to download archived sounding data from the University of Wyoming sounding archive. It then demonstrates how to plot that sounding data on a skew-T diagram using MetPy and add an inset hodograph to that diagram.

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
* [**Notebook widgets**](https://nbviewer.jupyter.org/github/Unidata/pyaos-ams-2021/blob/master/notebooks/notebook_enhancements/NotebookWidgetsTraining.ipynb)  
  This notebook explores various interactive [Jupyter Widgets](https://ipywidgets.readthedocs.io/en/stable/user_guide.html) and how they might be used to create dynamic visulizations and user interaction in a Jupyter Notebook.

## Links to other various Python resources

* [**Unidata MetPy Monday YouTube Playlist**](https://www.youtube.com/playlist?list=PLQut5OXpV-0ir4IdllSt1iEZKTwFBa7kO)  
  A weekly video series showing how to use MetPy or other Python libraries to solve problems relevant to geoscience applications.

* [**Unidata Python Training**](https://unidata.github.io/python-training/)  
  The Unidata Python Training site is meant to be a one-stop website for learning how to use Python for earth-science education and research for any experience level. 
