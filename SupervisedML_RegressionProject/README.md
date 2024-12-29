
# Air Quality Data Analysis  

This project involves analyzing air quality data from Thrissur CAAQMS for the month of April 2024. It uses Python libraries such as pandas, seaborn, matplotlib, and machine learning models to explore, preprocess, and evaluate the dataset.  

## Overview  
The project analyzes air quality index (AQI) data and pollutants such as PM10, PM2.5, SO2, CO, NO, NO2, NOX, NH3, and O3. It includes:  
1. Data exploration and visualization.  
2. Preprocessing and handling missing data.  
3. Machine learning models to predict AQI values.  
4. Evaluation of model performance using metrics like R² score and mean squared error (MSE).  

## Dataset Description  
The dataset contains the following columns:  
- `PARAMETERS`: Date of the reading.  
- `PM10`, `PM25`, `SO2`, `CO`, `NO`, `NO2`, `NOX`, `NH3`, `O3`: Air pollutant levels.  
- Other parameters such as `WS` (wind speed), `WD` (wind direction), `TC` (temperature), and `RH` (relative humidity).  
- `AQI`: Air Quality Index.  

## Methods and Models
Data Preprocessing:

Handling null values.
Standardization of numerical features using StandardScaler.
Visualization:

Seaborn and Matplotlib used for graphical representation of trends and distributions.
Models:

Linear Regression
K-Nearest Neighbors (KNN) Regressor
Decision Tree Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
Evaluation Metrics:

Mean Squared Error (MSE)
R² Score
## Results
The analysis identified pollutant patterns and evaluated regression models. The best-performing model for AQI prediction was Decision Tree Regressor, achieving an R² score of 1.
