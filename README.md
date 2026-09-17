# Superstore Data Analysis & Business Insights

## Overview

This project analyzes the **Superstore 2026 dataset** using Python to explore sales performance, profitability, customer behavior, product performance, and operational patterns.

The goal is to turn raw sales data into clear business insights and highlight areas that may require further investigation.

## Objectives

* Clean and validate the dataset.
* Handle missing values and data-quality issues.
* Analyze sales and profitability.
* Explore product and customer performance.
* Analyze geographic and shipping patterns.
* Identify trends over time.
* Examine the relationship between discounts and profitability.
* Communicate findings through visualizations and business insights.

## Data Preparation

The dataset was inspected and cleaned before analysis.

Key steps included:

* Checking missing values and duplicates.
* Filling **11 missing Postal Code values** using City-based mapping.
* Validating Sales and Quantity values.
* Checking Discount values between 0 and 1.
* Validating Order Date and Ship Date relationships.
* Creating additional analytical features.

Legitimate outliers were retained because extreme transactions can represent meaningful business activity.

## Key Business KPIs

| KPI | Result |
| --- | --- |
| Total Sales | **$2,297,200.86** |
| Total Profit | **$286,397.02** |
| Overall Profit Margin | **12.47%** |
| Average Order Value | **$458.61** |
| Unprofitable Orders Ratio | **26.31%** |
| Profit from Orders with Discount >20% | **-$135,376.06** |

## Key Insights

* **Technology** generated the highest sales and profit among the three main categories.
* **Furniture** generated substantial sales but comparatively low profit.
* **Tables** recorded the largest sub-category loss at **-$17,725.48**.
* **Copiers** generated the highest sub-category profit at **$55,617.82**.
* **Consumer** customers generated the highest aggregate sales and profit.
* **2026** recorded the highest sales and profit among the analyzed years.
* **New York City** was a major contributor to both sales and profit.
* **Standard Class** generated the highest aggregate sales and profit among shipping modes.
* Orders with discounts above 20% generated **-$135,376.06** in total profit.
* **26.31% of orders were unprofitable**, highlighting the importance of order-level profitability analysis.

## Selected Analysis Screenshots

## Selected Analysis Screenshots

* **[View Business Insights](https://github.com/saraarnest333/Superstore-Sales-Profitability-Analysis/blob/main/images/Business-Insights.png)**
* **[View Category & Product Performance](https://github.com/saraarnest333/Superstore-Sales-Profitability-Analysis/blob/main/images/Category-Performance.jpg)**
* **[View Sales & Profit Analysis](https://github.com/saraarnest333/Superstore-Sales-Profitability-Analysis/blob/main/images/Sales-Profit-Analysis.jpg)**
  
## Project Files

| File | Description |
| --- | --- |
| `superstore_final_project.ipynb` | Complete Python analysis notebook |
| `Report.pdf` | Business Analysis Report |
| `images/` | Selected project screenshots |

## Tools & Skills

**Technical**

Python · Pandas · NumPy · Matplotlib · Seaborn · Data Cleaning · EDA · Data Visualization · Feature Engineering

**Analysis**

Business Analysis · Profitability Analysis · Customer Analysis · Sales Trend Analysis · Data Storytelling

## Project Structure

```text
Superstore-Data-Analysis/
├── README.md
├── Report.pdf
├── superstore_final_project.ipynb
└── images/
    ├── Sales & Profit Analysis.jpg
    ├── Category & Product Performance.jpg
    └── Business Insights.png

```

## Author

**Sara Arnest Ebrahim**

Computer Science Student | Junior Data Analyst
