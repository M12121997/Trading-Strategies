# TSX Composite Analysis 101

This Jupyter Notebook provides a detailed analysis of the **Toronto Stock Exchange (TSX) Composite** index, focusing on valuation, financial metrics, and trading strategies. It combines fundamental data, financial modeling, and market insights to offer actionable investment perspectives.

---

## Overview

The notebook covers:

- **Data Preparation:** Loading and cleaning TSX-listed company data.
- **Financial Metrics:** Calculation of Free Cash Flow (FCF), growth rates, and Weighted Average Cost of Capital (WACC).
- **Discounted Cash Flow (DCF) Valuation:** Projecting company valuations under multiple macroeconomic scenarios.
- **Relative Strength Index (RSI) Analysis:** Identification of bottom-performing stocks based on RSI values.
- **Year-to-Date (YTD) Performance Analysis:** Comparison of stock returns with sector, industry, and major market benchmarks.
- **Visualization:** 3D DCF valuation surfaces for sensitivity analysis.

---

## Key Features

- Integration with **Yahoo Finance API** for live financial and market data.
- Flexible **DCF modeling** with adjustable growth and discount rates.
- Comparative analysis against **sector and industry averages**.
- Automated **price target** generation with upside scenarios.
- Interactive **3D plots** for valuation sensitivity across WACC and growth assumptions.

---

## Usage

1. Clone or download this repository.
2. Install required Python packages:
   ```bash
   pip install pandas numpy matplotlib yfinance tabulate plotly pytz

