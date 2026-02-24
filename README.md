# Sales and Business Performance Dashboard (Excel)

This project focuses on analyzing sales, profit, and delivery performance using Excel. The dashboard was built to understand how different regions, product categories, and shipping modes contribute to overall business performance.

---

## Project Overview
The objective of this project was to work with raw sales data and convert it into a structured and interactive dashboard. The analysis helps in identifying trends in sales, understanding profitability across categories, and evaluating delivery performance.

---

## Business Objective
- Evaluate overall business performance using sales and profit data  
- Identify areas with strong and weak profitability  
- Analyze delivery performance across different shipping modes  
- Support better decision-making using data insights  

---

## Dataset Understanding
The dataset includes information related to:
- Orders (sales, profit, quantity)
- Regions and countries
- Product categories and sub-categories
- Shipping modes and delivery timelines  

---

## Excel Sheets and Their Purpose

### 1. Raw Data Sheet
- Contains the original dataset without modifications  
- Used as the base for all analysis  
- Helps maintain data integrity and avoid overwriting source data  

### 2. Cleaned Data Sheet
- Removed duplicates and irrelevant columns  
- Handled missing or inconsistent values  
- Standardized formats (dates, categories, text fields)  
- Prepared the dataset for pivot table analysis  

### 3. Pivot Tables Sheet
- Created multiple pivot tables for:
  - Sales and profit by region  
  - Sales by category and sub-category  
  - Profit distribution across different segments  
  - Shipping mode performance  
- Used to summarize large datasets into meaningful aggregates  

### 4. Dashboard Sheet
- Built the final interactive dashboard  
- Combined charts and key metrics in one place  
- Added slicers for filtering by region, category, and shipping mode  
- Designed layout for easy interpretation  

---

## Technical Implementation

### Data Cleaning
- Used filters and sorting to identify inconsistencies  
- Removed blank or unnecessary fields  
- Standardized date and text formats  

### Pivot Table Analysis
- Aggregated sales, profit, and quantity using pivot tables  
- Used grouping to analyze trends over time  
- Compared performance across regions and product categories  

### Advanced Excel Functions Used
- `SUMIFS` → for conditional aggregation of sales and profit  
- `COUNTIFS` → for counting orders under specific conditions  
- `IF` → for basic logical categorization  
- `VLOOKUP` / `XLOOKUP` → for mapping and referencing data  
- `TEXT` and date functions → for formatting and time-based analysis  

---

## Dashboard and Visualizations

The dashboard includes:
- Bar charts for regional sales and profit comparison  
- Column charts for category-level performance  
- Line charts for sales trends over time  
- Slicers for interactive filtering  

These visuals help in quickly identifying patterns and comparing performance across different dimensions.

---

## Key Insights

- Regions with high sales do not always generate high profit, indicating possible pricing or cost issues  
- The Technology category contributes the highest profit, making it a key driver for the business  
- Some sub-categories generate strong sales but have low profitability, suggesting margin inefficiencies  
- Delivery performance varies across shipping modes, which can impact customer satisfaction and cost  

---

## Conclusion
This project demonstrates how Excel can be used to transform raw business data into meaningful insights. The dashboard provides a clear view of performance and highlights areas where improvements can be made in pricing, product strategy, and delivery operations.

---

## Tools Used
- Microsoft Excel (Pivot Tables, Charts, Formulas, Dashboarding)
