# Pharmacy Sales Analysis Dashboard

An Excel-based sales analysis project focused on exploring pharmacy
product sales, sales transactions, shipped boxes, and performance across
salespeople and locations.

## Project Overview

This project uses a pharmacy sales dataset to build an interactive Excel
dashboard. The dashboard is designed to help users explore sales
performance and compare results across different products, salespeople,
and locations.

## Dashboard Features

-   **Total Sales** -- total sales value for the selected data.
-   **Sales Transactions** -- number of sales records.
-   **Boxes Shipped** -- total quantity of boxes shipped.
-   **Average Transaction** -- average sales value per transaction.
-   Interactive filters (Slicers) for:
    -   Product
    -   Sales Person
    -   Governorate / City

The KPI cards are intended to update when the dashboard filters are
changed.

## Tools Used

-   Microsoft Excel
-   Excel Tables
-   Pivot Tables
-   Pivot Charts
-   Slicers
-   Excel formulas

## Data Preparation

The analysis workflow included:

1.  Reviewing the source data and column types.
2.  Checking for duplicate records.
3.  Cleaning text fields.
4.  Validating dates, quantities, and sales amounts.
5.  Building Pivot Tables to summarize the data.
6.  Creating KPI indicators and interactive dashboard filters.

## Dataset Fields

The source dataset contains the following fields (location labels may be
adapted in the working copy):

-   `Date`
-   `Product`
-   `Sales Person`
-   `Boxes Shipped`
-   `Amount`
-   `Country` / `Governorate` / `City`

> **Data note:** Use only anonymized or sample data in this public
> repository. Do not upload patient, customer, employee, or other
> confidential business information.

## Dashboard Preview

Add a screenshot of your completed Excel dashboard to the `images`
folder and name it `dashboard-preview.png`.

When the image is uploaded, this section will display it:

`images/dashboard-preview.png`

## Project Structure

``` text
Pharmacy-Sales-Analysis/
├── README.md
├── Pharmacy_Sales_Analysis.xlsx
└── images/
    ├── dashboard-preview.png
    └── project-cover.png
```

Update the Excel filename and image filenames if your actual files use
different names.

## How to Use

1.  Download the Excel workbook from this repository.
2.  Open it in Microsoft Excel.
3.  Go to the Dashboard sheet.
4.  Use the slicers to filter by product, salesperson, or location.
5.  Review how the KPI indicators and charts respond to the selected
    filters.

## Future Improvements

-   Rebuild the dashboard in Power BI.
-   Add more business insights and trend analysis.
-   Publish an interactive online version where appropriate.

## Author

Created as a practical portfolio project to demonstrate data cleaning,
analysis, and dashboard development with Microsoft Excel.
