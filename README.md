# 🛍️ Sales Performance Analysis of a Retail Store (Excel Project)

This project demonstrates how to analyze the sales performance of a retail store using **Microsoft Excel**. It uses real-world-inspired data to uncover business insights such as top-performing salespeople, regional performance, product-level profitability, and more.

---

## 📁 Dataset Overview

- **Rows**: 50 sales transactions
- **Columns**: Date, Salesperson, Product, Units Sold, Unit Price, Discount, Region, and Customer Rating

---

## 🔧 Tools & Features Used

| No. | Feature / Task                                           | Excel Tool                                 |
|-----|-----------------------------------------------------------|---------------------------------------------|
| 1   | Calculate Total Sales (Units × Price)                     | `=D2*E2` formula                            |
| 2   | Calculate Net Sales after Discount                        | `=F2*(1 - J2/100)`                          |
| 3   | Filter sales made by a specific salesperson               | Filter → Text Filter                        |
| 4   | Show products with rating > 4.5                            | Filter → Number Filter                      |
| 5   | Highlight top 5 transactions                              | Conditional Formatting → Top/Bottom Rules   |
| 6   | Rank transactions by Total Sales                          | `RANK()` formula                            |
| 7   | Sort data by Net Sales                                    | Sort → Descending                           |
| 8   | Restrict ratings between 1 and 5                          | Data Validation → Decimal between 1 and 5   |
| 9   | Pivot Table of Salesperson vs Total Sales                 | Insert → Pivot Table                        |
| 10  | Add Slicers to filter Pivot Table by Region/Salesperson   | Pivot Table Analyze → Insert Slicer         |
| 11  | Bar Chart: Salesperson vs Total Sales                     | Insert → Chart → Column Chart               |

---

## 📊 Visualizations

- **Bar Chart**: Salesperson vs Total Sales
- **Pivot Table**: Sales by Region and Product
- **Slicers**: Region, Salesperson filters
