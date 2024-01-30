# Exploratory-Data-Analysis-of-Supermarket-Store-Branches
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/blob/main/Supermarket_Store_image.jpg)

## Table of Contents
- [Project Overview](#project-overview)
- [Tools](#tools)
- [About Dataset](#about-dataset)
- [Supermarket Store Branches EDA In Python](#supermarket-store-branches-eda-in-python)
- [Data Analysis and Visuals in PowerPoint Presentation Slides](#data-analysis-and-visuals-in-powerpoint-presentation-slides-front-page)
- [Factors That Influences The Emergence of Unicorns](#factors-that-influences-the-emergence-of-unicorns)
- [Recommendations Towards The Growth of Unicorn Companies](#recommendations-towards-the-growth-of-unicorn-companies)
- [View Power BI Dashboard Report](#view-power-bi-dashboard-report)

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

## Supermarket Store Branches EDA In Python:

Top 10 Stores With Most Item Sales       | Least 10 Stores With Most Item Sales        
:----------------------------------------:|:--------------------------------------------:|
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/a9d0e9c3-63bf-40d5-a2f9-4892c5b5f46c)| ![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/88152193-ebc5-41a5-afb0-0bb86d704b01)


Top 10 Stores With Most Item Sales By Store Area and Daily Customer Count       | Least 10 Stores With Most Item Sales By Store Area and Daily Customer Count       
:----------------------------------------:|:--------------------------------------------:|
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/10660ed6-60c7-4e37-8757-e8a1503f8b17)| ![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/4c354003-9b2c-4680-a685-db068409be3b)

Top 10 Stores With Most Daily Customer Count By Store Area and Item Sales       | Least 10 Stores With Most Daily Customer Count By Store Area and Item Sales       
:----------------------------------------:|:--------------------------------------------:|
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/fabea63d-2241-44ab-a523-466a11340f52)| ![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/3979af5d-6d93-4bf8-8449-93f03b37522c)

Top 10 Stores With Most Store Area By Store Sales and Daily Customer Count       | Least 10 Stores With Most Store Area By Store Sales and Daily Customer Count        
:----------------------------------------:|:--------------------------------------------:|
![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/dd7cfed4-8892-45c0-aaea-f617b3a836fa)| ![](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/assets/157266999/e2621780-5414-4716-83a2-0f420b75fb1f)

For a complete view of the processes, codes, visuals, key insights, observations and summary of the Exploratory Data Analysis (EDA) of this project in python Jupiter Notebook, please click [here](Supermarket_Stores_Branches_Sales_Analysis_Project.ipynb)

## Data Analysis and Visuals in PowerPoint Presentation Slides (Front Page):
![](Supermarket_Store_Front_Page.jpg)

1. From the presentation, the toal revenue accrued by all the supermarket store breanches is $53,178,770.
2. The total number of store branches is 897.
3. The total number of items in all store branches is 1,596,704.
4. Total number of daily customers that comes for shopping in all store branches is 704,570.
5. Total area of all stores (size) is 1,330,927.
6. For the top performing stores, store sizes and volume of item stock plays a slightly positive role in the number of customers that visit the stores daily and the profits they make. 
7. While some of the top stores with most daily sales has a higher daily customer count, others maintain strong slaes performance with lower customer count. indicating effective sales strategies by these stores with lower customer count but are ranked amongst the top selling stores.
8. The least performing stores by store size and daily customer count faces the challenge of attracting a substantial number of daily customers, which suggests potential room for improvement. Some stores with bigger store area still faces the challenge of weak daily customer count which affects their daily sales and which reflects a potential area for improvement.
9.  The top selling stores with the most daily customer count includes a combination of stores with varying store sizes which indicates an effective sales strategy and which also resulted in effectively drawing foot traffic.
10. The least selling stores with the least daily customer count indicates a challenge in customer attraction strategy. There are also stores with larger store sizes and volume of items but with a weak daily customer count which suggests mapping out an effective strategy for sales improvement.
11. For a better and deep understanding, a complete PowerPoint Prentation project in PDF of this project analysis can be viewed or downloaded [here](EDA%20OF%20SUPERMARKET%20STORE%20BRANCHES%20USING%20PYTHON%20-%20ODINAKACHUKWU%20UGOCHUKWU%20NNANNA.pdf)

## Recommendations towards Rectifying Defects In Store Branches Sales and On Making Them More Profitable
- The Store branches that are experiencing low sales have opportunities to improve. Strategies such as targeted marketing, inventory adjustments, or operational enhancements can boost sales.

- Stakeholders may need to evaluate the allocation of resources to these stores. They should consider whether additional staff support, staff trainings, an upward review of staff salaries and bonuses, or improvement in marketing efforts are needed to improve the performance of these stores.

- Some of the least performing stores exhibits low customer counts, this indicates that stakeholders need to look into potential areas for improvement in customer attraction and engagement possibly through targeted marketing, promotions, store layout enhancements or re-organization.

- There are stores with large store sizes but with lower daily customer counts and sales output, stakeholders should look at ways of improving sales strategies, ways of optimizing sales efficiency and ways of enhancing customer engagement.

- The stakeholders should also look for means of improving their systems and processes by leveraging technology in their stores day-to-day operations. A strong online presence in form of  a good branding of the business online, digital marketing, an e-commerce store, a platform to interact with customers through which they can analyze customer behavioural trend, understand their needs and design a strategy for customer retention online and offline.

- All these points can improve sales immensely.


## View Power BI Dashboard Report
Here’s a link to a [PowerPoint Presentation](https://github.com/Ugochukwuodinaka/Supermarket-Store-Branches-Analysis/blob/main/EDA%20OF%20SUPERMARKET%20STORE%20BRANCHES%20USING%20PYTHON%20-%20ODINAKACHUKWU%20UGOCHUKWU%20NNANNA.pdf) of this report which I created in the second phase of this project. This presentation slides displays clear visuals of this analysis.
