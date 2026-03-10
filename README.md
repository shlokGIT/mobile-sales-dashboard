
# Mobile Sales Dashboard (Power BI Project)

# Project Overview

This project is an interactive **Mobile Sales Dashboard** built using **Microsoft Power BI**.
The dashboard provides deep insights into mobile sales performance across different cities, brands, payment methods, and time periods.

It helps analyze:

* Total Sales Revenue
* Total Transactions
* Quantity Sold
* Monthly Sales Trends
* Brand Performance
* Customer Ratings
* Payment Method Distribution
* City-wise Sales Performance

---

# Key Features

✔ Interactive Filters (Brand, Mobile Model, Payment Method, Day Name)
✔ KPI Cards (Total Sales, Transactions, Quantity)
✔ City-wise Sales Map Visualization
✔ Monthly Quantity Trend Line Chart
✔ Payment Method Distribution (Pie Chart)
✔ Customer Ratings Analysis
✔ Brand-wise Sales Breakdown
✔ Day-wise Sales Trend

---

# Tools & Technologies Used

* Microsoft Power BI
* Power Query (Data Cleaning & Transformation)
* DAX (Data Analysis Expressions)
* Excel Dataset

---

# Dataset

The dataset includes:


![DATASET](https://github.com/shlokGIT/mobile-sales-dashboard/blob/main/Screenshot%20(413).png?raw=true)

---

# Business Insights 

* Identified top-performing brands by revenue.
* Analyzed which cities generate maximum sales.
* Determined most preferred payment method.
* Found monthly sales trend patterns.
* Analyzed customer satisfaction ratings.

---

#Project Objective

The objective of this dashboard is to simulate a real-world retail sales reporting system that helps management make data-driven decisions.

---

# DAX Measures Used
```
Total Sales = SUMX(Sales_Data,Sales_Data[units_sold] * Sales_Data[Price_Per_Unit])
```
```
- Total Transactions = COUNTROWS(Sales_Data)
```
```
- Total Quantity = SUM(Sales_Data[Price_Per_Unit])
```
```
- Average  = AVERAGE(Sales_Data[Price_Per_Unit])
```


---

# Author

Shlok Kumar Singh

B.Tech | Data Analyst Enthusiast

 SQL | Power BI | Excel | DAX




