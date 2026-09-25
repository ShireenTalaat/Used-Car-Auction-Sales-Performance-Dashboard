# Used-Car-Auction-Sales-Performance-Dashboard

## 📊 Overview

This repository contains a **Used Car Auction Sales Performance Dashboard** built with **Microsoft Power BI**. The dashboard provides a comprehensive, at-a-glance view of key sales metrics, revenue trends, profit margins, and geographic distribution for used car auction data across the United States.

---

## 🖼️ Dashboard Preview

![Dashboard Preview](dashboard.png)

---

## 📈 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| **Total Sales** | 559K |
| **Total Revenue** | 8 Billion |
| **Total Records** | 14.26K |
| **Total Profit Margin** | -88 Million |

---

## 📋 Dashboard Components

### 1. KPI Cards with Trend Lines
- **Total Sales** – Overall number of cars sold with monthly trend.
- **Total Revenue** – Total revenue generated with monthly trend.
- **Total Profit Margin** – Net profit/loss with monthly trend (currently showing a negative margin of -88M).

### 2. Avg. Profit Margin % by Month
- Line chart tracking the average profit margin percentage from **January through December**.
- Highlights seasonal fluctuations, with a notable dip around **April**.

### 3. Max Selling Price by Month
- Line chart showing the **maximum selling price** per month, ranging from **$0M to $0.2M**.

### 4. Total Sales & Revenue by Seller (Table)
- Detailed breakdown of **12 major sellers** including:
  - Avis Corporation
  - Enterprise Vehicle Exchange/Rental
  - Ford Motor Credit Company LLC
  - GE Fleet Services
  - Hyundai Motor Finance
  - JPMorgan Chase Bank N.A.
  - Nissan Infiniti LT
  - Santander Consumer
  - TDAF Remarketing
  - The Hertz Corporation
  - Wells Fargo Dealer Services
- **Total Sales:** 137,386 | **Total Revenue:** $1,967,896,830

### 5. State and Selling Price (Choropleth Map)
- Interactive **Azure Maps** visualization of the United States.
- Color-coded by **selling price ranges** (from $1 to $300+).
- Data sourced from **OpenStreetMap (OSM)** and **TomTom**.

### 6. Top 5 Sold Cars by Body Type
| Body Type | Sales Volume |
|---|---|
| Sedan | 0.24M |
| SUV | 0.14M |
| Hatchback | 0.03M |
| Minivan | 0.03M |
| Coupe | 0.02M |

### 7. Top 5 Car Colors
| Color | Sales Volume |
|---|---|
| Black | 0.11M |
| White | 0.11M |
| Silver | 0.08M |
| Gray | 0.08M |
| Blue | 0.05M |

### 8. Top 5 Car Makes
| Make | Sales Volume |
|---|---|
| Ford | 94K |
| Chevrolet | 61K |
| Nissan | 54K |
| Toyota | 40K |
| Dodge | 31K |

### 9. Top 5 Sellers
| Seller | Sales Volume |
|---|---|
| Nissan Infiniti | 20K |
| Ford Motor | 19K |
| The Hertz Corporation | 18K |
| Santander Consumer | 15K |
| Avis Corporation | 13K |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization
- **Microsoft Azure Maps** – Geographic/map visualization
- **DAX** – Data modeling and calculated measures
- **Power Query (M)** – Data transformation and ETL

---

## 📁 Project Structure

```
used-car-auction-dashboard/
├── cars.jpg          # Dashboard screenshot
├── data/
│   └── used_car_sales.csv # Raw dataset (if included)
├── reports/
│   └── dashboard.pbix     # Power BI report file
└── README.md              # This file
```

---


## 📊 Key Insights

- **Sedans** dominate the used car auction market, accounting for the highest sales volume (0.24M).
- **Black and White** are the most popular car colors, each representing 0.11M in sales.
- **Ford** is the top-selling car make with 94K units sold.
- The dashboard reveals a **negative profit margin (-88M)**, indicating potential areas for cost optimization.
- **Nissan Infiniti** leads among individual sellers with 20K sales.
- Geographic data shows varied selling prices across U.S. states, useful for regional pricing strategies.

----

> *Built with ❤️ using Microsoft Power BI*
