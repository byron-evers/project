## Calculating thermal time indices and merging UAV data.

**Name**: Byron Evers<br/>
**Semester**: Spring 2019 <br/>
**Project area**: Agronomy


## Objective
Write a python function to calculate biometeorological time (BMT (T<sub>max</sub>, T<sub>min</sub>, L, _a_<sub>0</sub>,_b_<sub>0</sub> )), physiological days (Pdays (T<sub>min</sub>, T<sub>max</sub>, T<sub>opt</sub>)) and growing degree days (GDD (T<sub>min</sub>, T<sub>max</sub>, T<sub>base</sub>)) for several UAV collection dates.
Then, through a python function, merge UAV reflectance data, plot level phenotypic data and calculated values into one .csv file.


## Outcomes
The final outcome is to generate a .csv file that has UAV and plot level phenotype data merged buy plot_id with additional columns for calculated date times. 


## Rationale

Current phenotyping methods are labor intensive, hard to replicate, and have limited temporal resolution. UAVs equipped with multispectral sensors present a possible solution to obtain valuable time sensitive data. To use these data points in spatio-temporal models, crop phenology needs to be estimate. Past research papers have used a range of thermal time equations to estimate crop phenology (Saiyed et al 2009). However, there is still a need to compare evaluate these thermal predictors in relationship to reflectance data.

Over the last two growing season I have collected UAV reflectance data across several breeding nursery locations at several dates. Currently this data is being merged with plot level data with excel. This process is inefficient and introduces potential errors. I would like to stream line this process with Python. Additionally, having the ability to calculate several phenological development thermal times, with a Python function, will be useful for modeling purposes.


## Sketch

<img src="diagram.png" alt="sketch_image" width="500"/>

## References
Kyratzis Angelos C., Skarlatos Dimitrios P., Menexes George C., Vamvakousis Vasileios F., Katsiotis Andreas, 2017. Assessment of Vegetation Indices Derived by UAV Imagery for Durum Wheat Phenotyping under a Water Limited and Heat Stressed Mediterranean Environment. Frontiers in Plant Science V.8 P 1114

Saiyed, I., Bullock, P.R., Sapirstein, H.D., Finlay, G.J., Jarvis, C.K., 2009. Thermal time models for estimating wheat phenological development and weather-based relationships to wheat quality. Can. J. Plant Sci. 89, 429–439.

