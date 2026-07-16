📊 Stock Analysis Tool

An Excel-based fundamental analysis toolkit that pulls a company's financial data and turns it into a full valuation workbook: historical financials, key ratios, an Altman Z-Score, a 3-scenario DCF valuation model, and auto-generated charts — all in one file, one ticker at a time.

The included example is pre-loaded with Apple Inc. (AAPL).

✨ Features


Company Snapshot (INFO) — sector, industry, market cap, IPO date, employee count, and a 15+ year history of Revenue, Gross Profit, EBITDA, Net Income, EPS, and Free Cash Flow (plus year-over-year growth %).
Altman Z-Score — built-in default/bankruptcy risk calculation from working capital, retained earnings, EBIT, equity, and liabilities.
Financial Statements (FS) — full historical Income Statement, Balance Sheet, and Cash Flow Statement.
DCF Valuation Model (DCF) — projects Revenue, EBIT, Taxes, D&A, CapEx, and Change in NWC forward, with adjustable Revenue Growth, EBIT Margin, Tax Rate, D&A, CapEx, WACC, and Terminal Growth Rate assumptions, run across Conservative / Base (Wall Street Estimates) / Optimistic scenarios.
Ratio Analysis (RATIOS) — Profitability (Gross Margin, Net Margin, ROA, ROE, ROIC), Market Value (P/E, P/B, EV/EBITDA, EV/Sales, P/S), Liquidity (Current Ratio), and Leverage (Debt-to-Equity, Interest Coverage, DSO, DPO, DOH) — each benchmarked against sector and industry averages.
Charts (CHARTS) — auto-generated visualizations of the key trends above.
Historical Price Data (Data) — daily closing prices used for market cap, P/E, and valuation calculations.
Raw Data Feed — per-statement annual tables (Income Statement, Balance Sheet, Cash Flow, Key Metrics, Financial Growth) that feed the rest of the workbook.


🗂️ Sheet Structure

INFO      → Company overview, key metrics, Z-Score
CHARTS    → Visualizations
FS        → Historical financial statements
DCF       → Discounted Cash Flow valuation
RATIOS    → Ratio analysis vs. sector/industry
Data      → Historical stock prices
[TICKER] - Income Statement FY
[TICKER] - Balance Sheet FY
[TICKER] - Cash Flow FY
[TICKER] - Key Metrics FY
[TICKER] - Financial Growth FY

🚀 Getting Started


Download Stock_Analysis_Tool.xlsx.
Open it in Excel (or Google Sheets / LibreOffice Calc — note some charts/conditional formatting may not render outside Excel).
To analyze a different company, replace the ticker and raw data in the [TICKER] - ...FY sheets and Data sheet with fresh data for your chosen stock, then update the INFO and DCF sheet references.
Adjust the DCF assumptions (growth, margins, WACC, TGR) to build your own conservative/base/optimistic valuation.


📥 Data Source

Financial statement and key metrics data is structured to match the Financial Modeling Prep (FMP) API format, making it straightforward to refresh with a free or paid FMP API key.

⚠️ Disclaimer

This tool is for educational and informational purposes only. It does not constitute financial or investment advice. All figures, assumptions, and valuations should be independently verified before making any investment decisions.

📄 License

[Choose a license — MIT is a common, permissive choice for tools like this. Add a LICENSE file to the repo.]

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with improvements, additional ratios, or support for more tickers/data sources.
