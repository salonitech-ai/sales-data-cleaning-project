# 🧹 Sales Data Cleaning Project

## 📌 Objective
The goal of this project was to clean and prepare raw sales data for analysis by identifying and resolving data quality issues.

---

## 📊 Dataset Description
The dataset contains sales transaction records including:
- Order ID
- Customer Name
- City
- Order Date
- Product & Category
- Sales, Quantity, Profit

---

## 🔍 Data Issues Identified
- Unnecessary time component in date column  
- Presence of negative profit values (loss cases)  
- Data type verification required  

---

## 🛠 Data Cleaning Steps
- Removed time from Order_Date column  
- Standardized text values (City, Product, Category)  
- Ensured numeric format for Sales, Quantity, Profit  
- Created new column: `Profit_Type` (Profit/Loss)

---

## 🧰 Tools Used
- Microsoft Excel

---

## ✅ Final Outcome
A clean and structured dataset ready for analysis and visualization.

---

## 📊 Key Insights

- Mumbai generates the highest sales, while Chennai has the lowest  
- Headphones are the most profitable product, whereas Laptops generate the lowest profit  
- Out of 100 transactions, 71 are profitable and 29 result in losses  
- A significant portion of transactions are profitable, but losses still exist and need attention  
- Profitability varies across different products, indicating scope for optimization  

## 📈 Visualizations

### Sales by City
[Sales by City](sales_by_city.png)

### Profit by Product
[Profit by Product](profit_by_product.png)

### Profit vs Loss
[Profit vs Loss](Profit_vs_Loss.png)

