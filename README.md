# Bike Buyers Sales Analysis Dashboard | Excel

An interactive Excel dashboard analyzing customer characteristics associated with bike purchases. This project uses data cleaning, calculated fields, PivotTables, charts, and slicers to identify patterns in customer income, gender, commute distance, age, education, marital status, and region.

## Dashboard Preview

[View the Excel Project Workbook](Training_Project_Excel.xlsx)

> The workbook includes the raw data, cleaned working sheet, PivotTables, and interactive dashboard.

## Project Objective

The purpose of this project is to analyze customer data from a bike retailer and identify the factors that appear to influence whether a customer purchases a bike.

The analysis focuses on questions such as:

- Does income differ between customers who purchased a bike and those who did not?
- Does gender have an observable relationship with average customer income and bike purchases?
- Which commute distances are associated with the highest and lowest purchase counts?
- Which age group has the greatest number of bike purchases?
- How do marital status, education, and region affect the dashboard results?

## Dataset

The dataset contains **1,000 customer records** from a bike retailer.

### Main Fields

| Field | Description |
|---|---|
| Marital Status | Customer marital status |
| Gender | Customer gender |
| Income | Customer annual income |
| Children | Number of children |
| Education | Customer education level |
| Occupation | Customer occupation |
| Home Owner | Whether the customer owns a home |
| Cars | Number of cars owned |
| Commute Distance | Customer commute-distance category |
| Region | Customer region |
| Age | Customer age |
| Purchased Bike | Whether the customer purchased a bike (`Yes` / `No`) |

## Workflow

### 1. Raw Data

The original data is stored in the `bike_buyers` worksheet. It contains the unmodified customer records used as the starting point for the analysis.

### 2. Data Cleaning

A separate working sheet was created to prepare the data for analysis.

Cleaning and preparation steps included:

- Expanded abbreviated marital-status values:
  - `M` → `Married`
  - `S` → `Single`
- Expanded abbreviated gender values:
  - `M` → `Male`
  - `F` → `Female`
- Created an **Age Brackets** calculated column to group customers into broader age categories:
  - Adolescent
  - Middle Age
  - Old
- Prepared the cleaned data for PivotTable analysis and dashboard reporting.

### 3. PivotTable Analysis

PivotTables were created to summarize purchase behavior and compare customer groups.

The analysis includes:

- Average income by gender, separated by bike purchase status.
- Count of bike purchases by commute distance.
- Count of bike purchases by age bracket.

### 4. Interactive Dashboard

An interactive dashboard was created in Excel to make the insights easier to explore.

The dashboard includes:

- Average income per purchase by gender.
- Customer commute-distance analysis.
- Customer age-bracket analysis.
- Interactive filters using slicers.

## Dashboard Features

### Charts

| Chart | Purpose |
|---|---|
| Average Income per Purchase by Gender | Compares average income for male and female customers based on whether they purchased a bike |
| Customer Commute Distance | Shows purchase behavior across commute-distance categories |
| Customer Age Brackets | Shows customer purchase counts by age group |

### Interactive Slicers

The dashboard includes slicers that allow users to filter all connected charts at the same time:

- Marital Status
- Education
- Region

For example, a user can select a specific region and education level to see how income, commute distance, and age patterns change for that customer group.

## Key Insights

- The overall bike purchase rate was **48.1%**, with **481 out of 1,000 customers** purchasing a bike.
- Customers with a short commute of **0–1 miles** were the most likely to purchase a bike:
  - **200** customers purchased a bike.
  - **166** customers did not purchase a bike.
- Customers with a long commute of **10+ miles** were much less likely to purchase a bike:
  - **33** customers purchased a bike.
  - **78** customers did not purchase a bike.
- Commute distance appears to be a strong factor associated with bike-purchase behavior. Customers with shorter commutes showed stronger purchase activity than customers with longer commutes.
- Middle-aged customers represented the largest group among both buyers and non-buyers.
- Middle-aged customers also had the highest raw count of bike purchases, with **388 purchases**.
- Average income among customers who purchased bikes was slightly higher for males than females:
  - Male buyers: **$60,124**
  - Female buyers: **$55,774**

## Business Recommendations

Based on this analysis, the retailer could consider:

- Targeting customers with short commute distances, especially customers commuting **0–1 miles**.
- Creating marketing campaigns focused on middle-aged customers because they represent the largest customer segment and the highest raw number of purchases.
- Investigating the needs of customers with commutes of **10+ miles**, where purchase activity is significantly lower.
- Using dashboard slicers to identify high-potential customer segments by region, education level, and marital status.
- Creating segmented promotions based on commute distance, income, and demographic characteristics.

## Tools Used

- Microsoft Excel
- Data cleaning and transformation
- Calculated columns
- PivotTables
- PivotCharts
- Excel charts
- Slicers
- Interactive dashboard design

## Project Structure

```text
Training Project Excel.xlsx
│
├── bike_buyers
│   └── Original dataset containing 1,000 customer records
│
├── Working Sheet
│   └── Cleaned data, expanded labels, and calculated age brackets
│
├── Pivot Table
│   └── PivotTables used for analysis and dashboard charts
│
└── Dashboard
    └── Interactive Excel dashboard with charts and slicers
```

## How to Use the Dashboard

1. Download the Excel workbook from this repository.
2. Open the workbook in Microsoft Excel.
3. Navigate to the `Dashboard` sheet.
4. Use the slicers for **Marital Status**, **Education**, and **Region**.
5. Review how the charts change based on the selected customer segment.
6. Clear slicer filters to return to the complete dataset view.

## File

- `Training Project Excel.xlsx` — Full Excel workbook containing the raw data, cleaned working sheet, PivotTables, and interactive dashboard.

## Author

**Mohab Adel**

Aspiring Data Analyst with experience in Excel, SQL, Tableau, dashboard design, data cleaning, data visualization, and real-estate data research.

- GitHub: [mohabadel10](https://github.com/mohabadel10)
- Project Repository: [Bike Buyers Sales Analysis Dashboard](https://github.com/mohabadel10/Training-Project-Excel)
