# Bicycle Business Profitability 
# Exploratory RFM and Customer Segmentation Analysis

## Goal of the Project
The purpose of this project is to increase profitability by identifying and targeting high-value customers through RFM (Recency, Frequency, Monetary) analysis and customer segmentation. Despite stable sales, the company aims to boost profitability by understanding what high-value customers are buying and analyzing their customer lifetime values based on various available attributes.

## Tableau Dashboard
The Pricing Insight Dashboard for Customer Segmentation and Sales Analysis.
![6 Dashboard](https://github.com/user-attachments/assets/47c0dc65-704d-413a-89dc-510bca6de461)


In case of failure of loading Jupyter Notebooks on GitHub, the following notebooks can be found in nbviewer. Click on the respective hyperlinks to view:

- RFM table & Data prep: [link to nbviewer RFM table & Data prep]
- Customer Segment Analysis: [link to nbviewer Customer Segment Analysis]

## Analysis Approach

### 1. Data Preparation and RFM Analysis
- Created an RFM table from transaction data
- Calculated Recency, Frequency, and Monetary values for each customer
- Performed K-means clustering to segment customers

### 2. Customer Segmentation
- Segmented customers into four groups: Platinum, Gold, Silver, and Bronze
- Analyzed characteristics of each segment including:
  - Online vs offline order preferences
  - Product size preferences
  - State distribution
  - Gender distribution
  - Job industry categories
  - Wealth segments

### 3. Sales and Product Analysis
- Examined sales trends over time
- Analyzed sales by age group and gender
- Investigated brand preferences and profitability for each customer segment
- Studied product line preferences and profitability

### 4. Age Group and Product Preferences
- Analyzed product line preferences by age group
- Identified top 10 products by sales and their typical customer profiles

## Key Insights

1. Sales Overview:
   - Sales appear to be steady over time, indicating a stable customer base but potential for growth.
   - Customers in their 40s and 50s are the leading contributors to sales, followed closely by those in their 30s and 60s.
   - There's a slight lead in sales from female customers, but the difference is not significant.

2. Customer Segmentation:
   - Gold segment generates the most profit, followed by Platinum.
   - Both Platinum and Gold customers have a nearly even split between online and offline orders.
   - Medium-sized products are most popular (64-66%), followed by large, then small.
   - NSW dominates (53-54%) in terms of customer location, followed by VIC and QLD.
   - Financial Services and Manufacturing are top industries for both Platinum and Gold segments.

3. Brand and Product Analysis:
   - High-value customers (Platinum and Gold) prefer Solex, WeareA2B, and Giant bicycle brands.
   - WeareA2B generates the most profit, despite Solex being the most popular choice.
   - Standard, Road, and Touring product lines are the most profitable for the business.
   - Touring bicycles have the highest profit margins but are not the first choice for most customers.

4. Age Group Preferences:
   - Standard Bikes are the most versatile option, appealing to a wide range of customers.
   - Road Bikes are a balanced choice for both younger and older riders interested in speed and performance.
   - Touring Bikes are particularly popular among older age groups.
   - Mountain Bikes are popular among younger riders seeking excitement.

## Datasets Used
- RFM_Final_Dataset.xlsx: This dataset included detailed information about customer transactions, demographics, and RFM scores.

## Tools and Technologies Used
- **Python**: For Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis using libraries like pandas, matplotlib, and seaborn.
- **Jupyter Notebooks**: For documenting the analysis process and creating visualizations.
- **Excel**: For minor analysis and broad view to make decisions. 
- **PowerBI**: For creating the Pricing Insight Dashboard to visualize analysis.

## Future Work
- Develop targeted marketing strategies for each customer segment
- Analyze seasonal trends in purchasing behavior
- Investigate the impact of pricing strategies on customer segment behavior
- Explore potential for cross-selling and upselling within and across segments
