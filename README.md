# Beijing-O3-Forecasting
ADS 506 Fall 2023 Team 5 Final Project: Shailja Somani &amp; Caleb McCurdy

**-- Project Status: Completed**


## Installation
To follow the steps used in this project, begin by executing the following:

git init

git clone https://github.com/shailja-somani-0/ADS-506-Team-5.git


## Contributors
Authors: Shailja Somani, Caleb McCurdy


## Methods
Data Exploration

Data Pre-Processing

Data Visualization

Data Modeling (training, testing, validation, metrics)

## Technologies
Microsoft Excel

Google Docs

Google Slides

R Applications (RStudio)


## Abstract
Using daily ground-level ozone forecast predictions, we can allow for public health agenices to warn Beijing residents to take precautions on days with high O3 pollution. These warnings can improve the overall public health through minimization of related ramifications. Additionally, the agriculture industry may use these predictions to make decisions with plant survival in mind.


## Problem Statement
The purpose of this project is to develop a forecast model that predicts the ground-level ozone levels in Beijing, China. This can be achieved by learning from a time series of O3 values with various external factors. First, we want to gain a better understanding of the time series data which can be achieved via exploratory data analysis. This will allow us to make decisions on how to proceed and learn which predictors may have greater influence on O3 levels. After later steps are taken such as preprocessing and model training, we will be able to make a recommendation on which forecast model to implement. Using this model, the public can gain a better sense of when this specific type of air pollution is worst and be better prepared. Specifically, we can make predictions on when the ground level ozone is above public health standard.


## Data Sources
The dataset used was collected hourly at the Nongzhanguan nationally-controlled air-quality monitoring site in Beijing from March 2013 until February 2017 (Chen, 2019). The data includes six main air pollutants and six meteorological variables and was downloaded from the UCI Machine Learning Repository with public availability using the following link: https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data (Chen, 2019). The data was downloaded as a zip file with 12 CSV files, one for each of 12 air-quality monitoring sites in Beijing, but we elected to use only the Nongzhanguan file as it was the monitoring site with the least amount of null values for hourly O3 levels. The CSV for the Nongzhanguan site is 2.8 MB with 35,064 records (hourly reports).


## References
Chen, Song. (2019, Sep 19) Beijing Multi-Site Air-Quality Data. UC Irvine Machine Learning Repository. Retrieved Nov 9, 2023, from https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data. 

Effects of Ground Level Ozone. (n.d.) Iowa Department of Natural Resources. Retrieved Nov 9, 2023, from https://www.iowadnr.gov/Environmental-Protection/Air-Quality/Air-Pollutants/Effects-Ozone. 

Exploring Air Pollutants in Beijing. (n.d.). Kaggle.com. Retrieved December 10, 2023, from 		https://www.kaggle.com/code/sid321axn/exploring-air-pollutants-in-beijing. 

Li, X., Peng, L., Yao, X., Cui, S., Hu, Y., You, C., Chi, T. (2017). Long short-term memory neural network for air pollutant concentration predictions: Method development and evaluation. Environmental Pollution. https://doi.org/10.1016/j.envpol.2017.08.114.

Ozone Effects on Plants. (2020, Jul 22) National Park Service. Retrieved Nov 9, 2023, from https://www.nps.gov/subjects/air/nature-ozone.htm. 

Pak, U., Kim, C., Ryu, U., Sok, K., & Pak, S. (2018). A hybrid model based on convolutional neural networks and long short-term memory for ozone concentration prediction. Air Quality, Atmosphere & Health, 11(8), 883–895. https://doi.org/10.1007/s11869-018-0585-1.

Reddy, V., & Yedavalli, P. (n.d.). Deep Air: Forecasting Air Pollution in Beijing, China. 
https://www.ischool.berkeley.edu/sites/default/files/sproject_attachments/deep-air-forecasting_final.pdf. 

Reitze, A. W. (2015). The National Ambient Air Quality Standards for Ozone. SSRN Electronic Journal. https://doi.org/10.2139/ssrn.2692876.

US EPA, O. (2016, March 21). Ozone Pollution and Your Patients’ Health. US EPA. 		
https://www.epa.gov/ozone-pollution-and-your-patients-health/what-ozone#:~:text=Ozone%20(O3)%20is%20a%20highly. 

TOAR: China is Hot Spot of Ground-Level Ozone Pollution. (2018, Aug 29) National Oceanic and Atmospheric Administration (NOAA) Chemical Sciences Laboratory. Retrieved Nov 9, 2023, from https://csl.noaa.gov/news/2018/244_0829.html. 

Wang, W., Parrish, D. D., Wang, S., Bao, F., Ni, R., Li, X., Yang, S., Wang, H., Cheng, Y., & Su, H. (2022). Long-term trend of ozone pollution in China during 2014–2020: distinct seasonal and spatial characteristics and ozone sensitivity. Atmospheric Chemistry and Physics, 22(13), 8935–8949. https://doi.org/10.5194/acp-22-8935-2022. 


## Project and Presentation
[Project Report](https://github.com/shailja-somani-0/ADS-506-Team-5/files/13644282/Team_5_Final_Paper.pdf)


## Acknowledgments
A special thanks to our University of San Diego Professor Erin Cooke, M.S. 
