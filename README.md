# Sales Data Analysis

## Description
This is a breakdown of sales data to identify trends and anomalies and gain insights that lead to recommendations. More detailed procedure and breakdown of thinking is in the code.

## Getting Started
To run this notebook, you will need to have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn

# A three part Approach: 

Data Cleaning: I cleaned the data by converting data types, and filling missing values in unit price with the mean to ensure that calculations do not result in errors. I then eliminated duplicates cautiously by making sure multiple entries with the same date and values would be grouped rather than dropped because there is no transaction ID to ensure that similar records are dropped.
I then created a new Month Year feature for later analysis.

Exploratory Data Analysis:
Provided a sales overview of category and business with Quantity and Value, looked at sales trends in time series and created a total value based on unit price * quanitity. 

Advanced Analysis:
I used a segmentation method to classify businesses, and categories based on their transaction frequency, quantity, and value with extensive recommendations through comments after the code.

My Strategic Insights and Recommendations: My recommendations are shown in a short Sales PowerPoint.

My Dashboard and Reporting: This is in done in the Tableau link attached. 
