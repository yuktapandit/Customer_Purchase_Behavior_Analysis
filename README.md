
🛒  Customer Purchase Behavior Analysis

📘 Overview

  This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.
  The objective is to identify key insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business strategies and improve decision-making.

🧾 Dataset

  - Total Rows: 3,900
  
  - Columns: 18
  
  - Key Features:
  
      * Customer Demographics: Age, Gender, Location, Subscription Status
    
      * Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
    
      * Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type
  
  - Missing Data: 37 missing values in review_rating handled via median imputation per product category

🧰 Tools & Technologies

  Python – Data loading, cleaning, and EDA (Pandas, NumPy, Matplotlib)
  
  MySQL – SQL queries for structured data analysis
  
  Power BI – Dashboard creation and visualization
  
  Jupyter Notebook – Code execution and documentation

🔍 Steps Performed
  1. Data Preparation & Cleaning
  
    - Imported dataset using Pandas.
    
    - Checked structure with .info() and summary stats with .describe().
    
    - Handled missing values in review_rating via median imputation.
    
    - Renamed columns to snake_case for readability.
    
    - Created additional features:
    
        - age_group (binned by age)
        
        - purchase_frequency_days (derived from transaction data)
    
    - Dropped redundant column promo_code_used after consistency checks.
  
  2. Exploratory Data Analysis (EDA)
  
    - Examined purchase trends, seasonal variations, and discount effects.
    
    - Analyzed demographic impact on spending behavior.
    
    - Visualized correlations and category performance using Matplotlib.
  
  3. SQL Data Analysis
  
    - Key business questions answered using MySQL queries:
    
        - Revenue comparison by gender
        
        - High-spending discount users
        
        - Top 5 products by average rating
        
        - Average spend by shipping type (Standard vs. Express)
        
        - Subscribers vs. Non-Subscribers revenue analysis
        
        - Top discounted products
        
        - Customer segmentation (New, Returning, Loyal)
        
        - Top 3 products per category
        
        - Repeat buyers vs. subscription rate
        
        - Revenue contribution by age group
  
  4. Power BI Dashboard
  
    - Developed an interactive Power BI dashboard to visualize:
  
        - Revenue distribution across demographics
        
        - Category and seasonal performance
        
        - Customer segmentation and loyalty insights
        
        - Subscription-based revenue trends
        
        - Discount and rating correlations

📊 Results & Insights

  - Subscribers spend significantly more than non-subscribers.
  
  - Loyal customers drive consistent, high-value revenue.
  
  - Express shipping users make larger purchases.
  
  - Top-rated products show strong correlation with repeat buying.
  
  - Discounts effectively boost sales but require profit margin monitoring.

⚙️ How to Run

  1. Clone the repository:
  
    git clone https://github.com/yourusername/Customer-Purchase-Behavior-Analysis.git
    cd Customer-Purchase-Behavior-Analysis
  
  
  2. Install dependencies:
  
    pip install -r requirements.txt
  
  
  3. Run the analysis script:
  
    python data_analysis.py
  
  
  4. Load data into MySQL:
  
      - Create a database named customer_behavior.
      
      - Update database credentials in the Python script.
      
      - Execute the SQL scripts to generate insights.
  
  5. Open the Power BI dashboard:
  
      - Launch Power BI Desktop.
      
      - Open Customer_Purchase_Behavior_Dashboard.pbix for interactive visualization.

🧩 Project Presentation

  You can view the full presentation here:
  
  👉 [View Project Presentation (PPT)](https://customer-purchase-behavi-2xpjpp3.gamma.site/)

🏁 Conclusion

  This project demonstrates an end-to-end data analytics workflow — from data cleaning and exploratory analysis in Python to SQL-based insights and Power BI visualization.
  It highlights practical skills in data wrangling, business intelligence, and analytical storytelling — essential for real-world decision-making in the retail domain.
