# Resources and tutorials

## All-in-one tutorials for earth data science
* Earth Lab at University of Colorado, Boulder: 
  * [Online "textbook:" Introduction to Earth Data Science](https://www.earthdatascience.org/courses/intro-to-earth-data-science/) - zero to hero tutorial covering bash, python, git/github, and data science workflows - The best all in one tutorial on these topics I have seen!
  * [Workshop: Get Started With GIS in Open Source Python - Geopandas, Rasterio & Matplotlib](https://www.earthdatascience.org/workshops/gis-open-source-python/) - Covers similar material to geohackweek, but with more brevity

## Introductions to remote sensing from NASA ARSET

* [Fundamentals of Remote Sensing](https://arset.gsfc.nasa.gov/webinars/fundamentals-remote-sensing): Session 2B: Satellites, Sensors, and Earth Systems Models for Water Resources Management and Session 2C: Fundamentals of Aquatic Remote Sensing
## Learning python
1. A bare-bones, interactive [tutorial](https://www.learnpython.org/) in python basics, with a more detailed version available for purchase at DataCamp.

2. MIT 6.00: [Introduction to Computer Science and Programming](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/): How Ethan learned programming and python. Not recommended because it is quite verbose! It is also taught in python 2.xx, while python 3.xx is now current. 

3. Matplotlib plotting style [guide](https://matplotlib.org/gallery.html)

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

## Matlab
...

## R
...
