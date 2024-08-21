## Sales Performance Analysis

### Project Overview
**Sales Performance Analysis** is a data-driven project aimed at empowering retail management to make informed decisions regarding product offerings. By developing an interactive dashboard, this project will visually represent monthly sales performance across various product segments and categories, enabling stakeholders to easily identify which areas are performing well and which require attention.

### Background
Mike Goodman, the Product Management Director at a retail products company, is tasked with evaluating the company’s product catalog. His goal is to determine which products to continue selling and which ones to phase out.

### Objective
The primary aim of this project is to create a comprehensive dashboard that displays monthly sales performance by product segment and category. This tool will assist the client in pinpointing segments and categories that have met or surpassed their sales targets, as well as those that have fallen short.

### Domain
**E-commerce**

### Dataset Overview
This analysis will utilize two key datasets: **Sample - Superstore** and **Sales_Target**.

#### Sample - Superstore
This dataset includes order data from 2014 to 2017 and contains the following fields:

| Field          | Description                                          |
|----------------|------------------------------------------------------|
| Row ID         | Observation Index                                   |
| Order ID       | Unique identifier for each order                    |
| Order Date     | Date when the order was placed                      |
| Ship Date      | Date when the order was shipped                     |
| Ship Mode      | Mode of shipment used for the order                 |
| Customer ID    | Unique identifier for each customer                 |
| Customer Name  | Name of the customer                                 |
| Segment        | Product segment (e.g., Home Office, Corporate, Consumer) |
| Country        | Name of the country                                  |
| City           | Name of the city                                    |
| State          | Name of the state                                   |
| Postal Code    | Postal code for the area                            |
| Region         | Specific region within the country                  |
| Product ID     | Unique identifier for each product                  |
| Category       | Product category                                    |
| Sub-Category   | Product subcategory                                 |
| Product Name   | Unique name of the product                           |
| Sales          | Total sales amount                                  |
| Quantity       | Quantity of products sold                           |
| Discount       | Discount applied to the product                     |
| Profit         | Financial gain from the sale                        |

#### Sales_Target
This dataset focuses on sales targets and includes the following fields:

| Field          | Description                                          |
|----------------|------------------------------------------------------|
| Category       | Product category                                    |
| No. of Records | Unique record count                                 |
| Order Date     | Date when the order was placed                      |
| Sales Target   | Target sales amount to be achieved                  |
| Segment        | Product segment (e.g., Home Office, Corporate, Consumer) |

### Analysis Tasks
1. Utilize the **Sample - Superstore** dataset.
2. Create a bullet chart incorporating Category and Segment dimensions along with Sales measures.
3. Integrate the **Sales Target** dataset to include the Sales Target measure.
4. Implement color coding in the chart to distinguish between Categories and Segments that are above or below target.
5. Add a year filter to the dashboard to allow users to select one, multiple, or all years for analysis.
