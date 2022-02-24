# GEODE-Geospatial_python_intro

## Introduction: Setup and [Jupyter](https://jupyter.org/)
In this tutorial we will be using Jupyter Notebooks within Jupyter Lab using python 3.8 in (Ana)conda. Here is a useful [Anaconda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf). Once a python distribution is installed:
1. Clone this repository using method of choice. For example in Git Bash:
```
$ cd /WHERE_REPO_WILL_LIVE/
$ git clone https://github.com/CQuinn8/GEODE-Geospatial_python_intro.git
```
Check contents
```
$ cd GEODE-Geospatial_python_intro
$ ls
```
2a. Use the provided py38-gis.yml environment setup file to install the required libraries:
```
conda env create -f py38-gis.yml
pip uninstal rtree
conda install -c conda-forge rtree=0.9.3
```
2b. If the yml does not work, try to manually create env and install libs:
```
conda create --name py38-gis python=3.8
conda install -c conda-forge jupyterlab geopandas matplotlib ipyleaflet
pip3 install glob2
pip uninstal rtree
conda install -c conda-forge rtree=0.9.3
```
3. Activate environment and open Jupyter Lab: 
```
conda activate py38-gis
jupyter lab
```

# Introduction to Jupyter Notebooks and GeoPandas/Vector data

# Raster data and Visualization
