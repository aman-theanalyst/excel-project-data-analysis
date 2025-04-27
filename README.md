# Pizza Place Sales Analysis

"Pizza Sales - US Store -2015.xlsx" - This excel file conatin Cleaned data, all KPI's calculated and 2 DashBoards.  

## Problem Statement

The pizza restaurant has recently seen a decline in sales and plans to increase them by analyzing customer and order data.  
The management team aims to perform a thorough analysis of order data and consumer behavior to identify important trends, patterns, and areas for improvement.  


## Background

This project analyzes pizza sales data collected from January 2015 to December 2015.  
The dataset covers transactions from various pizza outlets across the United States.  
The goal is to discover trends and insights related to customer preferences, sales performance, and operational efficiency to help management make informed, data-driven decisions.  

## About The Dataset

This dataset contains 4 tables in CSV format.  
•	The **Orders table** contains the date & time that all table orders were placed  
•	The **Order Details table** contains the different pizzas served with each order in the Orders table, and their quantities  
•	The **Pizzas table** contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type  
•	The **Pizza Types table** contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients.  

Link of Dataset : https://www.kaggle.com/datasets/ankitrajmishra/pizza-place-sales-analysis?resource=download

## Data Structure & Initial Checks  

This dataset contains 4 tables : Orders table, Order Details table, Pizzas table and Pizza Types table with total of 48,620 rows.

![Entity Relationship Diagram](https://github.com/aman-theanalyst/excel-project-data-analysis/blob/main/ERD%20Diagram.png?raw=true)  

## KPI's   

    1.	Total Revenue   
    2.	Average Order Value    
    3.	Total Pizza Sold  
    4.	Total Orders   
    5.	Average Pizza’s per Order   


## Recommendation Analysis  
These are the question that we have to answer by analysing the dataset.  
  
    1. How many customers do we have each day? Are there any peak hours?  
    2. How many pizzas are typically in order? Do we have any bestsellers?  
    3. How much money did we make this year? Can we identify any seasonality in the sales?  
    4. Are there any pizzas we should take off the menu, or any promotions we could leverage?


## More Insight

We have aimed to uncover deeper insights and trends, presenting them in the form of a comprehensive dashboard.

    1.  "Weekly & Monthly Trend for total orders" :- This visualization will help identify patterns or fluctuations in order volumes.   

    2. "Hourly Trend for total orders" :- This visualization will help pinpoint peak hours or periods of increased order activity.    

    3. "% of sales by pizza category" :- This visualization will offer insights into the popularity of each category and their contribution to total sales.   

    4. "% of Sales by Pizza Size" :- This chart will provide insights into customer preferences for pizza sizes and their influence on overall sales.    

    5. "Total Pizzas Sold by Pizza Category" :- This visualization will enable a comparison of sales performance across various pizza categories.    

    6. "Top 5 Pizza by revenue" :- This chart will help identify the most profitable pizza options.     

    7. "Bottom 5 Pizza by revenue" :- This chart will help identify the least profitable pizza options.

    8. "Top 5 Best Sellers by total pizza quantity" :- This visualization will help identify the most popular pizza options.     

    9. "Bottom 5 Sellers by total pizza quantity" :- This visualization will help identify underperforming or less popular pizza options.  

    10. "Top 5 Pizza sold by orders" :- This chart will help identify the most popular pizza options based on sales volume.  
    
    11. "Bottom 5 Pizza sold by orders" :- This chart will help identify the least popular pizza options based on sales volume.  

## Recommendation To Owner

    1. Introduce Limited-Time Offers (LTOs) or Seasonal Specials:
    Offer discounts on these special pizzas or bundle them with side items (e.g., "Get a free drink with any seasonal pizza purchase"). Promote these offers heavily on social media to reach a broader audience.

    2. Loyalty Programs and Rewards:
    Offer points for every purchase that can be redeemed for discounts, free items, or exclusive offers. A digital loyalty app could make it easier for customers to track their rewards and encourage repeat visits.

    3. Targeted Promotions Based on Customer Preferences:
    Send personalized offers via email or SMS, such as "Get 20% off your favorite The Classic Deluxe Pizza this week!"

    4. Upselling and Cross-selling Strategies:
    Train staff to suggest complementary items during the ordering process, like offering a discount on soda with a large pizza.

## DashBoard Screenshots  

![DashBoard 1](https://github.com/aman-theanalyst/excel-project-data-analysis/blob/main/Dashboard%201.png?raw=true)

![DashBoard 1](https://github.com/aman-theanalyst/excel-project-data-analysis/blob/main/Dashboard%202.png?raw=true)
