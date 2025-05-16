# 📊 Task 4: Power BI Dashboard – Sample Superstore Sales Analysis

## 🎯 Objective
Build an **interactive Power BI dashboard** using the **Sample Superstore dataset** to help business stakeholders analyze key metrics such as sales, profit, growth trends, and top-performing regions or segments.

---

## 🛠️ Tools Used
- ✅ Power BI Desktop  
- ✅ Power Query Editor  
- ✅ DAX (Data Analysis Expressions)

---

## 📁 Dataset: Sample Superstore
The dataset includes:
- **Order ID, Order Date, Ship Date**  
- **Customer Name, Segment, Region**  
- **Product Name, Category, Sub-Category**  
- **Sales, Quantity, Discount, Profit**

---

## 🧹 Data Cleaning (Power Query Editor)
Performed the following in **Power Query Editor**:
- 🔄 Removed duplicates  
- 🧹 Removed null or blank values  
- 📅 Converted `Order Date` and `Ship Date` to **Date** format  
- ➕ Created a new column:  
  ```Power Query
  Profit Margin = Profit / Sales
