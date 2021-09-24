# La_Mercante_Seoul

## About
'La Mercante Seoul' is a Python and Pandas project that processes South Korean public data to analyze market-entry strategies of franchise brands in Seoul.

This project applies descriptive statistics for Exploratory Data Analysis(EDA) technique in Python including correlation analysis, Dist plot, Joint plot, and KDE plot.

This project visualizes geospatial data on the map using Python Folium library tools: GeoJSON, Choropleth, Heatmap, and Marker Cluster (Please check Important Notes below). 

Python Missingno Library is used to impute and visualize missing values.


## Description
### Commercial District Analysis (Part 1 and 2)
* Data Load and Missing Value (Part 1)
* Missing Value Visualization by 'missingno' Library
* Data Preprocessing: Raw Korean Data to Useable DataFrame
* Descriptive Statistics: 'Univariate' and 'Bivariate' Analysis
* Subset Analysis - Food Business Analysis: Boolean Indexing
* Subset Analysis - Education Business
* Multi-index Reformation (Part 2)
* Visualization by 'Latitude' and 'Longitude'

### Baskin-Robbins and Dunkin'
* Missing Data Handling and Data Preprocessing
* Text Data Analysis
* Data Visualization
* Map Visualization

### Starbucks and Ediya Coffee
* Visualization by Pandas functions and Seaborn
* 'groupby' vs 'pivot_table'
* Folium with SimpleMarker
* GeoJSON and Choropleth
* CircleMarker based on Number of Stores

### Paris Baguett and Tous Les Jours
* Data Visualization
* Map Visualization

## Important Notes
### Note 1
When you try to open **'Commercial District Analysis 2.ipynb'** to view, you might see `Sorry, something went wrong. Reload?` message.
This is because .ipynb file is too big to open in github. Please click 'Reload' several times more until you see the contents.
If you cannot see the contents after clicking 'Reload' more than 5 times, you can download and open the file on your machine.
I highly recommend using **Anaconda** to open the file. Please refer to **How to Download and Install** section for the detailed instruction.

### Note 2
Unfortunately, if you open jupyter notebook files on github, you will find out that results of some Python functions using Folium library are not visuable because this library uses actual map to plot the data on it based on the longitude and latitude and github does not support this functionality. Please refer to **How to Download and Install** section to see how to run jupyter notebook files on your machine.


### Note 3
The public data file used in this project is too big to be uploaded in github repository. 
Please go to the following link and download **'seoul_store_info.csv'** file

Google Drive: https://drive.google.com/drive/folders/1_GTU8YnA85HdIaygMf0xUQO3H611Agz6?usp=sharing


## How to Download and Install
**Anaconda** is a Python distribution that makes it easy to install Python plus a number of its most often used 3rd party libraries in a flexible way. You can open **Jupyter Notebook** through Anaconda and upload the file after downloading from this repository to open.

**Download link**: https://www.anaconda.com/products/individual

After downloading Anaconda, you have to install the following libraries:
* If you are using Mac OS, plsease navigate to 'Environemnt' -> 'base (root)' -> 'Open Terminal' 
* Once you open the terminal through Anaconda Navigator, please install the following commands:
* **Folium**: `conda install -c conda-forge folium`
* Using `pip list` command on the terminal, double-check whether the following libraries are successfully installed: `pandas`, `numpy`, and `matplotlib`
* If any of the three libraries are missing, please install it by commanding `pip install [library name]`


## Data Resource
* https://www.data.go.kr/en/index.do
* https://www.data.go.kr/data/15012005/openapi.do















