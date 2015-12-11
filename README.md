# [Locating Archaeological Sites in Northern Mesopotamia](https://cleopythons.wordpress.com/)
(see a YouTube introduction to our project [here]())

*WARNING: Satellite Image files downloaded in Part 1 and Part 5 are large; downloading all of them requires ~50GB free space.*
(Downloaded and Wrangled Data Produced by these Notebooks is available [here](https://www.dropbox.com/sh/ayypu76velfpn7f/AADHxLd0p05vgIie2xys55dGa?dl=0))

## IPython Notebook Order:
1. Part 1: Loading and Wrangling Satellite Image Explanatory Variables
2. Part 2: Response Variable Wrangling
3. Part 3: Random Forest Classification
4. Part 4: Logistic Regression
5. Part 5: Iraq Predictions (in "Iraq Predictions" Folder)

## Additional Files needed to run code included in repository:
* Images: Additional images for Notebook Illustration
* coordinates.csv: coordinates for rectangular clipping area vertices in Part 1 Notebook
* Iraq Prediction\coordinates_iraq.csv: coordinates for rectangular clipping area vertices in Part 5 Notebook
* chromedriver.exe: used by Selenium in Part 2 Notebook on Windows machine to download .kmz file programmatically
* WGS84_1: Used by Grass GIS tool in Part 2 Notebook to work with WGS84 Projected data (.kmz file)

## Important software libraries needed to perform geographic wrangling:
* gdal (Python with GDAL command line tool)
* rasterstats (Python)
* osgeo (Python)
* GRASS GIS
