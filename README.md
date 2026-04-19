# ACC102 Mini Assignment – Track 2: Financial Performance Analysis of AAPL, MSFT, and IBM (2022–2024)
## Track 2 – GitHub Data Analysis Project

---

## 1. Analytical Problem & Target User
This project analyzes the **stock price and financial performance** of three major U.S. technology companies (Apple, Microsoft, IBM) from 2022 to 2024.  
The target users include finance students, entry-level investors, and anyone learning Python for financial data analysis.

## 2. Data Source
- **Database**: WRDS (Wharton Research Data Services)
- **Stock price data**: CRSP Daily Stock File (2022–2024)
- **Financial data**: Compustat Fundamental Annual (2022–2024)
- **Key variables**: date, stock price, revenue, net income
- **Access date**: April 2026

## 3. Python Methods & Workflow
1. Connect to WRDS using the official `wrds` package
2. Extract and clean stock price and financial data
3. Calculate annual average stock prices
4. Merge price and financial indicators by company and year
5. Visualize trends and comparisons using `matplotlib` and `seaborn`

## 4. Key Findings
- All three companies showed a **clear recovery trend** after the 2022 market decline.
- **Microsoft (MSFT)** achieved the strongest stock price growth.
- **Apple (AAPL)** maintained the **highest and most stable net income**.
- **IBM** showed steady but slower growth in revenue and profit.

## 5. How to Run the Notebook
1. Run cells sequentially from top to bottom
2. Enter your WRDS username and password when prompted
3. All charts and outputs will be generated automatically

## 6. Product & Demo Links
- GitHub Repository: (https://github.com/duyumiao/ACC102track2)
- Demo Video: https://www.bilibili.com/video/BV1cwoFB3EBD/

## 7. Limitations & Improvements
- Limitations: Only three companies included; no financial ratio analysis
- Improvements: Add ROE, ROA, P/E ratio; expand company list; build an interactive dashboard
