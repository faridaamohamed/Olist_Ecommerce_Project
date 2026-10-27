# Olist E-Commerce Data Analysis & Excel Dashboard

## Project Overview

This project focuses on analyzing the Brazilian E-Commerce Public Dataset by Olist to explore sales performance, customer experience, payment behavior, and geographic performance.

The project follows an end-to-end data analysis workflow, from data cleaning and transformation to data modeling, exploratory analysis, interactive dashboard development, and business recommendations.

## Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains approximately 100,000 orders placed between 2016 and 2018. It includes information about orders, customers, products, sellers, payments, reviews, and geographic locations.

The original dataset is available on Kaggle. Please refer to the source page for its license and usage conditions.

## Tools & Technologies

- **Microsoft Excel** — Data analysis and dashboard development
- **Power Query** — Data cleaning and transformation
- **Excel PivotTables** — Aggregation and exploratory analysis
- **Excel Data Model** — Managing relationships between tables
- **Excel Slicers** — Interactive filtering and dashboard navigation

## Project Workflow

1. **Data Cleaning & Preparation**
   - Inspected data quality and missing values.
   - Reviewed date fields and data types.
   - Investigated orders without matching product records.
   - Prepared data for analysis using Power Query.

2. **Data Modeling**
   - Connected related tables using appropriate keys.
   - Organized the data model to support cross-table analysis.
   - Used distinct counts where appropriate to avoid double-counting orders.

3. **Exploratory Data Analysis**
   - Analyzed sales trends and product category performance.
   - Compared payment methods by order count and payment value.
   - Examined order approval and delivery times.
   - Explored customer satisfaction and delivery delays.
   - Compared sales, customer counts, and delivery performance across Brazilian states.

4. **Interactive Dashboard Development**
   - Created three interactive Excel dashboard pages.
   - Added KPI cards, charts, slicers, and navigation elements.
   - Designed the dashboards to present key metrics and trends clearly.

## Dashboard Pages

### 1. Sales Performance
- Monthly sales performance
- Sales by product category
- Average order value
- Payment method analysis

### 2. Customer Experience
- Order approval time
- Average delivery time
- Customer sales performance
- Delivery delays and review scores

### 3. Geographic Performance
- Sales by state
- Customer distribution
- Geographic delivery performance
- Identification of regions requiring further investigation

## Key Findings

- **Payment Methods:** Debit card payments recorded the lowest order count and payment value among the analyzed payment methods.
- **Product Categories:** `beleza_saude` was the highest-performing category by sales, while `seguros_e_servicos` recorded the lowest sales.
- **Monthly Sales:** October 2016 showed higher sales than September and December in the available data. November 2016 was not represented in the current monthly analysis and requires further validation.
- **Customer Experience:** Average order approval time was approximately 10 hours, while average delivery time was approximately 13 days.
- **Delivery & Satisfaction:** Late deliveries were associated with lower customer review scores.
- **Geographic Performance:** São Paulo (SP) had the highest customer concentration, while states such as Amapá (AP) and Roraima (RR) showed low sales and customer counts alongside high average delivery times.

## Business Recommendations

- Evaluate the cost and customer impact of maintaining low-usage payment methods before making changes.
- Review inventory and marketing strategies for high- and low-performing product categories.
- Investigate the factors behind October's sales performance and assess whether they can be replicated.
- Review order approval processes and delivery operations to identify opportunities to reduce processing and delivery times.
- Improve retention through targeted offers for high-value customers.
- Investigate logistics challenges in underserved states and test targeted marketing initiatives before making major expansion decisions.

## Data Quality Considerations

- Investigate the difference between the number of distinct orders in the `orders` and `order_items` tables.
- Validate the absence of November 2016 from the current monthly analysis before drawing conclusions about sales activity.
- Interpret geographic comparisons carefully, considering differences in order volume and data coverage.

## Project Files

- `Olist_Excel_Dashboard.xlsx` — Final interactive Excel dashboard and analysis.
- `Screenshots/` — Dashboard previews.

## Author

Data Analysis Portfolio Project

**Dataset credit:** Olist — Brazilian E-Commerce Public Dataset, hosted on Kaggle.
