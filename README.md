# Spotify Trend Analysis and Prediction

<p align = "justify">
The user has been a Spotify subscriber since 2015, primarily relying on the platform for all music needs. Recently, the user discovered that Spotify allows users to request their historical listening data, which sparked an interest in exploring listening trends over time. After submitting a request, the user received their historical data within two days. This dataset forms the basis for the analysis, which combines both exploratory and predictive methods. The objective of the analysis is to examine the user’s listening behavior throughout the years and to develop a predictive model that can forecast future listening trends and preferences on the platform.
</p>

## Overview
<p align = "justify">
This project seeks to analyze the user's historical listening patterns and leverage these insights to predict future listening behaviors. The dataset utilized for this analysis is derived from the user's historical listening data, obtained directly from Spotify.
</p>

## Libraries Used
<p align = "justify">
This analysis relies on the following R libraries for data manipulation, visualization, and predictive modeling:

- **dplyr**: For data manipulation and transformation.
- **ggplot2**: For data visualization.
- **lubridate**: For handling dates and times.
- **readr**: For reading CSV files.
- **forecast**: For time series forecasting.
- **scales**: For better visualization scaling.
- **rstantools**: For statistical modeling.
- **randomForest**: For predictive modeling using Random Forest algorithm.
</p>

## Data Preprocessing
<p align = "justify">
The data was provided in multiple CSV files spanning different years. The preprocessing steps include:

1. Merging all the CSV files into a single dataframe.
2. Converting timestamps into useful components such as date, hour, day of the week, and duration in minutes.
3. Handling missing or NA values where applicable.
</p>

## Exploratory Data Analysis (EDA)
<p align = "justify">
Exploratory Data Analysis (EDA) was conducted to understand the patterns and distributions within the data. The following steps were performed:
  
- **Trend Analysis**: Analyzing the user's listening frequency over time, identifying key peaks and trends.
- **Artist Preference**: Examining the most listened-to artists over the years.
- **Listening Habits**: Investigating listening behavior by time of day, day of the week, and seasonality.
- **Outliers and Anomalies**: Identifying any unusual listening patterns that may impact the predictions.
</p>

## Predictive Analysis
<p align = "justify">
To predict future listening behavior, several machine learning and time series forecasting techniques were applied:
  
- **Time Series Forecasting**: Using the historical listening data to predict the number of plays for each genre and artist over the next few months.
- **Random Forest Model**: A Random Forest algorithm was used to model user preferences based on historical data, including genre, artist, and listening time.
- **Evaluation**: The models were evaluated for accuracy using appropriate performance metrics, such as RMSE (Root Mean Squared Error) for the time series model and feature importance for the Random Forest model.
</p>

## Conclusion
<p align = "justify">
This analysis provides valuable insights into the listening behavior of a long-term Spotify user. By combining exploratory data analysis and predictive modeling, it is possible to forecast future listening habits and predict which artists, albums, or songs are likely to remain popular. The findings of this analysis can help refine music recommendations and optimize user engagement with the platform.
</p>
