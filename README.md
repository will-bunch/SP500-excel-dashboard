# S&P 500 Stock Performance Dashboard

An interactive Microsoft Excel dashboard analysing the historical performance of 100 selected S&P 500 companies across multiple sectors and timeframes.

This project was developed to demonstrate practical Excel skills, financial data analysis and interactive dashboard design. It allows users to explore individual stock returns, compare sector performance and identify the strongest and weakest performers over different periods.

## Dashboard Features

### 1. Stock Performance Overview
- Performance analysis of 100 selected S&P 500 companies.
- Dynamic return calculations across 1-week, 1-month, 3-month, 6-month and 1-year periods.
- Conditional formatting to distinguish positive and negative returns.
- Sector classifications for comparing companies across industries.

### 2. Sector Analysis
- PivotTable summarising average stock returns by sector.
- Interactive slicer for filtering sectors.
- Visual comparison of sector performance.
- <img width="612" height="476" alt="image" src="https://github.com/user-attachments/assets/5cdfb510-45ef-42cc-aa89-79d61bf7a800" />

### 3. Individual Stock Analysis
- Automatically updated top five and bottom five performing stocks.
- Dropdown menu to select individual companies.
- Historical adjusted closing price chart for the selected stock and timeframe.
- <img width="848" height="650" alt="image" src="https://github.com/user-attachments/assets/9e435c7c-d901-4910-bf30-3045e145cd74" />

## Skills Demonstrated

- **Excel Functions:** XLOOKUP, FILTER, LARGE and SMALL.
- **Data Analysis:** Historical stock prices, adjusted closing prices and percentage returns.
- **PivotTables & Slicers:** Interactive sector-level analysis.
- **Conditional Formatting:** Dynamic visual representation of stock performance.
- **Data Visualisation:** Interactive charts and performance comparisons.
- **Dashboard Design:** Organising financial data into an accessible, user-friendly interface.

## Dataset

The workbook contains approximately 25,100 daily price observations covering 100 selected S&P 500 companies between 7 November 2025 and 6 November 2026.

Historical market data was prepared from a dataset identified as [Aethereal Data — S&P 500 Stock Prices](https://dataset.aethereal.top/datasets/sp500-stock-prices).

The dataset was cleaned and reduced to a manageable sample for the purposes of this project.

## How to Use

1. Download `SP500_100_Stocks_One_Year.xlsx`.
2. Open the workbook in a modern desktop version of Microsoft Excel.
3. Use the **Companies** sheet to select a return period and compare stocks.
4. Explore the **Price returns pivot table** sheet to compare sector performance.
5. Use the **Individual performers** sheet to view top and bottom performers and individual price histories.

**Important:** After changing the return period, refresh the sector PivotTable manually to update its results. Further guidance is available in the workbook's **Read Me** sheet.

## Limitations

- The analysis covers a sample of 100 companies, not the complete S&P 500 index.
- Historical data is static and does not update automatically.
- Sector PivotTable results require manual refreshing after timeframe changes.
- The project is intended as a demonstration of Excel and financial analysis skills rather than an investment decision-making tool.
