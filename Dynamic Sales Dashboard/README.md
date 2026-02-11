# Dynamic Excel Dashboard Project
📌 Project Overview

This project demonstrates the design and development of a dynamic, interactive Excel dashboard that provides high-level business insights through KPIs, charts, and slicers. The dashboard is built with a clear separation between raw data, analytical logic, and presentation, following real-world reporting best practices.

The goal of the dashboard is to allow users to quickly analyze sales performance across different dates, regions, and products without interacting directly with the underlying data.
________________________________________

Tools & Features Used

* Microsoft Excel
* Pivot Tables & Pivot Charts
* KPI Cards
* Slicers & Timeline
* Dynamic chart interactions
* Clean dashboard layout and formatting
________________________________________

Data Model & Structure

The workbook is structured into three logical layers:

* Raw_Data
Contains the original dataset and remains unchanged.

* Pivot_Data
Houses all pivot tables used for calculations and chart sources. This sheet acts as the analytical backend and is not exposed to end users.

* Dashboard
The presentation layer containing KPIs, charts, slicers, and timeline controls.

This separation ensures maintainability, accuracy, and scalability.
________________________________________

Dashboard Features

* Dynamic KPIs
* Total Revenue
* Total Quantity Sold
* Number of Orders
* Average Order Value (AOV)
* Interactive Visuals
* Revenue trend over time
* Revenue by region
* Revenue by product / category
* Top-performing items
* User Controls
* Slicers for Region and Product
* Timeline for Date filtering

All visuals and KPIs update instantly based on selections
________________________________________

Validation & Quality Assurance

The dashboard was validated to ensure:
* KPIs respond correctly to all slicers and timeline filters
* All slicers are connected to the relevant pivot tables
* No pivot tables or backend calculations are visible on the dashboard
* KPI values reconcile with pivot outputs and filtered data
________________________________________

Screenshots

The following screenshots are included in the /screenshots folder:
* Dashboard – Default View
* Dashboard – Filtered View (with slicers applied)
* Pivot_Data Sheet (backend structure)

These provide a quick visual overview without requiring Excel to be opened.
________________________________________

Files Included

* data/raw_sales_data.xlsx – Original dataset
* workbook/dynamic_dashboard.xlsx – Final dashboard workbook
* screenshots/ – Dashboard and model screenshots
________________________________________

Notes

This dashboard is optimized for on-screen interactivity. Printable output focuses on filtered results rather than displaying slicer or timeline controls.
________________________________________
