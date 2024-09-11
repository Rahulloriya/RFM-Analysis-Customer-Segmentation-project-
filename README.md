# Customer Segmentation Project 

## Goal of the Project
The purpose of this project is to conduct a comprehensive Customer Segmentation Analysis for an Australian automobile bike company. Customer segmentation is performed by developing an RFM (Recency, Frequency, Monetary) Model and applying K-means clustering algorithm. RFM analysis is a behavior-based approach grouping customers into segments based on their previous purchase transactions, while K-means clustering helps to identify distinct customer groups based on multiple attributes.

In this analysis, the customer base was divided into 4 distinct segments using K-means clustering: Platinum, Gold, Silver, and Bronze. The project aims to determine which customer segments should be targeted to enhance sales revenue and profitability for the company. A detailed Dashboard is developed using Tableau to visualize key insights and trends.

The data quality assessment, RFM analysis, K-means clustering, and exploratory data analysis are performed using Python. This project seeks to provide actionable insights into customer behavior, brand preferences, and product performance to drive strategic decision-making and targeted marketing efforts.

## Tableau Dashboard
The Dashboard for Customer Segmentation and Sales Analysis can be found [here](https://public.tableau.com/views/RFMDashboard_17260549311650/Dashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![6 Dashboard](https://github.com/user-attachments/assets/47c0dc65-704d-413a-89dc-510bca6de461)


In case of failure of loading Jupyter Notebooks on GitHub, the following notebooks can be found in nbviewer. Click on the respective hyperlinks to view:

- [RFM table & Customer segmentation](https://nbviewer.org/github/Rahulloriya/RFM-analysis-Customer-segmentation-project-/blob/main/4.Customer_Segmentation_using_RFM_and_KMeans.ipynb)
- [Data Analysis](https://nbviewer.org/github/Rahulloriya/RFM-analysis-Customer-segmentation-project-/blob/main/5.Data%20Analysis.ipynb)

- [CustomerDemographic Data Cleaning](https://nbviewer.org/github/Rahulloriya/RFM-analysis-Customer-segmentation-project-/blob/main/2.Data%20Cleaning/2.Data%20Cleaning%20CustomerDemographic.ipynb)
- [Transactions Data Cleaning ](https://nbviewer.org/github/Rahulloriya/RFM-analysis-Customer-segmentation-project-/blob/main/2.Data%20Cleaning/4.Data%20Cleaning%20Transactions.ipynb)
- [Customer Address Data Cleaning](https://nbviewer.org/github/Rahulloriya/RFM-analysis-Customer-segmentation-project-/blob/main/2.Data%20Cleaning/5.Data%20Cleaning-Customer%20Address.ipynb)

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

  
## Solution
The company can increase profitability by targeting its high-value (Platinum and Gold) customer segments and optimizing its product offerings.

### Reasons
- High-value customers (Platinum and Gold) generate the most profit for the company.
- The analysis revealed key insights about the preferences and behaviors of these high-value customers, which can be leveraged to drive profitability.
- Certain product lines, brands, and features have higher profit margins, indicating opportunities for optimization.

### Facts
- Gold customers account for the highest total profit, followed closely by Platinum customers.-
- High-value customers prefer Solex, WeareA2B, and Giant Bicycle brands, which have relatively higher profit margins.
- Standard, Road, and Touring product lines are the most profitable, with Touring bicycles having the highest profit margins.
- Customers in their 40s, working in Manufacturing or Financial Services, and belonging to the Mass Customer wealth segment are the primary buyers of the top-selling products.
- Balanced approaches to online and offline sales channels, as well as targeted marketing campaigns based on customer demographics and preferences, can help increase profitability.fitability.

## Tools and Technologies Used
- **Python**: For Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis using libraries like pandas, matplotlib, and seaborn.
- **Jupyter Notebooks**: For documenting the analysis process and creating visualizations.
- **Excel**: For minor analysis and broad view to make decisions. 
- **Tableau**: For creating the Pricing Insight Dashboard to visualize analysis.

