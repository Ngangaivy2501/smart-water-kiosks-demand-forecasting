Smart Water Kiosks Demand Forecasting

 Project Overview

Optimizing Smart Water Kiosks Operations Through Demand Forecasting in Kilifi County

This data science project focuses on improving the operations of smart water kiosks in Kilifi County through data analysis and demand forecasting.

Smart water kiosks use prepaid cards to record water transactions, including the time of purchase and volume of water sold. However, fixed refill schedules can result in some kiosks running out of water while others still have substantial amounts remaining.

This project applies data analysis and machine learning techniques to identify demand patterns and develop a model that can help predict water demand and support more efficient refill scheduling.


Objectives

The main objectives of this project are to:

- Analyze historical smart water kiosk transaction data.
- Identify patterns and trends in water demand.
- Explore factors that influence water consumption.
- Perform data cleaning and exploratory data analysis.
- Develop and compare machine learning models for demand prediction.
- Identify the most suitable model for predicting liters of water sold.
- Provide insights that can support improved kiosk refill scheduling.

Dataset

The dataset contains information related to smart water kiosk operations and environmental conditions.

Key variables include:

- Tank capacity
- Water level before refill
- Price per liter
- Total sales
- Temperature
- Rainfall
- Truck arrival delays
- Daily population served
- Water quality
- Hour of transaction
- Kiosk location
- Payment method
- Refill status
- Sensor status
- Holiday and weekend indicators
- Day of the week
- Month

The target variable used for the final regression model is:

"liters_sold"

Data Preparation

The dataset was prepared before modeling through several preprocessing steps, including:

- Checking for missing values
- Identifying and handling outliers
- Converting variables into appropriate data types
- Creating time-related features
- Encoding categorical variables
- Preparing numerical features for machine learning
- Splitting the data into training and testing sets

Exploratory Data Analysis

Exploratory Data Analysis was performed to understand relationships and patterns within the data.

Visualizations included:

- Distribution plots
- Boxplots
- Correlation heatmaps
- Sales and demand trends
- Categorical frequency plots
- Branch/location comparisons

These visualizations helped identify important patterns and relationships between water demand and operational, environmental, and temporal factors.

Machine Learning

Several regression approaches were considered for predicting water demand.

The final project focused on Random Forest Regression because of its ability to model complex relationships between multiple features and the target variable.

Final Target

"liters_sold"

Model

Random Forest Regressor

The model was trained using operational, environmental, temporal, and categorical features.

Model evaluation was performed using unseen test data to assess how well the model could generalize to new observations.


 Random Forest Features

The final model incorporated features such as:

- Tank capacity
- Water level before refill
- Price per liter
- Total sales
- Temperature
- Rainfall
- Truck arrival delay
- Daily population served
- Water quality
- Hour
- Kiosk location
- Payment method
- Refill status
- Sensor status
- Holiday status
- Weekend status
- Day of the week
- Month

Results

The developed model demonstrated the potential of machine learning for predicting water demand from historical kiosk data.

The predictions can be used to support:

- Better refill scheduling
- Reduction of stock-out situations
- More efficient water distribution
- Identification of high-demand periods
- Improved operational planning

The project also demonstrates how historical transaction data can be transformed into actionable insights for resource management.


Technologies Used

- Python
- P
