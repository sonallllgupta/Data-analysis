# Sales & Customer Support Performance Analytics

## Project Overview

This project is an Excel-based analytics solution designed to analyze Sales and Customer Support performance in one workbook. It includes data cleaning, KPI analysis, dashboards, pivot tables, record lookup, and what-if revenue analysis.

The project helps understand sales performance, revenue trends, sales pipeline stages, customer support efficiency, ticket resolution, and customer satisfaction.

## Project Objectives

- Analyze overall sales and revenue performance.
- Track deals, deal value, win rate, and lost deals.
- Compare sales performance across owners, regions, products, and lead sources.
- Monitor customer support tickets and their status.
- Analyze first-response time and resolution time.
- Measure customer satisfaction using CSAT.
- Identify blank cells and perform data-quality checks.
- Create dashboards for business reporting.
- Perform record lookup using Record ID.
- Estimate future revenue using what-if analysis.

## Dataset Information

- **Total Records:** 2,000
- **Data Period:** 2025–2026
- **Teams:** Sales and Support
- **Currency:** Indian Rupees (INR)
- **File Format:** Microsoft Excel (.xlsx)

## Project Worksheets

### 1. Raw_Data
Contains the original dataset with 2,000 records and 17 fields. It serves as the source data for the analysis.

### 2. cleaned
Contains the structured dataset prepared for analysis, including additional Month and YEAR fields for time-based reporting.

### 3. summary
Contains formula-based KPI calculations, data-quality checks, monthly revenue summaries, sales-stage analysis, lead-source analysis, and owner-level performance summaries.

### 4. DASHBOARD
Provides a visual overview of Sales and Customer Support performance through KPI cards and charts.

It includes:
- Monthly sales revenue
- Sales pipeline stages
- Support resolution time
- Customer satisfaction (CSAT)
- Support ticket status

### 5. pivot table
Contains pivot-table summaries to compare revenue, deals, deal value, sales owners, months, and sales stages.

### 6. pivot_dashboard
Presents selected Sales and Customer Support indicators through a dashboard based on pivot-table analysis.

### 7. VLOOKUP_Analysis
Allows users to search for a record using its Record ID and retrieve the corresponding record details.

### 8. What_If_Analysis
Provides a revenue-planning model to estimate projected revenue based on an expected growth percentage and compare it with a target.

## Dataset Columns

| Column | Description |
|---|---|
| Record_ID | Unique identifier for each record |
| Date | Date associated with the record |
| Team | Sales or Support |
| Owner | Responsible team member |
| Region | Region associated with the record |
| Customer | Customer name or label |
| Product | Product or service category |
| Lead_Source | Source of the sales lead |
| Sales_Stage | Current sales pipeline stage |
| Deals | Deal-count indicator |
| Deal_Value_INR | Deal value in Indian Rupees |
| Revenue_INR | Revenue in Indian Rupees |
| Tickets | Ticket-count indicator |
| First_Response_Hours | Time taken to respond to a support issue |
| Resolution_Hours | Time taken to resolve a support issue |
| CSAT | Customer Satisfaction Score |
| Status | Sales outcome or support status |

The cleaned worksheet also includes:
- **Month:** Used for monthly analysis.
- **YEAR:** Extracted year for yearly comparisons.

## Key Performance Indicators (KPIs)

### Sales KPIs
- Total Deals
- Won Deals
- Lost Deals
- Total Deal Value
- Total Revenue
- Win Rate
- Monthly Revenue
- Revenue by Owner
- Sales Pipeline by Stage
- Lost Deals by Lead Source

### Customer Support KPIs
- Total Tickets
- Average First-Response Time
- Average Resolution Time
- Average CSAT
- Closed Tickets
- Resolved Tickets
- Support Status Distribution
- Ticket Volume by Owner
- Support Owner Performance

### Data Quality Checks
- Blank-cell counts across source columns
- Validation of data used for analysis
- Identification of missing values

Some fields may be blank because they apply only to Sales or Support records. These blanks should be interpreted according to the relevant team.

## Excel Features and Functions Used

- SUMIF
- SUMIFS
- COUNTIFS
- COUNTBLANK
- AVERAGEIFS
- VLOOKUP
- Excel Tables
- Pivot Tables
- Charts and Dashboards
- KPI Calculations
- What-If Analysis

## How to Use the Workbook

1. Download and open the Excel workbook in Microsoft Excel.
2. Open the DASHBOARD worksheet to review overall performance.
3. Use the summary worksheet to understand KPI calculations and data-quality checks.
4. Explore the pivot table and pivot_dashboard worksheets to compare performance across owners, months, and sales stages.
5. Use VLOOKUP_Analysis to retrieve a record by entering its Record ID in the designated input cell.
6. Use What_If_Analysis to change the expected growth percentage or revenue target and explore different scenarios.
7. If you modify the source data, verify that formulas and table ranges include the new records.
8. Refresh pivot tables in Excel when necessary.

## Business Applications

This project can help businesses:

- Monitor sales performance and revenue trends.
- Identify effective lead sources.
- Compare sales-owner performance.
- Understand customer support workload.
- Improve response and resolution efficiency.
- Monitor customer satisfaction.
- Support data-driven planning and decision-making.

## Important Notes

- This is an Excel-based analytics project, not a live-connected reporting system.
- Dashboard results depend on the source data, formulas, and pivot-table refresh state.
- The what-if model provides hypothetical projections and does not guarantee future revenue.
- KPI definitions and business assumptions should be reviewed before making decisions.

## Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Data Quality
- Data Analysis
- KPI Development
- Sales Analytics
- Customer Support Analytics
- Pivot Tables
- Dashboard Development
- Data Visualization
- Excel Lookup Functions
- What-If Analysis
- Business Reporting



**Project:** Sales & Customer Support Performance Analytics  
**Tool:** Microsoft Excel  
**Focus:** Business Intelligence, Sales Analytics, Customer Support Analytics, and Data-Driven Decision-Making

