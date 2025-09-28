# Advanced Sales Analytics with Python and Google Looker Studio

Click on the below link to view the interactive dashboard:
**https://lookerstudio.google.com/reporting/d309043f-0a0c-42e1-b883-27ef3662b799**

## Project Description:

This project involves analyzing a comprehensive sales dataset to derive actionable insights and create impactful visualizations using Python and Google Looker Studio. The dataset represents customer transactions, product details, and payment information. The key objectives of this project include:

1.  **Deriving Key Insights:**
    Identifying top-performing products, analyzing category-wise trends, and comparing sales across different time periods to improve strategic decision-making.

2.  **Visualizing Data:**
    Creating interactive dashboards in Google Looker Studio for a clear and effective presentation of complex data.

3.  **Behavior Analysis:**
    Highlighting customer and sales patterns, such as weekend vs. weekday performance and payment behaviors, to support targeted marketing and sales campaigns.

## Pre-requisites:

Before starting this project, you should have the following knowledge and tools in place:

1.  **Basic Python Skills:**
    * Knowledge of Python and libraries such as Pandas for data manipulation and Matplotlib/Seaborn for data visualizations.
    * Experience in handling DataFrames and performing data cleaning and transformation tasks.

2.  **Google Looker Studio:**
    * Familiarity with Google Looker Studio for creating interactive dashboards and visualizations.
    * Knowledge of connecting data sources, blending data, and building dynamic reports.

3.  **Data Analysis Concepts:**
    * Understanding basic data analysis techniques, such as identifying trends, comparing time periods, and aggregating data to derive insights.
    * Familiarity with metrics like growth percentages, total sales, and performance benchmarks.

4.  **Tools & Technologies:**
    * **Python**: An IDE or environment (e.g., Jupyter Notebook, Google Colab) for running Python scripts.
    * **Google Looker Studio**: A Google account and access to Looker Studio for creating and sharing dashboards.

## Key Steps and Analysis

**Data Preparation:**

The project utilizes a pre-processed and merged dataset (`finaldataset.csv`) which combines information on orders, customers, products, and payments. All analysis was performed on this unified dataset, with data transformations and feature engineering (like creating a 'Day Type' column) handled directly within Python and Google Looker Studio.

**Analysis and Visualization:**

1.  **Top Product Analysis (Task 1):**
    * Identified the Top 5 selling products in the "Mobiles & Tablets" category for 2022 based on sales quantity.
    * Visualized the results using a sorted bar chart to clearly display the top performers.

2.  **Sales Decline Analysis (Task 2 & 5):**
    * Performed a comparative analysis of sales between 2021 and 2022 to find products with the largest decrease in sales.
    * This analysis was conducted for both the "Others" category (Top 20 products) and for all categories combined (Top 10 products).

3.  **Customer Checkout Behavior (Task 3):**
    * Filtered the dataset to identify a unique list of customers who completed the checkout process (`is_gross = 1`) but did not complete payment in 2022, creating a targeted list for marketing outreach.

4.  **Campaign Performance Analysis (Task 4):**
    * Evaluated the effectiveness of weekend sales promotions by comparing average daily sales on weekends vs. weekdays during Q4 2022, for each month and for the entire quarter.

5.  **Category Sales Trend Analysis (Task 6):**
    * Plotted a time series graph to visualize and compare the monthly sales trends of all product categories throughout 2022, identifying categories with the highest sales and growth.

6.  **Google Looker Studio Dashboards:**
    * Designed and published a multi-page, interactive dashboard to present the findings from all analytical tasks.
    * The dashboard allows for dynamic filtering and exploration, showcasing year-on-year trends, top-performing products, and sales patterns for easy stakeholder consumption.

## Tools and Technologies Used:

* **Python:**
    * Data processing and analysis with the **Pandas** library for cleaning, filtering, and transformation.
    * Data visualization using **Matplotlib** and **Seaborn** to generate insightful charts and graphs.
    * All Python code is documented in the [**Jupyter Notebook**](https://github.com/Abhipspk/Sales-Analysis/blob/eb9e0b014791d21dc3363223d4c4841c868392e3/Analysis.ipynb).

* **Google Looker Studio:**
    * Created a comprehensive and interactive dashboard with real-time filters and drill-down capabilities.
    * Used data blending and calculated fields to perform complex analysis directly within the dashboard.

## Key Deliverables:

1.  **Actionable Insights:**
    * Identified top products and categories driving revenue.
    * Highlighted trends and anomalies for inventory optimization and targeted promotions.

2.  **Interactive Dashboard:**
    * A live, shareable dashboard for real-time data exploration by stakeholders.
    * Easy-to-navigate visualizations that answer key business questions.

3.  **Customer Targeting Recommendations:**
    * Provided a specific list of customers for payment follow-ups, helping to optimize sales conversions.

## Impact:

The project empowers stakeholders with actionable insights and interactive visualizations, supporting strategic decisions in marketing, sales, and customer management. The Google Looker Studio dashboard makes the data easily accessible and interpretable, fostering data-driven strategies for better business outcomes.
