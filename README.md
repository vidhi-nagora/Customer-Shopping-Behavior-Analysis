# 📊 Customer Behavior Analysis (End-to-End Data Analytics Project)

## 🔍 Overview
This project analyzes customer shopping behavior using Python, SQL, and Power BI. The goal is to understand purchasing patterns, customer segments, and key factors influencing sales. The project follows a complete data analytics workflow from raw data to insights and visualization.

---

## 📁 Dataset
- Dataset: Customer Shopping Behavior Data  
- Contains information on customer demographics, purchase details, product categories, discounts, and transaction patterns  
- Total Records: ~3900 rows  
- Key Features:
  - Age, Gender  
  - Item Purchased, Category  
  - Purchase Amount  
  - Subscription Status  
  - Discount & Promo Usage  
  - Previous Purchases, Frequency  

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy)** → Data cleaning & EDA  
- **MySQL** → Data querying & analysis  
- **Power BI** → Dashboard & visualization  
- **Gamma (PPT)** → Presentation of insights  

---

## ⚙️ Project Workflow

### 1. Data Loading (Python)
- Imported dataset using Pandas  
- Performed initial inspection using `.head()`, `.info()`, `.describe()`

### 2. Data Cleaning & Preparation
- Handled missing values using category-wise median imputation  
- Standardized column names  
- Removed unnecessary columns  
- Created new features:
  - Age Groups  
  - Purchase Frequency (in days)  

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer spending patterns  
- Compared behavior across gender, category, and subscription status  
- Identified trends in discounts, shipping, and purchase frequency  

### 4. SQL Analysis (MySQL)
- Loaded cleaned data into MySQL  
- Wrote queries to solve business problems such as:
  - Revenue by category and gender  
  - Top products and customer segments  
  - Discount impact on sales  

### 5. Power BI Dashboard
- Built an interactive dashboard to visualize:
  - Revenue trends  
  - Customer segmentation  
  - Product performance  
  - Subscription insights  

### 6. Reporting & Presentation
- Summarized key insights into a report  
- Created a presentation (PPT) using Gamma  

---

## 📊 Dashboard Highlights
- Revenue distribution by category and gender  
- Customer segmentation by age group  
- Subscription vs non-subscription spending  
- Discount and promo code impact  
- Purchase frequency patterns  

---

## 📈 Key Insights
- Subscribed customers tend to spend more on average  
- Certain product categories contribute significantly to total revenue  
- Discounts influence purchase behavior but do not always increase spend  
- Repeat customers show higher purchase frequency and value  

---

## 📌 Conclusion

This project demonstrates an end-to-end data analytics workflow, combining Python, SQL, and Power BI to extract meaningful insights and support data-driven decision-making.
