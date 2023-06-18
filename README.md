# PLUS_softwaredev_2023_mprn
Software Development Course

## Assignment 1:
Candela Pelliza, Felipe Camacho and Elena Nafieva contributed to my repository

## Assignment 2:
Modified the environment "software_dev_v1.yml" using Anaconda Prompt by:
* Updating all the packages: `conda update`
* Installing Pydeck. Noticed that it is faster if the channel is explicitly named: `conda install -c conda-forge pydeck`
* Uninstalling Folium: `conda remove folium`
* Exporting the modified environment: `conda env export -n software_dev_v1>software_dev_v1_mod.yml`

For the environment "software_dev_v2.yml", it could not be recreated even if it is OS generic. Possibly, as it does not specify the versions of the packages or dependencies, it can lead to an unsolvable environment. The OS may not be able to resolve the environment because it cannot determine the appropriate versions of the packages to install.

## Assignment 3:
Created a Jupyter Notebook with the basic steps of working with Satellite Images in Python, specifically leveraging numpy, matplotlib, and rasterio. 
* Used dataset: Landsat 8 OLI/TIRS C2 L2 image which covers Buenaventura, a coastal seaport city situated in Colombia
* Based on: series of blog tutorials titled [Python for Geosciences: Working with Satellite Images (step by step)](https://medium.com/@cordmaur/list/python-for-remote-sensing-25d32ab8f21d) created by Maurício Cordeiro

## Assignment 4:
ECOSTRESS python module is meant to help the users to interact with the NASA AppEEARS API to download and cloud mask ECOSTRESS Land Surface Temperature (LST) satellite data
