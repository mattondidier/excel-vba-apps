# DIGESC: Business Management Software in Excel VBA

🇫🇷 [Version française](README.fr.md)

**From invoice to dashboard: purchases, sales, stock, cash register and treasury of a small business, in a single Excel application driven by VBA.**

![DIGESC demo](assets/digesc-demo.gif)

▶ **Full demo:** [watch on YouTube](https://www.youtube.com/watch?v=vkNjocGOuQI) (in French)

## The problem

A small trading business needs to track its customers, suppliers, products spread across several warehouses, sales documents and cash register. DIGESC brings all of this into one tool that runs on any computer with Excel, with nothing to install.

## Features

**Access and administration**
- User login, with the password set at first login
- User management by the administrator, with access rights per menu (File, Settings, Operations, Analysis)
- Company profile (name, address, taxpayer number, website) and choice of backup folder

**Settings**
- Payment methods: cash, bank, credit, Orange Money, MoMo
- VAT rates, product families, packaging, sales units
- Warehouses, customer, supplier and employee categories
- Reasons for stock and cash movements

**Master data**
- Products: family, purchase and sale prices, VAT, minimum, maximum and alert stock levels, quantities per warehouse, main and secondary suppliers, barcode, photo
- Third parties: customers, suppliers and employees, with category, contacts and person in charge

**Sales documents**
- Pro forma, purchase order, delivery note, purchase invoice, sales invoice
- Automatic numbering by year and document type
- Full invoice calculation: discount, early-payment discount, transport (charged, prepaid or due) with its VAT, VAT, withholding tax on purchases, net amount due, due date and payment method

**Cash register**
- Counter sales with product photo, numbered receipts and daily sales balance

**Ledgers**
- Stock ledger, cash ledger, payment tracking

**Analysis**
- Stock status overall, by warehouse and by period
- Cash position by period and daily cashier report
- Monthly sales and purchases, with charts

**Data exchange**
- Data import from an Excel workbook
- Export of every list to PDF or Excel, and printing

## Under the hood

| Item | Detail |
|------|--------|
| Language | VBA (Excel) |
| Code | About 6,000 lines, 17 UserForms, 7 modules, 470 procedures |
| Data | A single sheet acts as the database, each table in its own block of columns |
| Architecture | Generic display, create, update and delete routines, reused by every form |
| Calculations | `SumIfs` aggregations for stock, cash and performance reports |
| Interface | Animated home menu, progress bar, button styles centralised in a dedicated module |
| Exports | PDF via `ExportAsFixedFormat`, import by opening an external workbook |

## Status

The Excel file is not public. A demo is available on request.

Forecasting was planned for a later version.

## What's next

DIGESC is being rebuilt as a web application with Django.

## Author

**Didier Matton** | Financial Engineer | Full-Stack Data Scientist
