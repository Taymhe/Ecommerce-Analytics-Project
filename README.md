# Ecommerce-Analytics-Project
E‑Commerce Data Analytics Project: Sales, Customer &amp; Product Performance Insights


# E‑Commerce Sales & Customer Analytics Project  
### Excel • Python • Power BI

## Project Overview
This project analyzes an e‑commerce company’s sales, customer behavior, product performance, and operational efficiency using Excel, Python, and Power BI. The goal is to uncover insights that improve revenue, customer retention, and profitability.

---

## Business Objectives
- Identify sales trends and seasonal patterns  
- Analyze customer segments and lifetime value  
- Evaluate product performance and profitability  
- Understand the impact of discounts on profit  
- Detect operational issues such as returns and shipping inefficiencies  

---

## Dataset Description

### **Orders Table**
| Column | Description |
|--------|-------------|
| order_id | Unique order identifier |
| order_date | Date of purchase |
| customer_id | Customer identifier |
| product_id | Product identifier |
| region | Customer region |
| sales | Total sales amount |
| quantity | Units sold |
| discount | Discount applied |
| profit | Profit earned |
| shipping_cost | Cost of shipping |

### **Customers Table**
| Column | Description |
|--------|-------------|
| customer_id | Unique customer |
| age | Customer age |
| gender | Male/Female |
| segment | Consumer/Corporate/Home Office |
| region | Customer region |

### **Products Table**
| Column | Description |
|--------|-------------|
| product_id | Unique product |
| category | Product category |
| subcategory | Product subcategory |
| cost_price | Cost of product |

### **Returns Table**
| Column | Description |
|--------|-------------|
| order_id | Returned order |
| return_reason | Reason for return |

---

## Excel: Data Cleaning & Preparation
- Removed duplicates  
- Standardized date formats  
- Filled missing values  
- Created calculated fields:
  - Gross Margin  
  - Discount Rate  
  - Shipping Efficiency  
- Used conditional formatting to detect:
  - Negative profit  
  - High discount orders  
  - Outliers  

---

## Python: Exploratory Data Analysis (EDA)

### **Key Tasks**
- Time‑series analysis  
- Customer segmentation (RFM)  
- Product profitability  
- Discount vs Profit correlation  
- Return rate analysis  

---

## Power BI Dashboard
### **Pages**
1. **Sales Overview**  
2. **Product Performance**  
3. **Customer Insights**  
4. **Operations & Returns**

---

## Key Insights
- Q4 generates the highest revenue due to holiday promotions  
- Electronics have high sales but low profit due to heavy discounting  
- Top 10% customers contribute nearly half of total revenue  
- 12% of orders are returned, mostly due to wrong item delivered  

---

## Recommendations
- Reduce discounting on Electronics  
- Improve warehouse quality checks  
- Introduce loyalty program for high‑value customers  
- Increase marketing in underperforming regions  

---

## Tools Used
- **Excel** – Data cleaning  
- **Python (Pandas, Matplotlib, Seaborn)** – EDA  
- **Power BI** – Dashboard & storytelling  

---

## 📬 Author
Temitope Oluwatobi Oyelaja :  Data Analyst  
