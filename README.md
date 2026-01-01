# 🛒 Customer Shopping Behavior Analysis

![Dashboard Screenshot](https://github.com/mohdabdulbilal/customer_shopping_behavior/blob/main/customer_behavior_dashboard.jpg)

## 📊 Project Overview
This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across various product categories. The goal is to uncover insights into:  
- 💰 Spending patterns  
- 👥 Customer segments  
- 🛍️ Product preferences  
- 📦 Subscription behavior  

These insights can guide strategic business decisions and marketing strategies.

---

## 📂 Dataset
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - **Customer Demographics:** Age, Gender, Location, Subscription Status  
  - **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
  - **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  
- **Missing Data:** 37 missing values in the `Review Rating` column

---

## 🗂️ Project Files
| File | Description |
|------|-------------|
| `customer_shopping_behavior.csv` | Original dataset |
| `Customer-Shopping-Behavior-Analysis.ipynb` | Python EDA & data preprocessing |
| `customer_shopping_behavior_analysis.sql` | SQL queries for business insights |
| `customer_behavior_dashboard.pbix` | Interactive Power BI dashboard |
| `Customer Shopping Behavior Analysis Report.pdf` | Detailed analysis report |
| `Customer-Shopping-Behavior-Analysis-presentation.pptx` | Presentation of findings |

---

## 🛠️ Methodology

### 1️⃣ Exploratory Data Analysis (Python)
- Load data using `pandas`  
- Initial exploration with `.info()` and `.describe()`  
- Handle missing values (`Review Rating`) with median imputation  
- Standardize column names to `snake_case`  
- Feature engineering:  
  - `age_group` from customer ages  
  - `purchase_frequency_days` from purchase history  
- Data consistency checks and removal of redundant columns  
- Integrate with PostgreSQL for structured queries

### 2️⃣ Data Analysis (SQL)
Key business questions answered using SQL:
- Revenue by Gender 💵  
- High-spending discount users 🏷️  
- Top 5 products by rating 🌟  
- Shipping type comparison 🚚  
- Subscribers vs Non-subscribers 🔄  
- Discount-dependent products 💳  
- Customer segmentation (New, Returning, Loyal) 🧩  
- Top 3 products per category 🏆  
- Repeat buyers & subscription correlation 🔗  
- Revenue by age group 🎯  

### 3️⃣ Dashboard (Power BI)
Interactive visualizations of insights:
- Revenue comparisons 📊  
- Customer segments 👥  
- Product performance 🛒  
- Subscription behavior 📦  

---

## 💡 Business Recommendations
- **Boost Subscriptions:** Promote exclusive subscriber benefits 💎  
- **Customer Loyalty Programs:** Reward repeat buyers 🎁  
- **Review Discount Policy:** Balance sales boosts with profit margins ⚖️  
- **Product Positioning:** Highlight top-rated and best-selling products ⭐  
- **Targeted Marketing:** Focus on high-revenue age groups and express-shipping users 🎯  

---

## 🖥️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn) 🐍  
- SQL 🗄️  
- Power BI 📊  

---

## 🚀 How to Run
1. Load the dataset `customer_shopping_behavior.csv` into a Python or SQL environment  
2. Open `customer_behavior_dashboard.pbix` in Power BI to explore the dashboard  
3. Run SQL queries in `customer_shopping_behavior_analysis.sql` using PostgreSQL  
4. Follow the Jupyter Notebook for EDA and preprocessing steps  

---

## 👤 Author
**Mohd Abdul Bilal**
