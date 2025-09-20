# Profit_Analysis_Dashboard
Profit Analysis using SSMS, Alteryx &amp; Power BI


# Profit Analysis Dashboard – SSMS, Alteryx & Power BI

## Project Overview
This project performs a **Profit Analysis** for a company using data from Customers, Accounts, Transactions, and Revenue & Expenses.  
The goal is to calculate profits, visualize revenue vs expenses trends, and analyze profits per customer or account using **SQL Server, Alteryx Designer, and Power BI**.

---

## Tools Used

| Tool | Purpose |
|------|---------|
| **SQL Server Management Studio (SSMS)** | Created database tables, inserted sample data, and ran queries for data extraction |
| **Alteryx Designer** | Connected to SQL Server, cleaned and transformed data, joined tables, calculated Profit, extracted Year and Month, and prepared final dataset |
| **Power BI Desktop** | Built interactive dashboard: Line Chart (Monthly Profit Trend), Clustered Column Chart (Revenue vs Expenses), Matrix/Table (Profit by Customer/Account), Card (Total Profit), added slicers for interactivity and formatted visuals |

---

## Project Workflow

1. **SQL Server (SSMS)**
   - Created tables: Customers, Accounts, Transactions, Revenue_Expenses
   - Inserted sample data
   - Queried data to extract relevant information

2. **Alteryx Designer**
   - Connected to SQL Server via ODBC
   - Performed ETL operations: joined tables, cleaned data, calculated Profit
   - Extracted Year & Month from transaction dates
   - Output a final clean dataset for visualization

3. **Power BI Desktop**
   - Loaded dataset from Alteryx
   - Created visuals:
     - **Line Chart:** Monthly Profit Trend
     - **Clustered Column Chart:** Revenue vs Expenses
     - **Matrix/Table:** Profit by Customer/Account
     - **Card:** Total Profit Overview
   - Added slicers: Year, Month, Customer, and Account
   - Formatted dashboard for professional presentation

---

## Dashboard Screenshot
![Dashboard Screenshot](<img width="896" height="498" alt="Profit analysis Dash Board" src="https://github.com/user-attachments/assets/c59ad4c7-5465-4d53-b9c3-c86014aef06c" />
)

---

## How to Explore
1. Run the SQL script (`ABC.db`) in SSMS to create tables and insert data.  
2. Open the Alteryx workflow (`Profit_Analysis.yxmd`) and run it to transform and prepare the dataset.  
3. Open the Power BI report (`Profit_Analysis.pbix`) to view the interactive dashboard.
