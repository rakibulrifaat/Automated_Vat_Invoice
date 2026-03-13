# Automated VAT Invoice – Google Sheets Template

Automated invoice system built in **Google Sheets** with:
- Customer & item autofill using XLOOKUP
- Automatic line totals
- Subtotal, 15% VAT calculation, 5% discount, and grand total
- Print-ready layout

## Features
- Autofills customer name, address from database
- Autofills item description, unit price from item list
- Calculates: Amount = Qty × Rate, Subtotal, VAT (15%), Discount (5%), Grand Total
- Clean, printable format (Hides gridlines)

## Quick Access

[![View Template in Google Sheets](https://img.shields.io/badge/View_Template-Google_Sheets-blue?style=for-the-badge&logo=googlesheets&logoColor=white&labelColor=34A853)](https://docs.google.com/spreadsheets/d/14J5HuMjI55-vXhwMsRdNL1sp0avl2YV2IzYFJOEeO18/edit?usp=sharing)  
*(Click → To view The VAT Invoice)*

[![Download XLSX Version](https://img.shields.io/badge/Download-XLSX-green?style=for-the-badge&logo=microsoftexcel&logoColor=white&labelColor=217346)](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/automated%20invoice%20with%20database.xlsx)
*(Click → To Download The VAT Invoice)*

## Screenshots

### 1. Filled Invoice Example
![Filled Automated Invoice](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/01_Automated_Invoice_Filled.png)

### 2. Blank Invoice Template
![Blank Invoice](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/02_Invoice_Blank.png)

### 3. Database Sheet (Customers + Items)
![Database Sheet](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/03_DataBase_Sheet.png)

### 4. Invoice with Formulas Visible
![Formulas in Invoice](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/04_Invoice_with_Formulas.png)

### 5. Autofill Formulas Detail
![Autofill Formulas](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/05_AutoFill_Formulas.png)

### 6. Printing Preview
![Print Preview](https://github.com/rakibulrifaat/Automated_Vat_Invoice/raw/main/Automated%20Vat%20Invoice/Screenshots/06_Printing_Preview.png)

## How to Use
1. Click **View Template** above → Make a copy of the Google Sheet
2. In the **Database** sheet:
   - Add customers (code, name, address, contact)
   - Add items/products (code, description, rate/unit price)
3. In the **Invoice** sheet:
   - Enter customer code → name/address autofills
   - Enter item code + quantity → description, rate, amount autofills
   - Add discount percentage if applicable
   - Grand total calculate automatically
4. Print directly or export as PDF

Made with ❤️
