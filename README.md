# An-Integrated-Framework-for-Retail-Business-and-Consumer-Intelligence
**An end-to-end data analytics project that turns raw retail transaction data into an interactive Power BI dashboard, using Excel → MySQL → Python → MySQL → Power BI.**

Author: **Divya Rubini S** | LinkedIn | GitHub

**Business Problem**

Retail businesses need to monitor sales performance, understand customer purchase behaviour, identify valuable customer groups, track inventory, and compare product, store and staff performance. This project builds a complete pipeline that converts raw transactional data into structured, queryable information and presents it in an interactive dashboard.

**Tools Used**
Stage	Tool	What I did

**Data cleaning**	Excel	Standardised headers, removed duplicates, handled missing values, added data validation, derived total price, XLOOKUP/VLOOKUP, PivotTable.

**Database	MySQL**	Created relational tables with primary/foreign keys, wrote JOIN, aggregation, ranking and CASE queries.

**Analysis	Python** (Pandas, NumPy, SQLAlchemy)	EDA, RFM feature calculation, customer segmentation, exported results back to MySQL.

**Reporting	Power BI** (DAX, Power Query)	Data model, KPI cards, slicers, charts, maps, page navigation.

Pipeline **Excel Cleaning → MySQL Database → Python EDA & RFM → MySQL (customer segments) → Power BI
 Dataset**

Relational retail data with these tables: Customers, Orders, Order Items, Products, Brands, Categories, Stocks, Stores, Staffs.

**Key Steps**

Excel: cleaned and validated every sheet, created a derived column (list_price * quantity) - discount, and exported table-specific CSV files.

SQL: imported the CSVs, defined keys and relationships, used INNER JOINs, ranked products by quantity sold, and built spending categories with CASE.

Python: loaded data from SQL, ran EDA, calculated Recency, Frequency and Monetary values per customer, and assigned segments.

SQL again: wrote the segmented RFM table back to MySQL as customer_segments.

Power BI: connected to MySQL, built the model and DAX measures, and designed four interactive pages.


**Dashboard Pages**
Home / Consolidated Dashboard
Customer Analysis & Purchasing Behaviour
Product & Inventory Analysis
Sales Analysis

**Features**: dynamic KPI cards, slicers (category, store, order status, customer segment), navigation buttons, maps and DAX measures.
<img width="1310" height="740" alt="Screenshot 2026-09-16 143449" src="https://github.com/user-attachments/assets/1ebb9da4-e42e-4c59-838a-8027f31fd203" />
<img width="1317" height="751" alt="Screenshot 2026-09-17 193544" src="https://github.com/user-attachments/assets/364d0b85-3468-44f1-acb1-7b18e259e6df" />

Open to freelance data analysis work: Excel, SQL, Python and Power BI dashboards.




