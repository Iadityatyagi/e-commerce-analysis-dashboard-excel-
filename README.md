# 📊 E-Commerce Sales Analysis Dashboard (Excel)

## Project Overview

Developed an end-to-end E-Commerce Sales Analysis Dashboard in Microsoft Excel. The project involved data cleaning, transformation, analysis, and visualization to generate actionable business insights from sales data.

## 🔧 Data Cleaning & Preparation

* Removed extra spaces using **TRIM()** function.
* Standardized **Date**, **Product**, **Status**, and **Order Status** fields.
* Corrected discount values by converting them into **Discount %** format.
* Identified and handled missing values.
* Filled blank **Order Amount** values using:

```excel
=(Quantity*Unit Price)-((Quantity*Unit Price)*Discount)
```

* Created a **Month** column using:

```excel
=TEXT(OrderDate,"MMM")
```

* Created **Sales Buckets** (Low, Medium, High) using **IF()** statements for segmentation analysis.

## 📈 Data Analysis

Calculated key business metrics including:

* Total Orders
* Total Revenue
* Average Order Value
* Delivered Orders
* Cancelled Orders
* UPI Revenue
* Mobile App vs Website Orders
* Category-wise Revenue

Used Excel functions such as:

* SUM()
* AVERAGE()
* COUNTIF()
* SUMIF()
* IF()
* TEXT()
* TRIM()

## 📊 Pivot Table Analysis

Created Pivot Tables to analyze:

* Category-wise Revenue
* State-wise Revenue
* Monthly Sales Trends
* Order Status Distribution
* Channel Performance (App vs Website)
* Payment Mode Analysis

## 📉 Interactive Dashboard

Designed an interactive dashboard using:

* Column Charts
* Pie Charts
* Doughnut Charts
* KPI Cards
* Pivot Charts

## 🔍 Key Insights Generated

* Best-performing product categories
* Top revenue-generating states
* Monthly sales trends
* Most preferred payment methods
* Order fulfillment performance
* Sales distribution by channel
* Revenue contribution analysis

## 🛠️ Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Data Cleaning Functions
* Dashboard Design & Visualization

## 🎯 Outcome

Transformed raw e-commerce transaction data into a clean, structured, and interactive dashboard that helps stakeholders monitor sales performance, identify trends, and make data-driven business decisions.


