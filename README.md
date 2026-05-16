#  Retail Rocket E-commerce Funnel Analysis

##  Project Overview

This project analyzes customer behavior on an e-commerce platform using the **Retail Rocket** dataset. The goal was to understand the customer journey, identify major drop-off points, and provide actionable insights to improve conversion rates.

##  Objective

- Analyze the complete customer funnel (View → Add to Cart → Transaction)
- Identify the biggest drop-off stages
- Find peak activity hours and best performing days
- Provide data-driven recommendations to improve conversions

##  Key Insights

- **97.31%** of customers drop off at the **View → Add to Cart** stage (biggest opportunity area)
- Tuesday and Wednesday show the **highest customer activity** — ideal days for promotions
- Peak activity occurs between **12:00 AM - 5:00 AM UTC** (late night / early morning)
- Overall conversion rate is only **0.88%**, indicating significant room for improvement
- Improving the first stage conversion by just **1%** could bring in **over 2,500 additional customers**

##  Dataset

The original dataset file is **very large (~200 MB)**, so it is **not included** in this repository due to GitHub's file size limits.

### How to Get the Data:
1. Download the dataset from Kaggle:  
   [Retail Rocket E-commerce Events](https://www.kaggle.com/datasets/retailrocket/ecommerce-events-history-in-cosmetics-shop)
2. Place the CSV file inside a folder named `data/` in your project directory.
3. Run the Jupyter notebook (`Ecommerce_Funnel_analysis.ipynb`).

## Dashboard Highlights

- **3 Key KPIs** at the top: Total Unique Visitors, Overall Conversion Rate, Biggest Drop-off Stage
- **Purchase Funnel** showing true conversion rates between stages
- **Hourly Activity Trend** with clear peak hours
- **Day of Week Analysis** highlighting best performing days
- Clean and professional design with actionable insights

## Tools & Technologies Used

- **Tableau** – For interactive dashboard and visualizations
- **Python (Pandas + SQLite)** – For data cleaning and funnel analysis
- **SQL** – For extracting and aggregating funnel data

##  Business Recommendations

1. Focus on improving the **View → Add to Cart** experience (biggest drop-off)
2. Run targeted campaigns on **Tuesday and Wednesday**
3. Optimize website/app experience during **peak hours (12 AM - 5 AM UTC)**
4. A/B test product page design and add-to-cart flow to reduce friction
