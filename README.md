# 🛒 Superstore Sales & Profitability Analysis

An end-to-end data analysis project built in **Microsoft Excel**: from a raw 9,995-row sales file to a cleaned dataset, pivot-table analysis, and an interactive dashboard with business recommendations.

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)
![Records](https://img.shields.io/badge/Records-9%2C994-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-orange)

---

## 📌 Overview

The goal was to practise the complete analysis workflow in Excel:

1. Understand and clean a raw sales dataset
2. Transform it into a structured, analysis-ready table
3. Analyse it with formulas and pivot tables
4. Present the results in an interactive dashboard
5. Turn the findings into clear recommendations

**Dataset:** Superstore sales data (CSV) with 21 columns covering orders, shipping, customers, products and financials (sales, quantity, discount, profit). After cleaning: **9,994 unique records**, **4 regions**, **3 product categories**, orders from **2014 to 2017**.

---

## 🛠️ Tools & Techniques

| Area | What was used |
|---|---|
| **Data cleaning** | Remove Duplicates, Go To Special / COUNTBLANK (missing value check), Format Cells (data type conversion) |
| **Text functions** | TRIM, CLEAN, PROPER, UPPER, LOWER, LEFT, MID, RIGHT, LEN, CONCAT |
| **Transformation** | Excel Tables (Ctrl + T), table styles, conditional formatting, freeze panes, filters |
| **Formulas** | SUM, AVERAGE, MIN, MAX, COUNT, IF, DATE, NOW |
| **Analysis & visuals** | 4 pivot tables, 4 pivot charts, 4 slicers, 4 KPI cards, combined dashboard |

---

## 🔄 Project Workflow

**1. Data understanding** – Reviewed the domain, columns, data types and data quality.

**2. Data cleaning**
- No missing values found
- Removed **7 duplicate records**
- Converted date and sales columns to correct data types
- Standardised text with Excel text functions

**3. Data transformation** – Converted to an Excel Table with banded styling, conditional formatting, frozen header row/first column and filters.

**4. Analysis** – Calculated key figures with formulas and built pivot tables by sub-category, region, quantity and category.

**5. Visualisation** – Built four pivot charts, four slicers (Segment, Region, Ship Mode, Category) and four KPI cards on a single dashboard.

---

## 📊 Key Results

| Metric | Value |
|---|---|
| Total Sales | **$2,297,200.86** |
| Total Profit | **$286,397.02** |
| Profit Margin | **~12.5%** |
| Total Quantity Sold | **37,873 units** |
| Total Orders | **5,009** |
| Average Sale Amount | **$229.86** |

---

## 🔍 Key Insights

- **West is the strongest region:** 31.6% of sales, 37.9% of profit, 14.9% margin.
- **Central is the weakest:** only a 7.9% margin, driven by the highest average discount (24% vs 10.9% in the West).
- **Technology leads** with ~$836K in sales (36.4%) and the most profit ($145K).
- **Furniture earns just a 2.5% margin** despite ~32% of total sales.
- **Discounting is the main cause of losses:**
  - No discount → 29.5% margin
  - 20–40% discount → −15.3% margin
  - 40%+ discount → −77.4% margin
  - About **18.7% of order lines (1,871)** lose money, totalling roughly **$156K** in losses.
- **Loss-making sub-categories:** Tables (−8.6%), Bookcases (−3.0%), Supplies (−2.5%).
- **Top sellers:** Phones ($330K) and Chairs ($328K); **Copiers** lead profit ($55.6K, 37.2% margin).
- **Seasonality:** September to December brings ~52% of yearly sales; November and December peak.
- **Growth:** Sales grew ~51% and profit ~89% from 2014 to 2017 with a steady ~13% margin.
- **Order size:** Orders of 2–5 units make up ~63% of sales.

---

## ✅ Business Recommendations

1. **Control discounts** – require approval above 20% and stop discounts of 40% or more.
2. **Review Tables, Bookcases and Supplies** – adjust pricing, supplier costs or product range.
3. **Fix the Central region** – review its discount policy and Furniture sales; investigate Texas, Ohio and Pennsylvania.
4. **Look at Machines** – a 1.8% margin on $189K of sales needs a pricing/cost review.
5. **Protect the strengths** – keep investing in Technology, Paper and the West region.
6. **Plan for seasonality** – build inventory and marketing around the Sep–Dec peak.

---

## 📁 Repository Contents

```
├── superstore_sales___profitability_analysis.xlsx   # Excel workbook (cleaned data, pivots, dashboard)
├── superstore_sales___profitability_analysis.pdf    # Full project report with screenshots
├── super_store___profitability_analysis.pptx        # Presentation slides
└── README.md
```

---

## 🚀 How to Use

1. Download the `.xlsx` workbook and open it in Microsoft Excel (2016 or later recommended).
2. Go to the dashboard sheet and use the **slicers** (Segment, Region, Ship Mode, Category) to filter.
3. Read the PDF report for the step-by-step process, screenshots and full insights.

---

## 🔮 Future Scope

- Add a **Profit Margin % KPI card**
- Add a **Year slicer**
- Add a **monthly sales trend** chart
- Add a **discount vs profit** chart

---

## 🎓 Skills Demonstrated

Data cleaning · Data transformation · Excel formulas · Pivot tables & charts · Slicers · KPI dashboards · Business insight reporting

---

## 👤 Author

**Saran Kumar M**
GitHub: [@itzsaran10-bot](https://github.com/itzsaran10-bot)
LinkedIn: _add your profile link here_

⭐ If you found this project useful, consider giving it a star!
