# Exploratory-Data-Analysis-of-Supermarket-Store-Branches
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/blob/main/Supermarket_Store_image.jpg)

## Project Overview
### Introduction:
   
Supermarket chains operate multiple branches across various locations to cater to diverse customer needs and preferences. This project aims to leverage data analysis techniques to optimize the operations and performance of supermarket store branches. By analyzing key metrics and factors affecting branch performance, this study seeks to provide actionable insights for improving efficiency, profitability, and customer satisfaction.

### Problem Statement:
- In the competitive landscape of supermarket retail, ensuring optimal performance of individual store branches is crucial for sustained profitability and customer satisfaction.
- Understanding the multifaceted factors influencing branch performance and identifying key performance indicators (KPIs) can be challenging.
- This project aims to address these challenges by:
     - Analyzing trends, patterns, and factors affecting branch performance metrics such as sales, foot traffic, inventory turnover, and customer satisfaction.
     - Leveraging data-driven insights and predictive modeling techniques.
     - Developing actionable strategies and interventions to optimize operations, enhance profitability, and elevate the overall customer experience across supermarket store branches.
  
### Objectives:

- Identify key performance indicators (KPIs) for supermarket store branches.
- Analyze trends and patterns in branch performance metrics such as sales, foot traffic, inventory turnover, and customer satisfaction.
- Explore factors influencing branch performance, including location demographics, competition, store layout, product assortment, pricing strategies, and promotional activities.
- Develop predictive models to forecast sales, demand for specific products, and customer behavior at branch levels.
- Recommend strategies and interventions to optimize operations, enhance profitability, and improve customer experience across supermarket store branches.

### Tools:
1. Python (Was used for Data Cleaning, profilling and Exploratory Data Analysis)
   - The following Python Features were incorporated:
      1. Jupiter Notebook
      2. Numpy
      3. pandas
      4. Visualization
          - Matplotlib
          - Seaborn
          - Plotly
      5. Integration With Other tools
         
2. Microsoft PowerPoint(Was used to create analysis report presentation in slides for this project)

### Methodology (Python):
- Conduct descriptive analytics to summarize and visualize branch performance metrics, including sales trends over time, geographic distribution of customers, popular products, and peak shopping hours.
  
- Perform exploratory data analysis (EDA) to identify correlations, outliers, and patterns in the data, using techniques such as clustering, factor analysis, and association rule mining.

### Statistical Analysis:

- Calculate descriptive statistics, including mean, median, standard deviation, and correlation coefficients, to quantify store branches sales activity.


### Results and Insights:

- Provide actionable insights and recommendations for supermarket management to optimize branch operations and performance.

- Identify high-performing branches and best practices that can be replicated across the chain.

- Suggest improvements in product assortment, pricing strategies, promotional campaigns, staffing levels, and store layout to enhance customer satisfaction and loyalty.

- Propose targeted marketing strategies and personalized recommendations based on customer segmentation and behavioral patterns.

- Highlight opportunities for expansion, relocation, or consolidation of branches based on market demand, competition, and profitability.


### About Dataset:
The primary dataset used in this analysis is the "Stores.csv" file. These dataset was released by [Quantum Analytics](https://www.quantumanalyticsco.org/). The Data Dictionary can be viewed or downloaded [here](Stores.csv). In the dataset, you’ll get data of different stores of a supermarket company as per their store IDs which for ease have been converted to positive integers.

**Store ID:** (Index) ID of the particular store.

**Store_Area:** Physical Area of the store in yard square.

**Items_Available:** Number of different items available in the corresponding store.

**DailyCustomerCount:** Number of customers who visited stores on average over a month.

**Store_Sales:** Sales in (US $) that stores made

### Conclusion:

- Summarize key findings, insights, and recommendations from the data analysis project.

- Emphasize the importance of data-driven decision-making in optimizing supermarket store branch operations and achieving business objectives.

- Outline potential future research directions and areas for continuous improvement in leveraging data analytics for retail management.



## Exploratory Data Analysis on Supermarket Store Branches' Sales Data

### EXPLORATORY DATA ANALYSIS STEPS
1. Importing the required Libraries for EDA
2. Acquiring the dataset
3. Data Preparation
4. Data Profiling
5. Data Cleaning
   
     a. Dropping Duplicates
   
     b. Removing Missing Values
7. Finding Outliers
8. Finding Correlations
9. Visualizations
10. Observations and Summary
11. Recommendations

Importing the required Libraries for EDA
```
import pandas as pd
import os
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import plotly.express as px
```
Assign df as pandas DataFrame
```
df = pd.DataFrame()
```
Acquire the dataset
```
df = pd.read_csv(r"stores.csv")
```
View Pandas DataFrame
```
df
```
![image](https://github.com/Ugochukwuodinaka/Exploratory-Data-Analysis-of-a-Supermarket-Store-Branches/assets/157266999/c271abd0-ec1a-4e6c-8d67-9a189785b115)

View first 10 rows of data
```
df.head(10)
```
View last 10 rows of data
```
df.tail(10)
```
#### DATA PROFILING STEPS
1. Data type
2. Quantile statistics (central tendecies)
3. Length (length and shape of the dataset)
4. Discrete values
5. Uniqueness (unique values)
6. Occurence of null values and etc.

