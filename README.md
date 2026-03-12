# 📊 BI Project — Power BI Dashboard

A Power BI report analyzing customer purchasing behavior, satisfaction, and sales performance across different countries and product categories.

---

## 📁 Project Structure

```
BI_PROJECT.pbix       ← Power BI report file
README.md             ← This file
```

---

## 📄 Report Pages

### Page 1 — Sales Overview
Visuals: 4 KPI Cards, 1 Line Chart, 2 Bar Charts, 1 Column Chart, 1 Donut Chart, 1 Pie Chart, 2 Slicers

### Page 2 — Customer Analysis
Visuals: 4 Slicers, 1 Pie Chart, 1 Donut Chart, 1 Clustered Column Chart, 1 Scatter Chart

### Page 3 — KPIs & Satisfaction
Visuals: 1 Gauge, 1 KPI Card, 5 Cards

---

## 🗃️ Data Model

### Source Table
| Table | Description |
|-------|-------------|
| `Sheet1` | Main raw data table — contains customer and purchase details |

### Calculated/Derived Tables
| Table | Description |
|-------|-------------|
| `measurements` | DAX measures table |
| `PurchaseByGender` | Aggregated purchases by gender |
| `PurchaseCountByCategory` | Purchase count grouped by product category |
| `SalesByCountry` | Sales totals per country |
| `SalesByYearCountry` | Sales split by year and country |
| `Satisfaction by Category` | Average satisfaction score per category |
| `SatisfactionByCountry` | Average satisfaction score per country |

---

## 📐 Key Measures (DAX)

| Measure | Description |
|---------|-------------|
| `Total Purchase` | Total purchase value |
| `Total Customers` | Count of unique customers |
| `Avg Purchase Per Customer` | Average spend per customer |
| `Avg Satisfaction` | Average customer satisfaction score |
| `High Value Purchase Count` | Count of high-value transactions |
| `Top Category` | Best-performing product category |

---

## 🔢 Key Columns (from Sheet1)

- `Purchase_Date` / `Purchase Year`
- `Age Group`
- `Gender`
- `modified country`
- `Product_Category`
- `Customer_Satisfaction`

---

## 🚀 How to Open

1. Download `BI_PROJECT.pbix`
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Sign in with your Microsoft account if prompted

---

## 🛠️ Tools Used

- Power BI Desktop (version 2025.04)
- DAX for calculated measures
