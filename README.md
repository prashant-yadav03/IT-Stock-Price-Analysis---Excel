# 📊 Stock Price Analysis of IT Companies (2022–2023)

Welcome to the Excel-based data analysis project where I explored the performance of major IT companies over a two-year period. This project was done as a case study simulating a real-world business scenario in a financial services firm and showcases my Excel data handling, visualization, and analytical skills.

---

## 📁 Project Overview

**Objective:**  
Analyze stock price data of leading IT companies to identify investment insights based on volatility, financial health indicators (PE/PB ratios), and market capitalization. The final goal was to assist in informed investment decisions.

**Tools Used:**  
- Microsoft Excel (primary tool for data formatting, analysis, and visualization)

---

## 📚 Dataset Description

The dataset contains daily stock performance data for major IT companies with the following features:

| Column | Description |
|--------|-------------|
| `Date` | Trading date |
| `Company Name`, `Ticker Symbol` | Identification info |
| `Open`, `High`, `Low`, `Close`, `Adj Close` | Stock prices during the trading day |
| `Volume` | Shares traded |
| `Market Capitalization`, `PE Ratio`, `PB Ratio`, `Dividend Yield (%)`, `Beta` | Financial metrics |
| `52-Week High/Low`, `EPS`, `Revenue`, `Net Income`, `Operating Margin (%)` | Company performance indicators |
| `Debt-to-Equity`, `Free Cash Flow`, `Dividend`, `Industry` | Financial structure and sector info |

---

## 🧰 Project Activities

### 🖋️ Part 1: Data Cleaning & Formatting

- Frozen top row for better navigation.
- Applied proper number formatting (e.g., two decimals for price, commas for large numbers).
- Uniform date format (`dd-mm-yyyy`) and auto-fit column widths.
- Bold & center-aligned headers.
- Conditional formatting:
  - Green if `Close Price > $1000`, red if `< $500`.
  - Market Cap bands: Green (> $10B), Yellow ($5B–10B), Red (< $5B).
- Font standardization (Calibri 11pt) and cell borders added.
- Light shading for key columns like `Close Price`, `PE Ratio`, and `Dividend Yield`.
- Sheet renamed to **Stock Prices IT**.

---

### 📈 Part 2: Analysis Using Formulas & Logic

- **Volatility Analysis**:
  - Highlighted stocks with high daily volatility (`High - Low > $100`).
- **Derived Metrics**:
  - Added `Daily Price Change` column (`Close - Open`).
- **Insights via Conditional Formatting**:
  - Highlighted:
    - `Dividend Yield > 4%`
    - `PE Ratio < 20`
    - `Beta > 1.5` (high volatility)
    - Negative `Daily Price Change`
- **Aggregate Metrics**:
  - `COUNTIF`: Trading days with volume > 10M
  - `AVERAGEIF`: Average close price per company
  - `MAX`, `MIN`: Highest/lowest beta and close prices
  - `SUMIF`: Total revenue per company
  - `COUNTIFS`: Number of companies per industry and trading days in specific price ranges
  - `AVERAGE`: Overall average PE ratio

---

## 📊 Key Takeaways

- Identified undervalued stocks using PE and PB ratios.
- Benchmarked high-performing vs. underperforming companies.
- Volatility and dividend yield analysis helped in risk/reward profiling.
- Created a dashboard-ready Excel file with user-friendly formatting.

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `IT_stock_prices_analysis.xlsx` | Main Excel project file containing all formatting and analysis |
| `IT_stock_prices_dataset.xlsx` | Raw Excel file containing IT Stock Data |

---

## ✅ Skills Demonstrated

- Data Cleaning & Formatting in Excel  
- Logical Formulas & Conditional Formatting  
- Aggregation and Filtering with COUNTIFs, AVERAGEIF, SUMIF  
- Dashboard Presentation Techniques  
- Real-world business case application of stock analysis  

---

## 🚀 Future Scope

- Integration with Power BI for dynamic dashboards  
- Time-series analysis using Excel charts or Python  
- Predictive modeling for stock trends
