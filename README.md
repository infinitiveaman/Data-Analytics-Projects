# Exploratory Data Analysis on Superstore Sales Dataset

This project focuses on performing a detailed exploratory data analysis (EDA) on the *Global Superstore* dataset using Python.  
The goal is to identify key business insights such as sales and profit trends, category performance, customer behavior, and regional contributions.

---

## Objectives
- Understand sales, profit, and discount patterns across different regions, categories, and segments.  
- Identify top-performing products and customers driving revenue.  
- Explore relationships between discounts, sales, and profit margins.  
- Visualize monthly sales trends and overall business performance.

---

## Tools and Libraries
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib  
- **Environment:** Google Colab

---

## Dataset
- Dataset used: *SampleSuperstore.csv* (available on [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final))  
- Contains order-level sales data with attributes such as region, category, profit, and discounts.  

You can upload the CSV file directly in the Colab notebook when prompted.

---

## Analysis Overview
1. **Data Cleaning and Preprocessing**  
   - Handled missing values, duplicates, and inconsistent data types.  
   - Converted sales and profit columns to numeric for analysis.  
   - Extracted month and year from order dates for trend analysis.  

2. **Exploratory Analysis**  
   - Category and region-wise sales and profit visualizations.  
   - Correlation heatmap to identify relationships among numeric features.  
   - Discount vs. profit scatter plot to understand discount impact.  
   - Monthly sales trend analysis with line plots.  

3. **Insights and Dashboard**  
   - Top-performing products and customers identified.  
   - Profit margin calculated across segments.  
   - Summary dashboard with total sales, total profit, average discount, and category-wise breakdowns.

---

## Key Insights
- The **West** region contributes the highest profit overall.  
- **Technology** category drives the largest portion of total sales.  
- High discounts (above 30%) tend to reduce overall profit margins.  
- A noticeable sales increase occurs during the last quarter of each year.

---

## How to Run
1. Open the notebook in **Google Colab**.  
2. Upload your `SampleSuperstore.csv` file when prompted.  
3. Run all cells sequentially.  
4. Scroll to the final section for summary metrics and visual insights.

---

## Conclusion
This analysis provides a clear understanding of retail performance and profitability patterns.  
The approach can be adapted for real-world business analytics tasks involving customer segmentation, sales forecasting, or performance reporting.

