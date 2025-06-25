# 📊 Excel Sales Margin Dashboard (Dynamic + FP&A Focus)

A dynamic Excel dashboard built to demonstrate advanced business analytics, FP&A techniques, and Excel automation using functions like `SUMPRODUCT`, `XLOOKUP`, dynamic dropdowns, and helper columns for optional filtering.

---

## 🔍 Overview

This project simulates a real-world FP&A dashboard that tracks product sales performance, profit margins, and sales rep activity across multiple regions, products, and time periods.

Key features:
- ✅ **Dynamic filtering:** Select any, some, or no dropdown filters to slice the data across Region, Sales Rep, Product, and Month
- ✅ **XLOOKUP detail view:** See exact order data by selecting an Order ID
- ✅ **Weighted KPIs:** Calculated using `SUMPRODUCT` to account for volume-based pricing
- ✅ **Margin analysis:** Compare actual vs. target margins across dimensions
- ✅ **Sparklines:** Visualize monthly unit sales trend
- ✅ **Top/Bottom 3 products by margin**

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `sales_margin_dashboard_with_dynamic_menus.xlsx` | Fully functional Excel workbook with dynamic dashboard |
| `data/` | Contains mock dataset with 300+ transaction records |
| `README.md` | Project description and usage instructions |

---

## 📈 Dashboard Features

### Input Filters (any combination):
- Region
- Sales Rep
- Product
- Month
- Order ID (auto-populated based on other filters)

### KPI Outputs:
- Total Units Sold
- Weighted Avg Unit Price
- Weighted Avg Cost
- Total Sales
- Total Cost
- Margin and Margin %
- Target Margin % (Avg)
- Sparkline trend by month

### Formula Highlights:
- `SUMPRODUCT` for weighted averages and flexible logic
- `XLOOKUP` for precise transaction retrieval
- `FILTER` + `UNIQUE` for dynamic dropdown menus
- Boolean flags (`inc_combo`, etc.) for filter inclusion logic

---

## 🧠 Skills Demonstrated

- 📊 Advanced Excel functions (`XLOOKUP`, `SUMPRODUCT`, `FILTER`, `IF`, `UNIQUE`, `LET`)
- 💼 FP&A metrics: Margin, Target vs. Actual, Weighted Sales/Cost
- 🧩 Dynamic UX: Dependent dropdowns, optional filters
- 🛠 Excel dashboard design: Layout, formatting, sparklines

---

## 🛠 How to Use

1. Open `sales_margin_dashboard_with_dynamic_menus.xlsx`
2. On the **Dashboard** sheet:
   - Use dropdowns to filter by Region, Rep, Product, Month
   - Select an Order ID to view its details
3. Watch the KPIs and charts update instantly
4. Explore top/bottom margin performers

---

## 📚 Inspired By

- Real-world financial planning and sales ops workflows  
- Excel-based BI dashboards used in FP&A teams  
- Concepts similar to what’s found in Power BI / Tableau slicers  

---

## 🚀 Future Improvements

- Add slicers or pivot charts for visual flexibility
- Export-ready PDF or report sheet
- Connect to live Power BI or Tableau dashboard
- Automate mock data generation with Python

---

## 👤 Author

John Carrier  
[LinkedIn](https://www.linkedin.com) · [GitHub](https://github.com) · [Portfolio](https://yourportfolio.com)

---

## 📝 License

This project is open-source and free to use under the MIT License.
