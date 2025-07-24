# personal-finance-tracker
An interactive income & expense tracking tool with visual insights to support smarter financial planning.

## What This Project Does
This tracker helps users:
- Log their monthly income and expenses
- Categorize transactions
- View automated summaries and trends via a dashboard
- Filter data by month for better visibility
  
## Key Features
- Excel-based automation using formulas and data validation
- Easy-to-use data entry format
- Visual dashboard for better financial decision-making
- Clean layout designed for personal use and small business owners

## Tools Used
- Microsoft Excel
- Data validation
- Conditional Formatting
- Baic Excel Formulas (SUMIF, XLOOKUPS, etc)

## Why I Built This
With a background in finance and as a Chartered Accountant, I wanted to create a practical tool that helps individuals track their personal finances more efficiently. This project also demonstrates how Excel can be used to solve real-world financial problems with simplicity and clarity.

## File Info
- File name: 'Personal-Finance-Tracker.xlsx'
- Format: Microsoft Excel
  
## How to Use This Tracker
## 1. Set Up Your Items and Categories:
Before entering any transaction, go to the **"Item & Category Reference Table"** sheet. This is where you'll list all your custom income and expense items (e.g., "salary", "Groceries", "Electricity", etc). For each item, you must specify whether it is an **Income** or **Expense** in the corresponding columnn.

## 2. Enter Your Transactions:
After setting up your items, go to the **Transactions** sheet. Here, you will:
- Enter the **Date** of the tranaction
- Enter the **Amount** of the transaction
- Choose the **Item** from a dropdown list (powered by data validation)
- Once you select the item, the **Category (Income or Expense)** WILL automatically update - thanks to the formula linked to the Item & Category table.
**NOTE**;
If you try to enter a transaction item that has **not been listed** in the Item & Category Reference Table, it will **not appear** in the dropdown. So always add new items there first.
