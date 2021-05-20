# GISC420
#### Rhiannon and Katie's Final Project

#### Purpose: 
1) To use ArcGIS Pro's Model Builder to create a workflow that helps select a site based on the viewshed from a linear feature (such as a road)
2) To create a Python script that replicates this workflow through the use of Jupyter notebooks and code

Locations trialed have been selected based on the importance of viewsheds in the siting and location of development. 

#### Potential Locations to Trial: 
- Queenstown-Lakes, New Zealand
- Wellington, New Zealand
- Highlands, Scotland

#### Tasks
1) Find appropriate DEM
2) Create sample road lengths
3) Understand viewshed outputs
4) Think about workflow, combining raster
5) Trial in ArcGIS
6) Think about categorisation 
7) Experiment with different thresholds
8) Export code and look up pyarc 
9) Bring into Jupyter notebooks
10) Experiment and try and find pyarc solution

#### Potential Workflow
1) Inputs: DEM, linear feature, distance between points
2) Turn linear feature into points
3) Execute viewshed for each point
4) Combine resulting raster
5) Classify raster


#### Resources:
[arcpy code for a basic viewshed tool](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-analyst/viewshed.htm)

[ArcGIS Pro Course in viewshed analysis](https://www.esri.com/training/catalog/57d8718d8b3e1ff2376bf91c/performing-viewshed-analysis-in-arcgis-pro/)

[Iterations in Model Builder](https://pro.arcgis.com/en/pro-app/latest/tool-reference/modelbuilder-toolbox/examples-of-using-iterators-in-modelbuilder.htm) & [Youtube Walkthrough](https://www.youtube.com/watch?v=DoIkV2y0pEc)

[JupyterLab](https://www.youtube.com/watch?v=A5YyoCKxEOU&t=1s)


### What we have tried
- First tried to create ArcGIS Pro ModelBuilder but ran into issues with only being able to do iteration once and not being able to choose how and when the iteration stopped in the workflow. We were able to use iteration for the points but were unable to combine the datasets within the workflow because the output raster kept on being overwritten
- We exported the code from Arc into Spyder to examine it, it had multiple errors and was unable to run as a standalone script
- We tried to bring that data into Jupyter Lab to work with and ran into the same issues
- Then we tried to get arcpy working on the lab machines but unfortunately ran into errors because of the environment and were unable to access the g420 environment and install arcpy on it
- We created a notebook with a breakdown of the process needed but still needed to resolve using a viewshed function
- We found a GDAL solution to running the viewshed analysis (insert hyperlink) but were unable to download the neccessary software on the lab computers
- We then tried to download and use a GRASS solution (insert hyperlink) but it just didn't work. 
