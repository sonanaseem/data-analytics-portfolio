# Clustering Project: Weather Dataset Analysis

## Overview
This project demonstrates clustering techniques applied to a **minute-level weather dataset** to identify patterns and group similar data points. The dataset contains various meteorological features such as air pressure, air temperature, wind direction, and humidity, providing insights into weather behavior over time.

## Objectives
- Clean and preprocess the dataset by handling missing and duplicate values.
- Apply clustering techniques to group data based on weather characteristics.
- Visualize the clusters to interpret the results and uncover patterns.

## Dataset
**Source**: The dataset used in this project is `minute_weather.csv`.  
**Features**:  
- `air_pressure`: Atmospheric pressure (in hPa).  
- `air_temp`: Air temperature (in °C).  
- `avg_wind_direction`: Average wind direction (in degrees).  
- `avg_wind_speed`: Average wind speed (in m/s).  
- `max_wind_direction`, `max_wind_speed`: Maximum wind metrics.  
- `min_wind_direction`, `min_wind_speed`: Minimum wind metrics.  
- `rain_accumulation`, `rain_duration`: Rainfall metrics.  
- `relative_humidity`: Humidity level (%).  

## Steps
1. **Data Cleaning**  
   - Removed rows with missing values.  
   - Dropped unnecessary columns such as `rowID` and `hpwren_timestamp`.  
   - Checked and removed duplicate rows.

2. **Feature Selection**  
   Selected relevant features for clustering:  
   - `air_pressure`, `air_temp`, `avg_wind_direction`, `avg_wind_speed`, `max_wind_direction`, `max_wind_speed`, `min_wind_direction`, `min_wind_speed`, `rain_accumulation`, `rain_duration`, `relative_humidity`.

3. **Elbow Method for Optimal Clusters**  
   Used the **elbow method** to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).  

4. **Clustering with K-Means**  
   Applied the **K-Means algorithm** to group data points into clusters.

5. **Visualization**  
   Visualized the clusters using **Seaborn** and **Matplotlib** to interpret patterns and relationships.

## Results
- **Optimal Clusters**: Identified using the elbow method.
- **Clusters Formed**: Data points grouped into distinct clusters based on their weather features.  
- **Insights**: Observed weather patterns such as similarities in temperature, humidity, and wind conditions among data points.

## Tools & Technologies
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  

## Conclusion
This project showcases the power of clustering techniques in analyzing and deriving insights from meteorological data. The clusters provide a clear segmentation of weather patterns, paving the way for further analysis and applications.

## Future Work
Explore other clustering algorithms such as DBSCAN or Hierarchical Clustering.
Incorporate time-series analysis for better temporal insights.
Develop predictive models to forecast weather based on cluster features.
## License
This project is licensed under the MIT License.
