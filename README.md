# Telco Customer Churn Analysis Dashboard

## Project Overview:-
This project focuses on analyzing customer attrition (churn) for a telecommunications company. The goal is to identify why customers are leaving, calculate the financial impact of lost revenue, and provide actionable insights to improve customer retention.

**Key Objectives:**
* Identify high-risk churn segments.
* Analyze the relationship between contract types and loyalty.
* Track Revenue Loss and identify "High-Value" customers at risk.


## Dashboard Insights

###  Page 1: Executive Summary (The "What")
Provides a high-level view of the business health.
* **Key KPIs:** Average Monthly Revenue, Total Customers, Churn Rate (%), and Total Revenue Lost.
* **Service Impact:** Analysis of churn across Fiber Optic vs. DSL users.
* **Contract Trends:** Visualizing how month-to-month contracts correlate with higher churn compared to long-term commitments.

### Page 2: Customer Behavior (The "Why")
Dives into the demographics and tenure patterns.
* **Tenure Analysis:** Shows that new customers are most likely to churn within the first few months.
* **Demographics:** Churn distribution by Gender and Senior Citizen status.
* **Payment Methods:** Identifying "Electronic Check" as a high-churn payment category.

###  Page 3: Risk Assessment (The "Who")
A proactive look at customers that matter most.
* **High-Value Customer Tracking:** A focused table showing customers with high monthly charges and low tenure.
* **Retention Strategy:** Identifying specific IDs for the marketing team to target with loyalty offers.


##  Tools Used
* **Power BI:** Data Modeling, DAX (Data Analysis Expressions), and Visualization.
* **Power Query:** Data cleaning and transformation.
* **Excel/CSV:** Source data containing 7,000+ customer records.

## Data Schema & Methodology
* **Data Cleaning:** Handled missing values in "Total Charges" and formatted data types.
* **Logic:** Created a custom "High Value" category for customers paying above average monthly rates.
* **Interactivity:** Implemented cross-filtering across all pages via Slicers (Gender, Contract, Internet Service).

## How to Use
1. Download the `Telco-Customer-Churn.pbix` file.
2. Open it using **Power BI Desktop**.
3. Use the **Slicers** on the left to filter the data by Service or Contract type.
