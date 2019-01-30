
## Merging UAV and plot level data

**Name**: Byron Evers<br/>
**Semester**: Spring 2019 <br/>
**Project area**: Agronomy


## Objective
Write a python function to calculate biometeorological time (BTMT), physiological days (Pdays) and growing degree days (GDD) for several UAV collection dates.
Then, through a python function, merge UAV reflectance data, plot level phenotypic data and calculated values into one .csv file.

Currently UAV data is obtained in several .csv files as reflectance values of an individual band and as several vegetative indices. Furthermore, plot level 

Write a python function to automate the calculation of daily growing degree days using maximum and minimum daily air temperature.

## Outcomes
The final outcome is to generate a .csv file that has UAV and plot level phenotype data merged buy plot_id with additional columns for calculated date times. 


## Rationale
Current phenotyping methods are labor intensive, hard to replicate, and have limited temporal resolution. UAVs equipped with multispectral sensors present a possible solution to obtain valuable time sensitive data. In order to use these data point in spatio-temporal models crop phenology needs to be estimated through weather parameters. Past research papers have used a range of themral time equations to estimate crop phenology. Furthermore, Saiyed (et al 2009) have compared several of these thermal time predictors and found variation in accuracy depending on development stage.  However, there is still a need to compare evaluate these thermal predictures in relationship to reflectance data. 

Over the last two growing season I have collected UAV reflectance data across several KS Wheat breeding nursery locations at several dates. Additionally, several vegetative indices have been calculated and extracted. Currently this data is being merged with plot level data with excel. This is a time consuming process that introduces potential errors which I would like to stream line with the help of Python. Additionally, having the ability to calculate several phenological development thermal times, with a Python function, will be useful for modeling purposes. 

## Sketch

<img src="diagram.png" alt="sketch_image" width="500"/>

## References
Kyratzis Angelos C., Skarlatos Dimitrios P., Menexes George C., Vamvakousis Vasileios F., Katsiotis Andreas 2017Assessment of Vegetation Indices Derived by UAV Imagery for Durum Wheat Phenotyping under a Water Limited and Heat Stressed Mediterranean Environment. Frontiers in Plant Science V.8 P 1114




