# Oscar Kolawole | Data Analyst Portfolio

I'm a QA Engineer moving into data analysis. In QA, my job is to catch what's wrong before it reaches users. I bring the same habit to data: I check it, document what's broken, decide how to fix it, and prove my numbers match the source.

Live site: [oscarcodelab.github.io](https://oscarcodelab.github.io)

---

## Projects

### 1. BrightHaus Electronics: Sales, Profitability and Returns (Excel)

**The situation.** BrightHaus is a fictional Nigerian electronics retailer with 31 stores, covering January 2022 to December 2025. Its sales, returns, customer, product, store and employee data sat in separate tables, and some of it was messy. Management had no single reliable view of where profit comes from or where it leaks.

**The questions I set out to answer**
- Which products, channels and stores earn the most profit, and which earn less than their sales suggest?
- How much do discounts reduce margin?
- What is being returned, and why?
- How do online sales (with no employee involved) compare with employee-assisted sales?

**What I did**
1. **Cleaned six tables in Power Query**, and merged a separate marketplace order feed into the Orders table.
2. **Logged 49 data quality issues** in an Issue Log, each with the problem, the decision and the reason. Examples: two product IDs with conflicting prices, a duplicate employee record, two orders with no date, and blank genders and return reasons.
3. **Built a data model** with six relationships and wrote DAX measures for Net Sales, Profit, Margin %, Return Rate, and Assisted vs Online Sales.
4. **Checked my results against the source data** before building any charts.
5. **Built a five-page dashboard** (Overview, Sales, Products, Employees, Customers) with slicers and a navigation bar that highlights the current page.

**Results**

| Measure | Value |
|---|---:|
| Revenue | ₦12.52 billion |
| Profit margin | 17.56% |
| Return rate | 7.70% |
| Orders / order lines | 20,271 / 34,061 |

**What I found**
- [Finding 1, with a number]
- [Finding 2, with a number]
- [Finding 3, with a number]

**Tools:** Excel, Power Query, Data Model (Power Pivot), DAX, PivotTables, PivotCharts, Slicers

**Files:** [Dashboard](#) | [Issue Log](#) | [Screenshots](#)

*The data is synthetic and was provided as a practice case study. The company is fictional.*

---

### 2. JRAD Retail Dashboard (Power BI)

**The situation.** A Nigerian retail business kept customer, employee, product, branch and transaction data in five separate tables. I combined them to track sales, profit and returns by product, branch and sales rep.

**What I did**
- Cleaned the data in Power Query: fixed date formats, handled blanks, removed duplicates and corrected data types.
- Built a star schema with transactions at the centre. I fixed duplicate keys in the source tables rather than working around them in the model.
- Created a Date Table so year-over-year comparisons work correctly.
- Wrote DAX measures for revenue, profit, margin, return rate and year-over-year growth.
- Built an interactive dashboard with KPI cards, trends and slicers.

**What I found**
- [Finding 1, with a number]
- [Finding 2, with a number]

**Tools:** Power BI, Power Query, DAX

**Files:** [Dashboard screenshots](#)

---

### 3. SQL Server Data Cleaning (T-SQL)

Cleaning exercises on three real-world style datasets: customers, company layoffs and Audible audiobooks. For each one I worked in a staging table so the raw data stayed untouched, and checked records with a SELECT before running any UPDATE.

**What I did:** removed duplicates, standardised text, handled blanks, and corrected data types.

**Tools:** SQL Server, SSMS, T-SQL

**Files:** [Scripts](#)

---

## Skills

| Area | Tools and methods |
|---|---|
| Cleaning and validation | Power Query, T-SQL, issue logging, reconciling totals to source |
| Analysis | Excel (PivotTables), SQL, Python (pandas) |
| Dashboards | Power BI, Excel (PivotCharts, slicers, KPI cards) |
| Data modelling | Star schema, Excel Data Model, DAX |
| Background | QA engineer since 2022: manual testing, defect tracking, API testing |

---

## Contact

- Email: kolawoleopeyemioscar@gmail.com
- LinkedIn: [linkedin.com/in/kolawole-opeyemi-3063231b2](https://www.linkedin.com/in/kolawole-opeyemi-3063231b2)
- GitHub: [OscarCodeLab](https://github.com/OscarCodeLab)
