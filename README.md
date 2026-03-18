# Instacart Basket Analysis

## 📌 Project Overview

This project analyzes grocery basket data to uncover customer purchasing patterns and segment customers based on buying behavior. The goal is to generate actionable insights that can support targeted marketing, product placement, and operational decision-making. As a marketing analyst at Instacart, I want to understand customer behavior by time, region, and segment so I can schedule campaigns and promotions more effectively and increase conversion while protecting margin.

## 🎯 Business Objectives

* Identify common purchasing patterns and frequently bought products
* Segment customers based on shopping behavior and order characteristics
* Support data-driven marketing and merchandising strategies

## 📂 Data Source

* Instacart Grocery Basket dataset
* Includes information on orders, products, departments, aisles, and customers

## 🛠️ Technical Highlights

- Cleaned and merged multiple datasets using pandas
- Performed exploratory analysis on customer and transaction behavior
- Built grouped summaries and visualizations to identify patterns
- Documented analysis workflow for reproducibility
  
## 🔍 Key Steps

1. Data loading and initial inspection
2. Data cleaning and handling missing values
3. Feature engineering (order frequency, reorder behavior, basket size)
4. Exploratory data analysis
5. Customer segmentation and pattern analysis
6. Visualization of key findings

## 📊 Key Insights 

* Customers place most orders during a consistent “peak window” (often mid-day/afternoon). This is useful for staffing, promos, and delivery capacity planning.
* A large portion of items in baskets are reordered products.
* A few departments (typically groceries like produce/dairy/beverages/snacks) account for most items ordered. This helps prioritize homepage placement, featured deals, inventory planning, and “top department” campaigns.

## 📈 Visualizations

* Bar Chart - Loyalty Level
* Heatmap - Customer profile by age group
* Histogram - Orders per hour of day


## 📁 Repository Structure

```
instacart-grocery-basket-analysis/
├── data/
├── notebooks/
│   └── instacart_analysis.ipynb
├── visuals/
├── README.md
```

## 🚀 Next Steps

* Benchmarking: Compare patterns with industry grocery e-commerce
* Validate segments by clustering and predict next month behavior
* Approach your segmentation by RFM (Recency, Frequency, Monetary). VIP, Loyal, Promising, At Risk, Casual

## Recommendations

* Daypart ad scheduling + offer design. Peak hours: prioritize conversion campaigns and higher-margin categories.
* Department bundles aligned to customer profiles. Create 3–5 bundles by department affinity and promote by segment.
* Retention strategy using improved loyalty segmentation (RFM). Replace single-variable loyalty with RFM segments.
  VIP/Loyal: early access to delivery slots + personalized recommendations

## 👩‍💻 Author

**Mary Kane**
Data Analyst | Bilingual (English–Spanish)
