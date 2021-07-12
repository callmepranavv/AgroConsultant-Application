# AgroConsultant Application

AgroConsultant - an intelligent system that would consider environmental parameters (temperature, rainfall, farm’s latitude, longitude, altitude and distance from the sea) and soil characteristics (pH value, soil type and thickness of aquifer and topsoil) before recommending the most suitable crop to the user.Crop recommendation is one of the most important aspects of precision agriculture.Precision agriculture seeks to define these criteria on a site-by-site basis in order to address crop selection issues. However, in agriculture, it is critical that the recommendations made are correct and precise, as errors can result in significant material and capital loss.

This application will assist farmers in increasing agricultural productivity, preventing soil degradation in cultivated land, reducing chemical use in crop production, and maximizing water resource efficiency.

# [Dataset]()
This dataset was build by augmenting datasets of rainfall, climate and fertilizer data available for India.

### [Attributes information:]()

* **N** - Ratio of Nitrogen content in soil
* **P** - Ratio of Phosphorous content in soil
* **K** - Ratio of Potassium content in soil
* **Temperature** -  temperature in degree Celsius
* **Humidity** - relative humidity in %
* **ph** - ph value of the soil
* **Rainfall** - rainfall in mm 

### [Experiment Results:]()
* **Data Analysis**
    * All columns contain outliers except for N.
 * **Performance Evaluation**
    * Splitting the dataset by 80 % for training set and 20 % validation set.
 * **Training and Validation**
    * GausianNB gets a higher accuracy score than other classification models.
    * GaussianNB ( 99 % accuracy score )
 * **Performance Results**
    * Training Score: 99.5%
    * Validation Score: 99.3%

 
Dataset
* https://www.kaggle.com/atharvaingle/crop-recommendation-dataset
