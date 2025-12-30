# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## Dataset
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
- **Missing Data:** 37 missing values in the Review Rating column

## Project Files
- `customer_shopping_behavior.csv` – Original dataset  
- `customer_behavior_dashboard.pbix` – Power BI interactive dashboard  
- `customer_shopping_behavior_analysis.sql` – SQL queries for business insights  
- `Customer-Shopping-Behavior-Analysis.ipynb` – Python EDA and data preprocessing  
- `Customer Shopping Behavior Analysis Report.pdf` – Detailed analysis report  
- `Customer-Shopping-Behavior-Analysis-presentation.pptx` – Presentation of findings  

## Methodology

### 1. Exploratory Data Analysis (Python)
- Data loading using `pandas`
- Initial exploration using `.info()` and `.describe()`
- Handling missing data by imputing median values in the `Review Rating` column
- Column standardization to snake_case
- Feature engineering:
  - `age_group` from customer ages
  - `purchase_frequency_days` from purchase data
- Data consistency checks and removal of redundant columns
- Integration with PostgreSQL for structured analysis

### 2. Data Analysis (SQL)
Performed SQL queries to answer business questions such as:
- Revenue by Gender
- High-spending discount users
- Top 5 products by rating
- Shipping type comparison
- Subscribers vs. Non-subscribers
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Top 3 products per category
- Repeat buyers and subscription correlation
- Revenue by age group

### 3. Dashboard (Power BI)
An interactive dashboard to visualize insights, including:
- Revenue comparisons
- Customer segments
- Product performance
- Subscription behavior

## Business Recommendations
- **Boost Subscriptions:** Promote exclusive benefits for subscribers  
- **Customer Loyalty Programs:** Reward repeat buyers  
- **Review Discount Policy:** Balance sales boosts with profit margins  
- **Product Positioning:** Highlight top-rated and best-selling products  
- **Targeted Marketing:** Focus on high-revenue age groups and express-shipping users  

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (PostgreSQL)
- Power BI

## How to Run
1. Load the dataset `customer_shopping_behavior.csv` into Python or SQL environment.
2. Open the Power BI file `customer_behavior_dashboard.pbix` to explore the dashboard.
3. Use the SQL file `customer_shopping_behavior_analysis.sql` to execute queries in PostgreSQL.
4. Refer to the Jupyter Notebook for EDA and data preprocessing steps.

## Author
Mohd Bilal

