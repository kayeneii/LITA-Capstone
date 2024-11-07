# LITA-Capstone
This data analysis and report was created for the Ladies in Tech Africa (LITA).

[Overview](#overview)
[Dataset](#dataset)
[Methods](#methods)
[Findings and Recommendations](#findings-and-recommendations)
[Visualizations](#visualizations)
[Conclusion](#conclusion)

## Sales Performance Analysis for a Retail Store

### Overview
---
This project aims to analyze and report the sales performance of a retail store through the data provided, in order to uncover key insights such as the top-selling products, regional 
performance, and monthly sales trends. The goal is to communicate these insights in a manner that best informs the decisions pertinent to the Retail Store.


### Dataset
---
The dataset used in generating this report was the Sales Data.xlsx obtained from the _Ladies in Tech Africa_ Data Analysis Program. For more info, see [the Incubator Hub](http://www.theincubatorng.org/).


### Methods
---
The following tools were used in the creation of this report.
- **Microsoft Excel:** For data cleaning and preparation, initial exploration, and visualization.
  1. Data Cleaning and Preparation:
     - Data loading and inspection
     - Data cleaning and formatting

  2. Initial Exploration or Exploratory Data Analysis:
     This involved an exploration of the data to derive answers to questions such as,
     - What is the total sales by product?
     - What is the total sales by region?
     - What is the total sales by month?
     - What is the average sales by product?
     - What is the average sales by region?
     - What is the total revenue by region?
     - Who are the top 10 customers?
     - What is the percentage revenue by region?
     - What is the percentage revenue by product?

  3. Data Visualization: This was done using Pivot Tables to provide answers to the questions asked during the initial data exploration. 

       
- **Microsoft Power BI:** For,
  1. Further Data Processing:
     - Data loading and quality inspection
     - Data transformation

  2. Analysis:
    During the analysis, additional columns were created using DAX functions. A Custom Column;
    
     ```DAX
     1[Customer Id]
     ```

  and a Conditional Column, called No of Products.

    ```DAX
    If Product contains Hat Then 1
    Else If Product contains Socks Then 2
    Else If Product contains Jacket Then 3
    Else If Product contains Shoes Then 4
    Else If Product contains Shirt Then 5
    Else If Product contains Gloves Then 6
    Else 7
    ```
   
  3. Data Visualizations: Data visualization was created with the aid of Matrices, Line, Pie and Bar Charts.

   
- **GitHUb:** For,
  1. Portfolio Building
  2. Communication


### Findings and Recommendations
---
1. **Findings:** The following key findings were made following a thorough analysis of the Sales Data at the last entry in August 2024, 
   - The total product bi-annual sales stands at 345,000.
   - The total bi-annual revenue was 10.58 Million.
   - Total revenue generation was significantly poor in the first half of 2023, rising only briefly in February.
   - The same pattern is seen in 2024, with a massive drop in total revenue from 1 Million to 250,000 in March.
   - Sales are the best in February, with total revenue coming in at 1.25 Million in 2023 and 1.5 Million in 2024.
   - The annual revenue which was 250,000 at December 2023, shot up to 1 Million by January 2024.
   - The top 5 customers with customer ID: 1488, 1375, 1023, 1059, 1367.
   - The South generated the highest revenue at 4.67 Million.
   - The Hat came in as the best selling product over two years, followed by Shoes.

2. **Recommendations:** Based on the above findings, it is recommended that,
   - a further analysis be made to determine why the most sales are made in February;
   - a proper customer behavior analysis be conducted to better understand buying behavior;
   - the marketing and sales strategy be redesigned to properly reflect these customer behavior and interests;
   - top 5-10 customers be rewarded;
   - regions be incentivized to encourage higher revenue generation and sales quota.


### Visualizations
---
  ![Sales Data Report](https://github.com/kayeneii/LITA-Capstone/blob/main/Sales-Data-Viz.png)
      ![Regional Sales](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_tr%20per%20region.png)
      ![Product Sales](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_total%20product.png)
      ![2023 Sales](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_2023.png)
      ![2024 Sales](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_2024.png)
      ![Avg per Product](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_avg%20per%20product.png)
      ![Avg per Region](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_avg%20per%20region.png)
      ![Product Revenue](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_tr%20per%20product.png)
      ![Region per cent](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_region%20per%20cent.png)
      ![Product per cent](https://github.com/kayeneii/LITA-Capstone/blob/main/sales_product%20per%20cent.png)


### Conclusion
---
This concludes the sales performance analysis of a retail store's data as provided by the _Ladies in Tech Africa_ Data Analysis Program. Thank you for your time!
Until my next report, you may find me [here.](https://www.linkedin.com/in/kayeneii/) I look forward to hearing from you. 😄
