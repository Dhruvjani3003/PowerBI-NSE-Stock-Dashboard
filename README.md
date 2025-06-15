# 📈 Power BI Dashboard - NSE Stock Analysis

This is an interactive Power BI dashboard based on stock data from the **National Stock Exchange of India**.

## ✅ Steps Performed

1. **Data Cleaning**:
   - Removed null/blank rows
   - Dropped unnecessary columns (e.g., `Unnamed`)
   - Handled missing values in price/trade data
   - Standardized column names (e.g., `LTP` → `Last_Traded_Price`)

2. **Data Formatting**:
   - Converted columns to correct data types (e.g., float, date)
   - Removed stocks with zero trade volume
   - Sorted by `Symbol` or date for analysis

3. **Power BI Visualization**:
   - Created dynamic charts, filters, and slicers
   - Designed KPI cards for performance tracking
   - Built drill-down pages for deeper insights

## 📁 Files

- `nse_stock_dashboard.pbix` – Power BI report file
- `National_Stock_Exchange_of_India_Ltd.xls` – Raw data from NSE (optional upload)

## 🛠 Tools Used
- Power BI Desktop
- pandas (for data prep)
- Excel / Power Query
