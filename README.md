# BlinkIt Data Cleaning Project

In this project, I took raw, unstructured data from BlinkIt (HomeKart Supplies)—which was formatted vertically—and converted it into a clean, well-structured Excel dataset.

## 📁 Project Files
* <a href="215.%20BlinkIt%20Data%20(HomeKart%20Supplies).xlsx">Raw Data File</a>
* <b>Cleaned Dataset:</b> <a href="[blinkit%20project%20excel.xlsx](https://github.com/Kanhaiya-2133/excel/blob/main/blinkit%20project%20excel.xlsx)">Cleaned Data File</a>

## What I Did (Steps):
1. **Data Reshaping:** The original data had details listed vertically as key-value pairs with blank rows in between. I grouped each order's details and transposed them into columns, creating a tabular dataset of 210 clean order records.
2. **Data Formatting:** 
   - Converted text dates into standard `YYYY-MM-DD` date formats.
   - Formatted numeric columns like Quantity, Unit Price, Discount, GST, and Net Amount.
3. **Validation & Cleanup:** 
   - Used Excel formulas to verify total amounts, discounts, and tax calculations.
   - Applied `TRIM` and `CLEAN` functions to remove extra spaces across product names, categories, and payment modes.

## Dataset Overview:
- **Total Records:** 210 Orders
- **Columns (14):** Order ID, Order Date, Customer, City, Pincode, Product, Category, Quantity, Unit Price, Discount, GST, Net Amount, Payment Mode, Delivery Status.
