# Resources and tutorials

## All-in-one tutorials for earth data science
* Earth Lab at University of Colorado, Boulder: 
  * [Online "textbook:" Introduction to Earth Data Science](https://www.earthdatascience.org/courses/intro-to-earth-data-science/) - zero to hero tutorial covering bash, python, git/github, and data science workflows - The best all in one tutorial on these topics I have seen!
  * [Workshop: Get Started With GIS in Open Source Python - Geopandas, Rasterio & Matplotlib](https://www.earthdatascience.org/workshops/gis-open-source-python/) - Covers similar material to geohackweek, but with more brevity
  
* Five spatial python/QGIS [tutorials](https://courses.spatialthoughts.com/index.html), recently made freely available by the author, Ujaval Gandhi. Recommended:
  * [Python Foundation for Spatial Analysis (Full Course Material)](https://courses.spatialthoughts.com/python-foundation.html): Lengthy, and more spatially-focused than CU Earth Lab course (above), but less flashy and current than geohack week.

## Introductions to remote sensing from NASA ARSET

* [Fundamentals of Remote Sensing](https://arset.gsfc.nasa.gov/webinars/fundamentals-remote-sensing): Session 2B: Satellites, Sensors, and Earth Systems Models for Water Resources Management and Session 2C: Fundamentals of Aquatic Remote Sensing
* [Advanced Webinar: Land Cover Classification with Satellite Imagery](https://arset.gsfc.nasa.gov/land/webinars/advanced-land-classification) and [Advanced Webinar: Change Detection for Land Cover Mapping](https://arset.gsfc.nasa.gov/land/webinars/adv-change18) - overview of fundamentals of landcover classification mapping- supervised, unsupervised
* [Advanced Webinar: Accuracy Assessment of a Land Cover Classification](https://arset.gsfc.nasa.gov/land/webinars/18adv-land-classification) - converting your accuracy matrix into confidence intervals

## Learning python
Python and its numerical array programming package, numpy, have become so ubiquitous in the sciences that they were the topic of a 2020 review [article](https://www.nature.com/articles/s41586-020-2649-2) in Nature!

1. A [tutorial](https://docs.python.org/3/tutorial/) provided by the developers of python- not recommended for beginners because it is quite formal and technical. Good for reference, though.

2. [Python Like You Mean It](https://www.pythonlikeyoumeanit.com/): this looks good! Written by a former physics grad student who wished something like this had existed when they started. Described as "a free resource for learning the basics of Python & NumPy, and moreover, becoming a competent Python user," and "a lean, one-stop resource for learning the essentials of Python from scratch."

3. Basic, interactive [tutorial](https://www.w3schools.com/python/) from W3Schools.com with advertisements.

4. A bare-bones, interactive, 10-minute-long [tutorial](https://www.learnpython.org/) in python basics, with a more detailed version available for purchase at DataCamp.

5. MIT 6.00: [Introduction to Computer Science and Programming](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/): How Ethan learned programming and python. Not recommended because it is quite verbose! It is also taught in python 2.xx, while python 3.xx is now current. 

6. Matplotlib plotting style [guide](https://matplotlib.org/gallery.html)

## Python for tabular data analysis: pandas package

1. A list of [tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html) from pydata.org.

2. Geohackweek chapter

## Shell scripting in bash
Bash is the most commonly used shell scripting language in minutes systems, and is often the default.  It is the go-to for scientific processing workflows, and can be used to run other programs: python, matlab, etc. It is delightfully old-school, yet highly powerful.

### Step one: install the windows subsystem for linux
...or Docker, Virtual Box, or git-bash. WSL is available from the microsoft [store](https://docs.microsoft.com/en-us/windows/wsl/install-win10) for free and I find it the most convenient way to run Linux on a Windows machine in a fast, low-resource way. Bonus: WSL integrates with the text editor Visual Studio Code.

1. Lynda tutorial on ["Linux: Bash Shell and Scripts"](https://www.linkedin.com/learning/linux-bash-shell-and-scripts/): requires LinkedIn Learning membership, which Brown subscribes to. Information should be fairly easy to understand, but will take some time to watch the videos.

2. [The linux documentation project](http://tldp.org/guides.html): lots of useful, if dated, guides and code snippets to learn with. For a quick crash course, or info on a specific topic, try the [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/index.html) by Machtelt Garrels and [Advanced Bash-Scripting Guide](http://tldp.org/LDP/abs/html/) by Mendel Cooper.

## Geocomputation workflows

1. [Geohackweek](https://geohackweek.github.io/): An up-to-date resource for geoprocessing workflows in Python, introduced through a series of python Jupiter notebook tutorials. Thanks to The University of Washington organizers for offering these workshops and archiving the tutorials!

2. Spatial-ecology.net workshops and [tutorials](http://spatial-ecology.net/dokuwiki/doku.php): Now preserved on Youtube, this site gives introductions to a variety of geospatial processing, including command line programs like gdal, and GIS software like QGIS and GRASS. Includes some introduction to linux, bash, and python as well. Thank you to Giuseppe Amatulli at Yale for hosting this site.

## Remote sensing tutorials

1. [NASA ARSET](https://arset.gsfc.nasa.gov/) has dozens of tutorials on a number of topics, from sensors like optical and SAR to applications such as wildfires and hydrology.

## Data science/machine learning

1. Artificial Intelligence for Earth System Sciences workshop (https://www2.cisl.ucar.edu/events/summer-school/ai4ess/2020/artificial-intelligence-earth-system-science-ai4ess-summer-school): includes archived workshop tutorials and jupyter notebooks, organized by NCAR.

2. [ORNL DAAC learning resources](https://daac.ornl.gov/resources/learning/): Dozens of quick tutorials on specific topcs such as downloading and analyzing multi-spectral AVIRIS data to using their WMS web maps in GIS tools.

3. [Pangeo gallery](http://gallery.pangeo.io/), a set of example scripts and workflows for various earth science topics, using the open – source [pangeo](https://pangeo.io/) Python environment

## Google Earth Engine

1. Straight from the [source](https://developers.google.com/earth-engine/guides). Also covered in [geohackweek](https://geohackweek.github.io/GoogleEarthEngine/01-introduction/).
2. [Examples scripts](https://code.earthengine.google.com/) in the default code editor
3. Useful python toolboxes: geemap

## Visualization
1. [Pydeck/Google Earth Engine](https://pypi.org/project/pydeck-earthengine-layers/)
2. [ColorMoves](https://sciviscolor.org/home/colormoves/): An interactive color map picker tool, downloadable color maps, and a script to import them into python or matlab

## DEM tools
1. RichDEM
2. TauDEM
3. Topotoolbox (Matlab)
4. [Mod-WET](https://margulis-group.github.io/teaching/): accompanying matlab package for Steven Margulis' online hydrology textbook.
5. Arcmap standard toolboxes and optimized pit removal tool
6. Whitebox GAT: geomorphology package
7. CloudCompare: open-source GIS-like software for all 3D formats, especially point clouds

## GDAL/OGR command line reference
* [GDAL/OGR cheat sheat](https://github.com/dwtkns/gdal-cheat-sheet)
* Another less-helpful [OGR cheat sheat](https://www.bostongis.com/PrinterFriendly.aspx?content_name=ogr_cheatsheet)

## Git
Git is software for code version control for individuals who want to be able to revert to checkpoints. It also offers ways to seamlessly sync scripts between collaborators using websites like github.
* LinkedIn Learning [course](https://www.linkedin.com/learning/git-essential-training-2012) on git - how Ethan learned
* Much shorter all-in-one tutorial through the online school, [W3docs](https://www.w3docs.com/learn-git.html)
* Git [tutorial](https://www.atlassian.com/git) from the developers of github
* Learning through a series of turorials on [github](https://try.github.io/)
* Another jupyter notebook-based [tutorial](https://github.com/patrickcgray/deep_learning_ecology/blob/master/Git_Basics.ipynb) for learning git, from Patrick Gray.


## Matlab
...

## R
...
