# Elm Living Power BI Dashboard

## Overview

This project presents an interactive **Power BI dashboard** developed for **Elm Living**, a boutique furniture and décor retailer.
The dashboard provides insights into **sales performance, customer behavior, promotions, returns, and delivery efficiency** across stores.

## Objectives

* Analyze **store performance** across locations
* Identify **top-performing products and categories**
* Evaluate the impact of **promotions and online sales**
* Monitor **returns and delivery performance**
* Provide **time-based insights** (MoM & YoY trends)

## Key Features

### Sales & Trend Analysis

* Total Orders by Month
* Month-over-Month (MoM %)
* Year-over-Year (YoY %)

### Financial Insights

* Revenue YTD vs Running Cost YTD
* Revenue per Product

### Product Performance

* Revenue Growth Table with YoY %
* Category & Product-level filtering

### Returns Analysis

* Returned Orders by Product
* Identification of high-return items

### Promotions Analysis

* Revenue contribution from promotions
* Comparison: Promotional vs Non-promotional sales

### Delivery Performance

* Average Delivery Days KPI
* Top 5 Products with longest delivery times
* Top 5 Stores with longest delivery times

## Interactive Filters

* Age Group
* Gender
* Store
* Product / Category
* Order Type (Online vs In-store)
* Month & Year
* Promotion Type

## Data Model

The dashboard is built using a **star schema**:

* **Fact Table**

  * Fact_sales (Revenue, Orders, Delivery, Discount)

* **Dimension Tables**

  * Dim_Products
  * Dim_Stores
  * Dim_Orders
  * Calendar

* **Additional Tables**

  * Issues & Promotions
  * Online Orders
  * In Store Orders

## Key Calculations (DAX)

* Revenue (Adjusted with Discount)
* Total Orders
* MoM %
* YoY %
* Revenue YTD
* Running Cost YTD
* Avg Delivery Days

## Design & UI

* Custom **purple-themed background** aligned with brand
* Clean card-based layout with rounded visuals
* Consistent slicer placement across pages
* Interactive navigation using bookmarks

## Tools & Technologies

* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Data Modeling

## How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Interact with slicers and visuals
4. Navigate across pages for insights

## Author

**Karthik Velavan**

## Highlights

* End-to-end dashboard development
* Business-driven insights
* Interactive and user-friendly design
* Real-world retail analytics use case

