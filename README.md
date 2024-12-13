
# Adventure Work Report (Power BI)

## Project Overview
The Adventure Work Report project is my first Power BI report, aimed at analyzing sales and returns data from the Adventure Works dataset. This project demonstrates the use of advanced data modeling, DAX calculations, and interactive dashboards to extract meaningful business insights. It includes multi-dimensional analysis such as product performance, customer behavior, and geographical trends.

## Tools and Technologies Used:
* **Power BI:** For creating visualizations, dashboards, and interactive reports.

* **Power Query Editor:** For data preprocessing and transformation.

## Dataset Information:
The dataset contains multiple tables related to Adventure Works:

* Fact Tables:

    * Sales Data

    * Returns Data

* Lookup Tables:

    * Calendar

    * Customer

    * Product Categories

    * Products

    * Product Subcategories

    * Territory
These tables were connected in the data model using primary and foreign key relationships.

## Analysis and Objectives
This project involved creating calculated fields and measures using DAX to gain detailed insights. Key calculations included:

**Calculated Columns:**

* Day of Week

* Weekend Indicator

* Customer Priority

* Income Level

* SKU Category

* Discounted Price

* Revenue

**Measures:** 

* Total Cost

* Total Customers

* Total Orders

* Total Profit

* Total Returns

* Total Revenue

* Weekend Orders

* Year-To-Date (YTD) Revenue

* Revenue Target

* Return Rate

* Quantity Sold vs. Returned

* Profit Target

* Previous Month Sales/Orders/Profit/Revenue/Returns

* Average Retail Price

* 90-Day Rolling Profit


## Key Insights and Outputs
1. Overall Metrics:

* Total Revenue: $24.9M

* Total Profit: $10.5M

* Total Orders: 25.2K

* Return Rate: 2.2%
2. Top Performers:

* Top Product: Water Bottle (3983 orders, 149 returns, Return Rate: 1.95%)

* Most Ordered Category: Tires and Tubes

* Most Returned Category: Shorts

* Top Revenue-Contributing Country: USA

* Top Customer: Mr. Maurice Shan

## Steps or Workflow
1. Data Preprocessing:

* Cleaned and transformed data using Power Query Editor tools.

2. Data Modeling:

* Built a data model in Power BI connecting fact and lookup tables.

3. DAX Calculations:

* Created calculated fields and measures for analysis.

3. Report Design:

* Developed a four-page interactive report including:

    * Executive Dashboard

    * Geographical Map

    * Product Detail

    * Customer Detail

## Challenges and Learnings

* Understanding the **filter context** and its behavior in complex scenarios.

* Managing **two-way relationships** and **active/inactive relationships** in the data model.

* Learning the workflow of advanced DAX functions.

* Overcoming challenges as this was my first Power BI project.
