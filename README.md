# Egypt Real Estate Market Analytics

An interactive Power BI dashboard analyzing **19,377 real estate listings across 16 regions in Egypt**, covering pricing, price per sqm, down payments, and listing supply.

(Egypt real estate market.png)

## Tools
- **Python (Pandas)**: data cleaning and preparation
- **Power BI**: data modeling and dashboard design
- **DAX**: custom measures (Total Listings, Median Down Payment %)

## Dashboard Overview
- **5 KPI cards**: total listings, typical (median) price, price per sqm, median down payment %, number of locations
- **7 charts**: price per sqm trend by year, listings by region, property type, bedrooms and compound, a regional treemap, and average down payment by region
- **Detailed table**: drill-down view by compound, region, type, size, and price per sqm
- **3 slicers**: region, property type, and availability date

## Dataset
- Fields: price, price per sqm, size (sqm), region, compound, property type, bedrooms, down payment, availability date
- Source: Egyptian Real Estate Listings on Kaggle (https://www.kaggle.com/datasets/hassankhaled21/egyptian-real-estate-listings)

## Files
- `EGYPT_REAL_ESTATE_MARKET.pbix`: Power BI dashboard
- Egypt real estate market: data cleaning code
- `dashboard.png`: dashboard screenshot
