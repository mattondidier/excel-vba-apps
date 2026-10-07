# Omboo: Investor and Treasury Management in Excel VBA

🇫🇷 [Version française](README.fr.md)

**From the investor's deposit to payment tracking: investments, schedules, treasury and communication, in a single Excel application driven by VBA.**

Developed in 2020.

![Omboo demo](assets/omboo-demo.gif)

## The problem

A company receiving funds from many investors needs to record each investment, track payment schedules, keep its treasury by cashier and payment method, and stay in touch with its investors. Omboo brings all of this into one tool that runs on any computer with Excel, with nothing to install.

## Features

**Access and administration**
- User login with password, with a choice of language (French or English)
- Access rights management
- Company profile, application update and public holiday calendar

**Settings**
- Payment methods, including mobile money (MoMo, Orange Money, YUP)
- Affiliation modes and cash movement reasons
- Investment plans
- Investors, employees and service providers

**Daily operations**
- Investment ledger: date, plan, investor, payment method, amount, with automatic calculation of the payment schedule
- Miscellaneous operations ledger
- Payment management by due date

**Communication**
- Message templates, e-mail campaigns and bulk SMS

**Analysis**
- 15 reports: investor-by-plan cross analysis, daily treasury (overall and per cashier), overall treasury position
- Treasury receipts, expenses and result by period, month by month
- Pending payments
- History of investments, miscellaneous operations, payments and cash flows
- Multi-criteria search (dates, plan, investor, payment method), charts and printing

## Under the hood

| Item | Detail |
|------|--------|
| Language | VBA (Excel) |
| Interface | Custom menu bar, a UserForm for each module |
| Data | Settings tables, ledgers and history stored in the workbook |
| Calculations | Payment schedule generated on entry, treasury reports aggregated by period, cashier and payment method |

## Status

The source file is no longer available. This page is based on the demo video.

## Author

**Didier Matton** | Financial Engineer | Full-Stack Data Scientist | Python, Django, VBA, BI & LLMs | Quantitative Finance
