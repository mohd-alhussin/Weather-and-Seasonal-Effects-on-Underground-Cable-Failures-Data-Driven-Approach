# Weather-and-Seasonal-Effects-on-Underground-Cable-Failures-Data-Driven-Approach


# MADRL-for-Taxi-Fleet-Management

This is the code repository for 'Weather and Seasonal Effects on Medium Voltage Underground Cable Joint Failures' paper we will provide the link to the paper soon.

## Code Structure 
1. Features and Clusters : containes that code that implements the Weather Feature Selection and K-means Clustering. 

	- Clusters.ipynb : Applys K-means clustering to the selected feature and comare the failure rates among the generated clusters.
	- Cloud.ipynb : Study the impact of clouds on faliure odds
	- Humidity.ipynb : Study the impact of humidity on faliure odds
	- Pressure.ipynb : Study the impact of pressure on faliure odds
	- Rain.ipynb : Study the impact of rain on faliure odds
	- Temp.ipynb : Study the impact of temperature on faliure odds
	- WindSpeed.ipynb : Study the impact of wind speed on faliure odds
	- Weather_Feature_selection.ipynb : Combine the selected features.
  


2. Forecasting : containes that code that implements the forecasting models.  

	- AutoEncoder.ipynb : Implements Auto-encoder forcasting model with 5 folds cross validation.
	- CNN.ipynb: Implements 1-D Convolutional forcasting model with 5 folds cross validation.
	- LSTM.ipynb : Implements LSTM forcasting model with 5 folds cross validation.
	- Fprophet.ipynb : Implements Facebook Prophet forcasting model with 5 folds cross validation.

3. Models: contains the  saved models' weights. 

4. Output: ontains the output csv file.


## Requirements 
The code the written in python and  following Libraries are required. 

	* Tensorflow
	* Matplotlib
	* seaborn
	* Prophet
  * sklearn
  * pandas






## Plots  

### Feature Selection
![Feature Selection](https://github.com/mohd-alhussin/Weather-and-Seasonal-Effects-on-Underground-Cable-Failures-Data-Driven-Approach/blob/main/ODDs.png)

### Clustering
![Clustering](https://github.com/mohd-alhussin/Weather-and-Seasonal-Effects-on-Underground-Cable-Failures-Data-Driven-Approach/blob/main/Clusters.png)
 
### Forecasting 
![Facbook Prophet Model](https://github.com/mohd-alhussin/Weather-and-Seasonal-Effects-on-Underground-Cable-Failures-Data-Driven-Approach/blob/main/Forecast.png)



