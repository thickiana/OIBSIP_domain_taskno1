# 🛍️ Retail Dataset Analysis

This project presents a comprehensive analysis of a retail dataset using Python and data analytics techniques. It was developed as part of the **Oasis Infobyte Internship Program (OIBSIP)** to demonstrate skills in data cleaning, exploration, and visualization.

## 📌 Project Objectives

The goal of this project is to explore and analyze retail data to extract meaningful business insights. Specific objectives include:

- **Descriptive Statistics**: Calculate basic statistics such as mean, median, mode, and standard deviation for key numerical features.
- **Time Series Analysis**: Explore and visualize sales trends over time using date-based aggregations.
- **Customer and Product Analysis**: Understand customer demographics (age, gender) and product category performance.
- **Visualization**: Present insights using clear visual tools such as bar charts, line plots, and heatmaps.
- **Recommendations**: Provide actionable recommendations for business improvement based on EDA results.

## **Dataset Overview**

The dataset contains detailed records of retail transactions, with each row representing a unique purchase. The key columns include:
- **Transaction ID**: Unique identifier for each transaction
- **Date**: Date of purchase
- **Customer ID**: Unique identifier for each customer
- **Gender**: Gender of the customer (e.g., Male, Female)
- **Age**: Age of the customer
- **Product Category**: Category of the product purchased (e.g., Electronics, Clothing, Beauty)
- **Quantity**: Number of units purchased
- **Price per Unit**: Cost per individual unit of the product
- **Total Amount**: Total cost for the transaction (`Quantity × Price per Unit`)

---

## 🔧 Tools used

- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical analysis
- **Matplotlib** and **Seaborn** – Data visualization
- **Google colab** – Interactive environment for analysis

---

## 📊 Key Insights

- Identification of top-performing product categories and customer segments.
- Discovery of sales trends and seasonal spikes using time series analysis.
- Understanding of customer age and gender distribution in relation to purchase behavior.
- Detection of high-value customers based on spending patterns.
- Summary statistics (mean, median, mode, etc.) for price, age, and quantity.

---

## 🧹 Data Cleaning Steps

- Converted the `Date` column to proper datetime format.
- checked for duplicates
- checked for missing values but None found
- Verified data types and consistency across the dataset.

---

## 📈 Visualizations Included

- **Bar charts** for product category performance and gender distribution.
- **Line plots** for monthly and weekly sales trends.
- **Heatmaps** to analyze feature correlations.
- **Histograms and boxplots** for understanding distribution and outliers.

---

## 🧠 Recommendations

Based on the analysis, here are a few actionable insights:

- **Targeted Marketing**: Focus campaigns on high-spending age groups and popular product categories.
- **Inventory Management**: Stock more of the high-performing products during peak months identified in the time series analysis.
- **Customer Engagement**: Develop loyalty programs aimed at frequent or high-value customers.
- **Pricing Strategy**: Review pricing for low-performing categories that may have high returns or low conversions.
  
## 📈 Visualizations Included
 Bar charts showing top-selling products and countries.
- Line plots of monthly sales performance.
- Heatmaps for correlation analysis.
- Boxplots to detect outliers in price and quantity.
