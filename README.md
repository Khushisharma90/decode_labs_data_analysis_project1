# decode_labs_data_analysis_project1

"E-commerce Data Cleaning, Documentation, and Analysis Dashboard.


# E-commerce Data Cleaning & Analytics Dashboard (Project 1)

## Project Overview📚
This repository contains my implementation of Project 1 with DecodeLabs. In this project, I acted as a Data Analyst to clean, audit, and analyze an e-commerce transactional dataset to achieve 100% data integrity and structural accuracy.

## Project Deliverables⚡
* **Cleaned Dataset & Dashboard (`.xlsx` file):** Includes raw data cleaning, dynamic Pivot Tables, and a multi-axis Combo Chart (Revenue vs. Quantity).
* **Data Audit Documentation (`.pdf` file):** A detailed, single-page change log tracking every operational change and business logic verification.

## Data Cleaning & Quality Checklist Enforced💡
1. **CR001 (Unique Identifiers):** Audited `OrderID` column for duplicates; verified 100% unique primary keys.
2. **CR002 (Temporal Standardization):** Standardized unstructured dates into uniform `YYYY-MM-DD` formats.
3. **CR004 (Missing Values Logic):** Preserved natural blanks in `CouponCode` to maintain authentic business metrics instead of forcing incorrect statistical imputation.
4. **CR006 (Financial Formatting):** Formatted `UnitPrice` uniformly to a strict 2 decimal places.
5. **CR007 (E-commerce Logic):** Allowed repeating `CustomerID` records to preserve genuine customer lifetime value and transaction history.
6. **CR008 (Logistics Trace):** Audited `TrackingNumber` column for 100% completeness.

## 🚀 How to Run⚡

Since this project is built using Microsoft Excel and includes documentation, follow these steps to review the analysis:

1. Clone or download this repository to your local machine.
2. Open the `.xlsx` file using **Microsoft Excel** (or Google Sheets) to view the dynamic Pivot Tables and the multi-axis Combo Chart.
3. Review the `Data Audit Documentation` (.pdf file) to see the full change log and business logic verification.


