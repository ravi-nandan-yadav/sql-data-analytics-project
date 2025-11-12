## 📘 SQL Scripts Overview

This repository includes a series of 14 SQL scripts that build and analyze the data warehouse step-by-step.  
They follow a logical order—from initializing the database to generating advanced customer and product reports.

| No. | File | Purpose / Description | Download |
|----:|------|-----------------------|-----------|
| 1 | 00_init_database.sql | Creates core database schema, tables, and relationships | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/00_init_database.sql) |
| 2 | 01_database_exploration.sql | Performs initial data inspection, counts, and integrity checks | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/01_database_exploration.sql) |
| 3 | 02_dimensions_exploration.sql | Examines dimension tables (customers, products, locations) | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/02_dimensions_exploration.sql) |
| 4 | 03_date_range_exploration.sql | Identifies time ranges and date gaps for sales data | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/03_date_range_exploration.sql) |
| 5 | 04_measures_exploration.sql | Calculates base metrics (sales, profit, quantity) | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/04_measures_exploration.sql) |
| 6 | 05_magnitude_analysis.sql | Analyzes revenue magnitude and distribution across segments | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/05_magnitude_analysis.sql) |
| 7 | 06_ranking_analysis.sql | Ranks top customers and products by key metrics | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/06_ranking_analysis.sql) |
| 8 | 07_change_over_time_analysis.sql | Measures month-over-month and year-over-year trends | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/07_change_over_time_analysis.sql) |
| 9 | 08_cumulative_analysis.sql | Builds running totals and cumulative KPIs | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/08_cumulative_analysis.sql) |
| 10 | 09_performance_analysis.sql | Evaluates regional and category-wise performance | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/09_performance_analysis.sql) |
| 11 | 10_data_segmentation.sql | Segments customers/products using behavioral and spend patterns | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/10_data_segmentation.sql) |
| 12 | 11_part_to_whole_analysis.sql | Computes contribution ratios (part-to-whole relationships) | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/11_part_to_whole_analysis.sql) |
| 13 | 12_report_customers.sql | Generates summarized customer-level reports for dashboards | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/12_report_customers.sql) |
| 14 | 13_report_products.sql | Produces product-wise sales and profitability summaries | [Get this file](https://github.com/ravi-nandan-yadav/sql-data-analytics-project/blob/main/13_report_products.sql) |

---

### 🧩 Workflow Summary
1. **Initialization (00)** – Create schema and import data.  
2. **Exploration (01–05)** – Understand structure, dimensions, and key metrics.  
3. **Analysis (06–11)** – Perform ranking, trend, segmentation, and ratio studies.  
4. **Reporting (12–13)** – Build ready-to-use SQL reports for BI tools.
