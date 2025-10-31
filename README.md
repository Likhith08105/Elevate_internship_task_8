# Task 8 – Simple Sales Dashboard

## 📘 Project Overview
This project is a **Power BI dashboard** created from the `Superstore_Sales_cleaned.csv` dataset.  
The goal is to visualize and analyze sales performance by month, region, and category — exactly as per the Task 8 instructions.

---

## 🧩 Files Included
| File Name | Description |
|------------|-------------|
| `Superstore_Sales_cleaned.csv` | Cleaned dataset used in Power BI |
| `clean_superstore.py` | Python script used to clean the original Superstore dataset |
| `dashboard.pdf` | Exported Power BI dashboard (final output) |
| `insights.txt` | Short insights and findings from the dashboard |
| `README.md` | Project documentation file |
| `powerbi-steps.txt` | Notes of steps followed in Power BI |

---

## ⚙️ Steps Performed

### 1. Data Cleaning (Python)
- Loaded `Superstore_Sales.csv` using pandas  
- Removed empty rows and fixed column names  
- Converted `Order Date` to datetime  
- Created new `Month-Year` and `Month Year Label` columns  
- Saved cleaned file as `Superstore_Sales_cleaned.csv`

### 2. Power BI Data Transformation
- Imported the cleaned CSV into Power BI  
- Ensured `Order Date` type = Date  
- Created `Month-Year` using Power Query custom column:
