# Customer Shopping Behavior & Trend Analysis

##  Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** to uncover trends in spending, customer segments, product performance, and subscription impact. The objective is to help a retail business make **data-driven decisions** to improve revenue, customer engagement, and long-term loyalty.

The analysis was performed using **Python for data preparation**, **SQL for structured business analysis**, and **Power BI for interactive visualization**.

---

## Tools & Technologies
- **Python** (Pandas, NumPy) – Data cleaning, EDA, feature engineering  
- **SQL** – Business queries and customer segmentation  
- **Power BI** – Interactive dashboards and KPI visualization  
- **Jupyter Notebook** – Analysis workflow and documentation  

---

## Dataset Summary
- **Total Transactions:** 3,900  
- **Total Columns:** 18  
- **Key Features:**  
  - Customer demographics (Age, Gender, Subscription Status)  
  - Purchase details (Category, Item Purchased, Amount, Season)  
  - Behavioral attributes (Discount Applied, Review Rating, Shipping Type)  
- **Missing Values:** 37 values (Review Rating column, handled via median imputation)

---

## Data Preparation (Python)
- Loaded and explored raw data using Pandas  
- Handled missing values using **median imputation**  
- Standardized column names for readability  
- Created **derived features** such as:
  - Age Groups  
  - Purchase Frequency  
- Integrated cleaned data into **PostgreSQL** for SQL analysis  

---

## Data Analysis (SQL)
Key business questions answered using SQL:
- Revenue comparison by **gender**
- Identification of **high-spending customers who still use discounts**
- Top-rated products by average review score
- **Standard vs Express shipping** impact on purchase value
- **Subscribers vs non-subscribers** spending behavior
- Customer segmentation into **New, Returning, and Loyal**
- Revenue contribution by **age group**
- Discount-dependent products and repeat buyer behavior

---

## Power BI Dashboard
An interactive Power BI dashboard was built to visualize:
- Total customers, average purchase amount, and review rating  
- Revenue and sales by category  
- Subscription vs non-subscription performance  
- Revenue by age group  
- Shipping type impact on spending  

 The dashboard enables stakeholders to quickly identify **high-value segments and growth opportunities**.

---

## Key Insights
- **Female customers generate slightly higher total revenue** than male customers  
- **Express shipping users spend ~12% more per transaction** than standard users  
- **Subscription customers contribute ~45% of total revenue** and show higher loyalty  
- A small segment of **high-value customers strategically uses discounts**  
- **Young Adults and Middle-aged customers** are the highest revenue contributors  

---

## Business Recommendations
- Promote **subscription plans** with exclusive benefits  
- Strengthen **loyalty programs** to convert returning customers into loyal ones  
- Target **high-revenue age groups** with personalized marketing  
- Highlight **top-rated products** in campaigns  
- Optimize discount strategies to balance revenue growth and margins  

---


## Outcome
This project demonstrates an **end-to-end analytics workflow**—from raw data to business insights—showcasing skills in **Python, SQL, Power BI, and analytical thinking**, aligned with real-world business use cases.





