# salz-bakes-analysis
Bakery order and revenue analysis — Power BI dashboard, Excel data
# Salz Bakes — Order & Revenue Analysis

## Overview
Power BI dashboard built on order data from Salz Bakes, a home bakery 
operating across Delhi NCR. Covers product performance, channel mix, 
and area-level revenue from January 2022 to June 2023.

## Tools Used
- **Power BI** — interactive dashboard
- **Microsoft Excel** — data cleaning, structuring, and preparation

## Key Findings
- 454 total orders generated ₹3,65,074 in revenue, with an average order 
  value of ₹804.13
- Cake is the clear top performer, making up 46% of category revenue — 
  more than Cookies & Brownies, Boxes & Assortments, Breads & Pastries, 
  and Cheesecake combined
- Direct customer orders account for 62% of total volume (283 orders), 
  with the rest split between Café/Coffee Shop, Corporate & Private 
  Events, and Local Bakery/Cloud Kitchen channels
- Shaheen Bagh leads all delivery areas by revenue at ₹52K, with Jasola 
  and Batla House following — South-East Delhi areas dominate the top 10
- Built a top-areas bar chart in place of a geographic map for this 
  version, since Power BI's built-in geocoding doesn't reliably resolve 
  Delhi neighbourhood-level names. A separate map-based version of this 
  dashboard exists in Tableau, where area-level coordinates were mapped 
  manually to work around the same issue

## Dashboard Sections
- **KPI Row:** Total Orders, Total Revenue, Average Order Value, Top Category
- **Orders and Revenue Trend:** Monthly line chart tracking order count 
  and revenue, Jan 2022 to Jun 2023
- **Revenue by Product Category:** Pie chart across all six product lines
- **Top 10 Areas by Revenue:** Bar chart ranking delivery zones
- **Orders by Channel Type:** Pie chart across four order channels

Filters available: Year, Quarter

## Repository Structure
| File | Description |
|------|--------------|
| `data/Bakery_AnalysisData_Cleaned.xlsx` | Cleaned order-level dataset |
| `dashboard/SalzBakes_PowerBI_Report.pbix` | Power BI dashboard file |
| `screenshots/dashboard_overview.png` | Full dashboard preview |

## How to View
- Download `dashboard/SalzBakes_PowerBI_Report.pbix` and open in 
  **Power BI Desktop** (free)
- Or check the `screenshots/` folder for a quick preview without 
  downloading anything
