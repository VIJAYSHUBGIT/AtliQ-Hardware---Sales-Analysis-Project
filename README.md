# AtliQ Hardware - Sales Analysis Project

![AtliQ Hardware Logo]( https://media.licdn.com/dms/image/C4D0BAQGbP1rKTsdruw/company-logo_200_200/0/1630545236414?e=2147483647&v=beta&t=YiJe-qqti4oMosazls7BI0CzChwaBhaaC6aDXY1KdTk )

## Project Overview

AtliQ Hardware is a renowned computer hardware company specializing in manufacturing various computer parts and peripherals. The company operates across four major regions: APAC (Asia Pacific), EU (Europe), NA (North America), and LATAM (Latin America).

## Task

This project aimed to accomplish the following tasks:
- Generate monthly Gross Sales Report.
- Identify the financial position of the company over various fiscal years.
- Identify Top Products, Markets, and Customers.

## Dataset Overview

To achieve the project objectives, the following steps were undertaken:
- Loaded a million rows of data into a MySQL database and executed multiple queries.
- Analyzed the following tables to derive key insights using SQL concepts:
  - `dim_customer`
  - `dim_date`
  - `dim_product`
  - `fact_act_est`
  - `fact_forecast_monthly`
  - `fact_freight cost`
  - `fact_gross_price`
  - `fact_manufacturing_cost`
  - `fact_post_invoice_deductions`
  - `fact_pre_invoice_deductions`
  - `fact_sales_monthly`

## SQL Components Developed

### User-Defined Functions
1. **get_fiscal_year**: Created to retrieve fiscal year information.
2. **get_fiscal_quarters**: Implemented to fetch fiscal quarters.

### Stored Procedures
1. **get_market_badge**: To obtain market-related information.
2. **get_monthly_gross_sales_for_given_customer**: Used to retrieve monthly gross sales for a specified customer.
3. **get_top_n_customers_by_net_sales**: Developed to identify top customers based on net sales.
4. **get_top_n_markets_by_net_sales**: Created to find top markets based on net sales.
5. **get_top_n_products_by_net_sales**: Implemented to determine top products based on net sales.

### Database Views
1. **gross_sales**: View displaying gross sales information.
2. **net_sales**: View presenting net sales data.
3. **sales_postinvoice_discount**: View providing post-invoice discount details.
4. **sales_preinvoice_discount**: View showing pre-invoice discount information (similar to the previous view).

## Information Section

**LinkedIn Profile**: [VIJAY SINGH ]( https://www.linkedin.com/in/vijay-singh-456a63285/)
