# Healthcare Sales Analysis using Excel

## Project Overview

This project focuses on analyzing healthcare equipment sales data using Microsoft Excel. The dataset contains sales transactions for medical products such as syringes, stethoscopes, ultrasound devices, and X-ray machines sold across different regions by multiple sales representatives.

The objective is to transform raw sales data into meaningful business insights by applying Excel formulas, calculated fields, logical functions, and summary calculations. The analysis helps management evaluate revenue performance, discount impact, product returns, and regional sales trends.

---

## Business Problem

The healthcare equipment supplier requires a structured sales analysis to:

* Track overall revenue performance
* Measure the impact of discounts on sales
* Monitor returned orders
* Identify high-performing sales transactions
* Categorize products based on pricing
* Generate region-specific insights
* Support data-driven business decisions

---

## Dataset Information

The dataset includes the following key attributes:

* Order ID
* Order Date
* Product Name
* Region
* Sales Representative
* Units Sold
* Unit Price
* Discount
* Discount Percentage
* Return Status

---

## Excel Tasks Performed

### Column Creation

#### TotalSales

Calculated actual sales revenue after discounts.

Formula:
UnitsSold × UnitPrice x (1 - Discount / 100)

#### Deductions

Calculated discount value deducted from expected revenue.

Formula:
(UnitsSold × UnitPrice × Discount%)

#### ExpectedSales

Calculated sales value before applying discounts.

Formula:
UnitsSold × UnitPrice

#### Date Extraction

Extracted:

* Day
* Month
* Year

from OrderDate.

#### Price Category

Classified products as:

* Low Price
* High Price

based on Unit Price.

#### Sales Performance

Compared sales against average sales and tagged orders as:

* Good
* Bad

#### Discount Category

Classified discounts as:

* High Discount
* Low Discount

#### Return Review Status

Flagged orders as:

* Review
* OK

based on return status.

#### Region Code

Generated region codes using the first two characters of the region name.

---

## KPI Calculations

The following business metrics were calculated:

* Total Sales
* Total Number of Orders
* Minimum Total Sales
* Maximum Total Sales
* Average Total Sales
* Total Expected Sales
* Total Deductions

---

## Excel Functions Used

* SUM()
* AVERAGE()
* MIN()
* MAX()
* COUNT()
* IF()
* LEFT()
* DAY()
* MONTH()
* YEAR()

---

## Key Insights Generated

* Revenue trends across healthcare products
* Discount impact on profitability
* Identification of high-value transactions
* Return order monitoring
* Regional sales categorization
* Performance benchmarking against average sales

---

## Tools & Technologies

* Microsoft Excel
* Excel Formulas
* Data Analysis
* Business Analytics

---

## Project Outcome

This project demonstrates practical Business Analyst skills in Excel, including data transformation, KPI creation, business rule implementation, conditional logic, and sales performance analysis. The resulting dataset provides actionable insights that support management decision-making and operational efficiency.

---

### Author

Akash GR
