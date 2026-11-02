# Kolawole Opeyemi Oscar | Data Analyst Portfolio

I'm a QA Engineer moving into data analysis. In QA, my job is to catch what's wrong before it reaches users. I bring the same habit to data: I check it, document what's broken, decide how to fix it, and prove my numbers match the source.

Live site: [oscarcodelab.github.io](https://oscarcodelab.github.io)

---

## Projects

### 1. BrightHaus Electronics: Sales, Profitability and Returns (Excel)

**The situation.** BrightHaus is a fictional Nigerian electronics retailer with 31 store locations, covering January 2022 to December 2025. Its sales, returns, customer, product, store and employee data sat in separate tables, and some of it was messy. Management had no single reliable view of where profit comes from or where it leaks.

**What I did**
1. **Cleaned seven raw tables in Power Query**, merging a separate marketplace order feed into the Orders table to give a six-table data model.
2. **Logged 49 data quality issues** in an Issue Log, each with the problem, the decision and the reason. Examples: two product IDs with conflicting prices, a duplicate employee record, two orders with no date, and blank genders and return reasons.
3. **Built a data model** with six relationships and wrote DAX measures for Net Sales, Profit, Margin %, Return Rate, and Assisted vs Online Sales.
4. **Checked my results against the source data** before building any charts.
5. **Built a five-page dashboard** with PivotCharts, KPI cards, slicers and a navigation bar that highlights the current page.

**What the dashboard covers**
- **Overview:** revenue, profit, margin and return rate at a glance
- **Sales:** performance by channel, store and time period
- **Products:** category and brand profitability
- **Employees:** sales by employee, and assisted sales compared with online sales that have no employee
- **Customers:** who is buying and from where

**Results**

| Measure | Value |
|---|---:|
| Revenue | ₦12.52 billion |
| Profit margin | 17.56% |
| Return rate | 7.70% |
| Orders / order lines | 20,271 / 34,061 |
| Data quality issues logged and resolved | 49 |

**Tools:** Excel, Power Query, Data Model (Power Pivot), DAX, PivotTables, PivotCharts, Slicers

**Files:** [Dashboard](#) | [Issue Log](#) | [Screenshots](#)

*The data is synthetic and was provided as a practice case study. The company is fictional.*

---

### 2. JRAD Retail Superstore Dashboard (Power BI)

**The situation.** JRAD is a grocery superstore with five branches. Its sales data (225K receipts, 1.8M line items and 632 products) was spread across 13 tables covering customers, employees, products, branches, payments, inventory and pricing. I combined them into one model to show which branches, products, payment methods and cashiers drive revenue, and who is buying.

**What I did**
- Cleaned 13 tables in Power Query: fixed dates, blanks, duplicates and data types.
- Built a relational data model with 14 relationships (12 active, 2 inactive to prevent ambiguous filter paths). Sales are stored as a header-detail pair: Receipt (one row per sale) and Transaction (one row per product sold), linked to customer, employee, product, department, branch, payment and date tables.
- Created a Date table and a dedicated measures table.
- Wrote DAX measures for revenue, receipts, average transaction value, month-over-month growth, product revenue tiers and share of company revenue.
- Built a six-page report (Overview, Sales, Product, Customer, Payment, Staff) with KPI cards, slicers and a short written insight on key pages.

**What I found**
- **Revenue:** ₦15.3bn from 225K receipts, averaging ₦67.99K each. December was the peak at ₦1.90bn, over 50% above the average of the other eleven months.
- **Products:** Groceries brings in 63% of revenue (₦9.7bn). Rice is the top category (₦3.4bn), and the top 20% of products generate about 75% of revenue.
- **Customers:** Walk-in shoppers bring 75% of revenue. The 800 registered customers bring 25% but spend about the same per visit (₦68.4K vs ₦67.9K), so registration is not yet increasing basket size.
- **Payments:** Transfer is 60% of transactions and revenue, POS 35% and cash 5%. Average spend is almost the same across all three (₦67K to ₦69K).
- **Branches and staff:** Egbeda leads at ₦3.6bn, 38% above Ajah (₦2.6bn). Revenue per cashier follows the same order (₦449M at Egbeda vs ₦322M at Ajah), and the top cashier makes up only 3.0% of company revenue, so the branch matters more than the individual.

**Tools:** Power BI Desktop, Power Query, DAX, Data Modeling

**Files:** [Dashboard screenshots](#) | [Data model screenshot](#) | [Power BI file](#)

*The dataset is synthetic and was used as a practice case study.*

---

### 3. SQL Server Data Cleaning (T-SQL)

Cleaning projects on three datasets: customers, company layoffs and Audible audiobooks. On the layoffs project I worked in staging tables so the raw data stayed untouched, and I checked records with a SELECT before running any UPDATE.

**What I did:** removed duplicates, standardized text, handled blanks, and corrected data types.

**Tools:** SQL Server, SSMS, T-SQL

**Files:** [Scripts](#)

---

## Skills

| Area | Tools and methods |
|---|---|
| Cleaning and validation | Power Query, T-SQL, issue logging, reconciling totals to source |
| Analysis | Excel (PivotTables), SQL, Python (pandas) |
| Dashboards | Power BI, Excel (PivotCharts, slicers, KPI cards) |
| Data modeling | Multi-table relational models (13 tables in JRAD), relationship design, Excel Data Model, DAX |
| Background | QA Engineer with 3+ years of experience: testing, defect tracking, validation |

---

## Contact

- Email: kolawoleopeyemioscar@gmail.com
- LinkedIn: [linkedin.com/in/kolawole-opeyemi-3063231b2](https://www.linkedin.com/in/kolawole-opeyemi-3063231b2)
- GitHub: [OscarCodeLab](https://github.com/OscarCodeLab)
