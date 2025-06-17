# Store Trial & Customer Insights Project

## Overview
This project analyzes retail transaction and customer data to identify trends, inconsistencies, and customer segments. The goal is to develop actionable insights and recommendations to improve sales performance and customer engagement.

## Key Objectives
- Analyze transaction and customer data for trends and inconsistencies.
- Develop metrics to examine sales drivers.
- Segment customers based on purchasing behavior.
- Statistical testing for significant differences in purchasing behavior.
- Create visualizations and prepare findings for strategic recommendations.

## Data Sources
1. **Transaction Data**: Includes details like date, store number, loyalty card number, transaction ID, product details, quantity, and total sales.
2. **Customer Data**: Contains loyalty card numbers, lifestyle stages, and premium customer classifications.

## Methodology
1. **Data Examination**: Clean and explore transaction and customer data for missing values, duplicates, and data types.
2. **Merging Datasets**: Combine transaction and customer data using loyalty card numbers.
3. **Statistical Analysis**: Calculate key metrics such as total sales, unique customers, and average transactions per customer.
4. **Customer Segmentation**: Split lifestyle stages into age groups and social status for deeper analysis.
5. **Visualization**: Generate plots to illustrate trends and insights.

## Key Steps
### 1: Data Cleaning & Exploration
- Cleaned duplicates and nulls.
- Parsed dates, calculated price per unit, and analyzed pack size distribution.

### 2: Trial Evaluation
- Aggregated monthly sales metrics: total sales, customer count, transactions/customer.
- Used **Pearson correlation** to select best control stores.
- Compared trial vs control store performance during trial months.

### 3: Customer Segmentation
- Grouped customers by frequency and spending levels.
- Identified top contributing customer groups and purchasing patterns.

### 4: Sales Drivers & Visualization
- Analyzed impact of **pack size**, **lifestage**, and **premium status** on sales.
- Created visualizations to support insights.

### 5: Statistical Testing
- Performed **ANOVA** using `statsmodels` to test for significant differences in purchasing behavior.

## Tools & Libraries
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib/Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive analysis and documentation.

## Sample Business Insights
- Store 88 showed a significant uplift in sales and customers during the trial.
- Premium and frequent buyers drive higher revenue.
- Larger pack sizes correlate with repeat purchases.
- Tailored marketing strategies can be developed based on segment behavior.

## Recommendations
- Target high-value customer segments with personalized promotions.
- Optimize inventory based on product trends.
- Expand to regions resembling Store 88's profile.
- Promote larger packs to increase customer retention.

## Author
Mohamed Khalifa Abouzid  
mohamedkhalifa10110@gmail.com
