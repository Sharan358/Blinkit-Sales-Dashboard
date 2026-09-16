# Blinkit Grocery Sales Dashboard

An interactive Power BI dashboard analyzing grocery sales performance using a Kaggle dataset of **8,523 records**, built with fully custom DAX measures and a cleaned data model via Power Query.

## Overview

This project explores sales trends across the Blinkit grocery dataset to surface actionable insights on outlet performance, item categories, and sales distribution. It was built end-to-end — from raw data cleaning to a polished, presentation-ready dashboard.

## Features

- **Data Cleaning & Transformation** — Standardized and cleaned raw data using Power Query (handling missing values, inconsistent categories, and outlet metadata)
- **Custom DAX Measures** — KPIs and calculated metrics built from scratch for sales, item, and outlet-level analysis
- **Interactive Visuals** — Slicers and cross-filtering for outlet type, location, item category, and fat content
- **Business Insights** — Highlights top-performing outlets, high-margin item categories, and sales distribution patterns

## Dataset

- **Source:** [Kaggle — Blinkit Grocery Sales dataset](https://www.kaggle.com/)
- **Size:** 8,523 rows
- **Fields:** Item identifiers, item type, MRP, outlet identifiers, outlet size/type/location, and sales figures

## Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard design & visualization |
| Power Query | Data cleaning & transformation |
| DAX | Custom measures & calculated columns |

## Repository Structure

```
├── data/               # Raw and cleaned dataset
├── dashboard/          # .pbix Power BI file
├── report/             # Project report (PDF)
├── screenshots/        # Dashboard preview images
└── README.md
```

## Key Insights

- **Fruits & Vegetables (₹178K) and Snack Foods (₹175K)** are the top-selling item categories, together accounting for over 25% of total sales
- **Regular fat content items outsell Low Fat items** — 64.6% (₹776.32K) vs. 35.4% (₹425.36K) of total sales
- **Supermarket Type1 outlets drive the majority of revenue** (₹7.87L of ₹12.01L total), far outpacing Grocery Stores and other supermarket types
- **Tier 3 locations lead in sales** (₹472.13K), followed by Tier 2 (₹393.15K) and Tier 1 (₹336.40K) — showing smaller cities contribute the most revenue
- **Medium-sized outlets generate the largest share of sales** (42.27%), ahead of Small (37.01%) and High (20.72%) outlet sizes
- Sales by establishment year peaked in **2018 (₹0.20M)**, with most other years holding steady around ₹0.13M

## Author

**Amudala Sharan Sai**
GitHub: [github.com/Sharan358](https://github.com/Sharan358)

