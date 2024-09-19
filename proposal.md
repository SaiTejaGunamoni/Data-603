# PROJECT PROPOSAL

## Project Title: Predicting Solar Output Using Weather Data
Capstone Project under Dr Chaoji Wang - Fall 2024 Semester
- Author: Sai Teja Gunamoni
- GitHub: https://github.com/SaiTejaGunamoni

## Overview:

With the global shift towards renewable energy sources, precise solar power generation forecasting has become crucial for effective grid management and energy planning. Our capstone project attempts to address the inherent variability of solar power generation by creating a machine learning model to predict solar energy output using weather data.

With the analysis of historical solar farm data, including hourly power generation readings and associated weather variables like wind speed, cloud cover, temperature, and solar irradiance I'll try to identify critical weather parameters that have a major impact on solar output by using thorough data preprocessing, exploratory data analysis, and feature engineering.

I'll attempt to apply and contrast a variety of machine learning models, such as neural networks, ARIMA, LSTM, and Random Forest, Gradient Boosting, and Linear Regression. Cross-validation techniques will be employed to validate these models after they have been trained on a subset of the data. Metrics like Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R-squared values are used to assess performance.

## Dataset and Description:

#### Data Source: https://nsrdb.nrel.gov/data-viewer

With the help of weather data, solar output can be predicted using this dataset.  The information on solar output, the weather, the date, and the time was gathered from a variety of sources. Previous weather patterns and data are the foundation for the solar output projections. Utilizing the dataset, one can train a model that forecasts solar output according to meteorological conditions.

Time-series data for the United States and other countries at a 30-minute resolution can be found in the National Solar Radiation Database (NSRDB), a comprehensive collection of meteorological and solar irradiance data. It includes important variables like temperature, wind speed, and other meteorological parameters, as well as surface cells that span an area of about 4 km in size. Examples of these include global horizontal irradiance (GHI), direct normal irradiance (DNI), and diffuse horizontal irradiance (DHI).

### Research Questions
- Which algorithms are the most efficient for weather-derived predictions ?
- What weather features are the most influential in the ML algorithms?

## Variables in dataset:


•	DR_NO - Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.
    
•	DATE OCC - Date of crime occurrence (YYYY-MM-DD)

•	AREA - The LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21.

•	AREA NAME - The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for.

•	Rpt Dist No - Code that represents a sub-area within a Geographic Area.

•	Crm Cd - Indicates the crime committed.

•	Crm Cd Desc - Defines the Crime Code provided.

•	Vict Age - Indicates the age of the victim.

•	Vict Sex - F: Female M: Male X: Unknown
            
•	Premis Cd - The type of structure, vehicle, or location where the crime took place.

•	Premis Desc - Defines the Premise Code provided.

•	Weapon Used Cd - The type of weapon used in the crime.

•	Weapon Desc - Defines the Weapon Used Code provided.

•	LOCATION - Street address of crime incident rounded to the nearest hundred block to maintain anonymity.

•	LAT - Latitude Coordinate.

•	LON - Longitude Coordinate

•	Vict Descent - Descent Code: A - Other Asian B - Black C - Chinese D - Cambodian F - Filipino G - Guamanian H - Hispanic/Latin/Mexican I - American Indian/Alaskan Native J - Japanese K - Korean L - Laotian O - Other P - Pacific Islander S - Samoan U - Hawaiian V - Vietnamese W - White X - Unknown Z - Asian Indian 


## Techniques and Models:
- Neural Networks
- ARIMA
- LSTM
- Random forest
- Gradient Boosting
- Linear Regression 
- Decision Tree Classifier

## Expected Outcome:

This project offers a data-driven method for predicting solar output, which advances the rapidly expanding field of renewable energy forecasting. The developed model may enhance the integration of solar power into the electrical grid and optimize energy distribution strategies. It is useful for solar plant operators, grid managers, and energy traders.

## References:

- http://www.ncdc.noaa.gov/
- https://nsrdb.nrel.gov/data-viewer
- Oeda S, Kurimoto I and Ichimura T 2006 Time series data classification using recurrent neural network with ensemble learning Lecture Notes Comput. Sci. 4253 742-8
