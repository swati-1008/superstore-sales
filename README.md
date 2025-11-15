# 🛒 Superstore Sales Analysis — SQL Case Study

This project is an end-to-end SQL analysis of the **Superstore Sales Dataset**.  
The objective is to explore sales performance, customer behavior, and operational insights using SQL.

---

## 📂 Dataset Overview

The dataset contains:

- **Order Information:** `RowID`, `OrderID`, `OrderDate`, `ShipDate`, `ShipMode`
- **Customer Information:** `CustomerID`, `CustomerName`, `Segment`
- **Geography:** `Country`, `City`, `State`, `Region`, `Postal Code`
- **Product Details:** `Category`, `Sub-Category`, `ProductID`, `ProductName`
- **Sales:** `Sales` (Numeric)

> **Note:** This dataset version does *not* include Quantity, Discount, or Profit columns.

---

## 🛠️ Tools Used

- **SQL (PostgreSQL)**
- **pgAdmin**
- **Local CSV Import**

---

## 🧹 Data Cleaning Steps

- Imported CSV using `COPY`
- Converted `OrderDate` + `ShipDate` from `VARCHAR` → `DATE`
- Validated data types
- Checked for duplicates

---

## 📌 SQL Analysis Performed

### 🔹 **Basic Exploration**
- Total number of orders  
- Unique product categories  
- Total sales  
- Regional sales distribution  

### 🔹 **Customer Analytics**
- Orders per customer  
- Customer Lifetime Value (CLTV)  
- RFM Segmentation (Recency, Frequency, Monetary)

### 🔹 **Product Insights**
- Top 10 highest-selling products  
- Most popular sub-category in each region  

### 🔹 **Time-Based Insights**
- Month-on-month sales trend  
- Average shipping delay  

### 🔹 **Advanced Analytics**
- Cohort Analysis (First Purchase Month)

---

## 📊 Key Insights

- **Top Revenue-Generating Categories:** Technology, Furniture, Office Supplies  
- **Highest Revenue Region:** West  
- **Top Customer by Revenue:** William Brown  
- **Average Shipping Delay:** Close to 4 days
- **Cohort Trends:** Multiple strong acquisition months  
- **RFM Findings:** Customer monetary values show high variance, ideal for segmentation  

---

## 📁 Project Structure
superstore-sales/
│

├── Capstone Project Queries.sql # All SQL queries used in the project

├── README.md # Project documentation

└── train.csv # Source dataset 



---

## ✅ Conclusion

This SQL case study demonstrates:

- Data cleaning  
- Aggregation and grouping  
- Window functions  
- Time-series analysis  
- Customer segmentation  
- Cohort & RFM modeling  

---

## ⭐ Future Enhancements

- Build visualizations in Python (Seaborn/Matplotlib)  
- Add dashboards (Power BI / Tableau)  
- Create an automated SQL → CSV reporting pipeline  

---

## 📬 Contact

For questions or collaboration, feel free to reach out.

---

