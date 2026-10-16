# Quantitative-Sector-Analysis-Evaluating-Growth-Macro-Sensitivity-and-Holding-Period-Risk
1. 0verview

This project evaluates the multi-horizon risk-return profile of three major US sector ETFs—Technology (XLK), Financials (XLF), and Healthcare (XLV)—relative to the macro interest rate environment represented by the 10-Year Treasury Yield (^TNX).

The goal is to determine optimal holding periods, quantify downside risks across various time horizons, and analyze how sector performance responds to shifting interest rates.

2. Tech Stack & Libraries
Language: Python

Data Source: Yahoo Finance (yfinance)

Libraries: pandas, numpy, matplotlib, seaborn

3. Implementation

Step 1: Data Pull & Cumulative Returns

Step 2: Interest Rate Sensitivity & Correlation Matrix

To analyze how sectors react to interest rate shifts, we calculate daily percentage returns for the stocks and daily absolute changes (.diff()) for the interest rate benchmark.

Key Finding: XLF exhibits a positive correlation (+0.054) with rate changes (benefiting from higher net interest margins), while XLK (-0.047) and XLV (-0.136) face valuation headwinds when yields climb.

Step 3: Rolling Volatility & Holding Horizon Risk

4. Empirical Findings & Economic Insights

Technology (XLK) — The Growth Engine: Delivers superior long-term cumulative returns (>200%), but carries high short-term volatility and drawdowns (20%–25%). Safe holding period: >3 years to smooth out rate-induced valuation contractions.

Financials (XLF) — The Macro Rate Hedge: Acts as a direct beneficiary of rising interest rates because financial institutions sit at the center of capital flows as primary credit intermediaries, expanding net interest margins as borrowers pay higher rates.

Healthcare (XLV) — The Defensive Anchor: Exhibits the lowest overall volatility and shallowest drawdowns, trading off higher growth for capital preservation. Ideal for short horizons (<1 year).
