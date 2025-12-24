  


# Customer Shopping Behavior Analysis 🛒  

An end-to-end **Data Analytics Project** focused on analyzing real-world customer shopping behavior using **Python, SQL, and Power BI**.

This project covers the complete analytics pipeline: 
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Business analysis using SQL 
- Interactive dashboard creation in Power BI 

---

## 📌 Project Objective  

To understand:
- How customers behave across product categories  
- The impact of discounts and subscriptions on revenue  
- Spending patterns across age groups and gender  
- The role of shipping methods in customer spending  

The goal is to convert raw data into **actionable business insights for decision-making**.

---

## 📂 Repository Structure

```

Customer_Behavior_Analysis/
│
├── Customer_shopping_Behavior_Analysis.ipynb   # Python cleaning & EDA
├── Customer_Behavior_sql_queries.sql           # Business SQL queries
├── Customer Behavior Analysis Dashboard.pbix   # Power BI Dashboard
├── customer_shopping_behavior.csv              # Original dataset
├── Business Problem Document.pdf               # Problem statement
└── README.md                                   # Project documentation

```

---

## 📊 Dataset Information

- **Total Records:** 3,900  
- **Total Columns:** 18  

### Key Columns

**Customer Info**
- `age`, `gender`, `location`, `subscription_status`

**Shopping Info**
- `item_purchased`, `category`, `purchase_amount`, `discount_applied`

**Behavior Metrics**
- `review_rating`, `previous_purchases`, `frequency_of_purchases`, `shipping_type`

### Data Cleaning

- Fixed **37 missing values** in `review_rating`  
- Missing values filled using **median rating by product category**  
- Column names converted to **snake_case**  
- Redundant column `promo_code_used` removed  

---

## 🛠️ Tools & Technologies Used

- **Programming:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Database Language:** SQL  
- **Visualization:** Power BI  
- **Environment:** Jupyter Notebook  

---

## 🧹 Data Processing (Python)

All preprocessing and EDA were performed inside:

`Customer_shopping_Behavior_Analysis.ipynb`

### Steps Performed

- Data loading using pandas  
- Data exploration using `.info()`, `.describe()`, `.head()`  
- Missing value treatment  
- Feature engineering  
  - Created `age_group`  
  - Processed customer purchase behavior  
- Exported cleaned dataset for SQL analysis  

---

## 🧠 Business Analysis (SQL)

All analytical queries are written in:

`Customer_Behavior_sql_queries.sql`

### Key Business Questions Answered

- Revenue comparison by gender  
- Subscriber vs non-subscriber spending patterns  
- Top 5 highest-rated products  
- Top products in each category  
- Impact of discounts on high spending customers  
- Shipping type vs purchase amount  
- Loyal vs returning customer behavior  
- Revenue contribution by age group  

---

## 📈 Power BI Dashboard

File:  
`Customer Behavior Analysis Dashboard.pbix`

### Dashboard Includes

- Total Revenue  
- Average Purchase Value  
- Customer Count  
- Discount Usage  
- Revenue by:  
  - Gender  
  - Age Group  
  - Subscription Status  
- Product performance by category  
- Shipping Type vs Purchase  
- Customer Segmentation  

The dashboard is fully interactive with slicers and filters.

---

## 💡 Key Insights

- Subscribers spend more per order than non-subscribers  
- Certain age groups generate the highest revenue  
- Express shipping users have higher purchase amounts  
- Some products rely heavily on discounts  
- Loyal customers contribute a major share of sales  

---

## ✅ Business Recommendations

- Focus marketing on high-revenue age groups  
- Improve subscription benefits to boost retention  
- Reduce excessive discounts on low-performing products  
- Promote top-rated products more aggressively  
- Implement loyalty rewards for repeat customers  

---

## ▶️ How to Run This Project

### 1. Clone the Repository

```

git clone https://github.com/murali3633/Customer_Behavior_Analysis.git
cd Customer_Behavior_Analysis

```

---

### 2. Install Required Packages

```

pip install pandas numpy matplotlib seaborn

```

---

### 3. Run the Python Notebook

```

jupyter notebook

```

Open:  
`Customer_shopping_Behavior_Analysis.ipynb`

---

### 4. Run SQL Queries

- Import the cleaned dataset into any SQL-supported database or tool  
  (MySQL, SQLite, SQL Server, etc.)
- Execute queries from:

`Customer_Behavior_sql_queries.sql`

---

### 5. Open Power BI Dashboard

- Open Power BI Desktop  
- Load `Customer Behavior Analysis Dashboard.pbix`  
- Refresh the dataset if connected to your local SQL source  

---

## 🚀 Future Enhancements

- Time-series sales analysis  
- Customer churn prediction  
- Customer Lifetime Value (CLV) modeling  
- Web dashboard using Streamlit  
- Automated data pipelines  

---

## 👤 Author

**Murali Nadipinti**  
Aspiring Data Analyst | Python | SQL | Power BI  


