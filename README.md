# LITA-Capstone
This data analysis and report was created for the Ladies in Tech Africa (LITA).

## Sales Performance Analysis for a Retail Store

### Overview
---
This project aims to analyze and report the sales performance of a retail store through the data provided, in order to uncover key insights such as the top-selling products, regional 
performance, and monthly sales trends. The goal is to communicate these insights in a manner that best informs the decisions pertinent to the Retail Store.

### Dataset
---
The dataset used is the Sales Data.xlsx [Download Here] obtained from the 'Ladies in Tech Africa' Data Analysis Program. For more info, please check out the Incubator Hub.

### Methods
---
The following tools were used in the creation of this report.
- Microsoft Excel: For data cleaning and preparation, initial exploration, and visualization.
  1. Data Cleaning and Preparation:
     - Data loading and inspection
     - Data cleaning and formatting

  2. Initial Exploration or Exploratory Data Analysis:
     This involved an exploration of the data to derive answers to questions such as,
     - What is the total sales by product?
     - What is the total sales by region?
     - What is the total sales by month?
     - What is the average sales by product?
     - What is the total revenue by region?
     - Who are the top 10 customers?

  3. Data Visualization

- Microsoft Power BI: For,
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

    
  4. Visualization:

- GitHUb: For,
  1. Portfolio Building
  2. Communication

### Findings and Insights
---
Following an initial exploration of the Sales Data, the following findings were made:
- Total Sales by Product
- Total Sales by Region
- Total Sales by Month
- Average Sales by Product
- Total Revenue by Region

### Visualizations
---
![Sales Data Report](https://github.com/kayeneii/LITA-Capstone/blob/main/Sales-Data-Viz.png)

