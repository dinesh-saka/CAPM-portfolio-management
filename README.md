# CAPM-portfolio-management

## 👋 Overview

Utilizing the Capital Asset Pricing Model (CAPM) to analyze multiple stocks within the S&P 500, aiming to optimize portfolio management by assessing the expected returns based on systematic risk and market performance.

## 💵 Introduction to CAPM (Capital Asset Pricing Model)
The Capital Asset Pricing Model (CAPM) is a financial model that establishes a relationship between the expected return of an investment and its risk, providing a method to determine an appropriate required rate of return for an asset. Developed by William Sharpe in the 1960s, CAPM helps investors assess the risk of a particular investment compared to the overall market.

### 💡Key Components:

1. Risk-Free Rate (Rf): The return expected from an investment with zero risk, typically represented by government bonds.
2. Market Return (Rm): The expected return of the market as a whole, usually represented by a market index like the S&P 500.
3. Beta (β): A measure of an asset's volatility in relation to the market. A beta of 1 indicates that the asset's price moves with the market, while a beta greater than 1 signifies greater volatility, and a beta less than 1 indicates lower volatility.

*CAPM Formula:* The expected return (E(Ri)) of an asset can be calculated using the formula:

```math
\ E(R_i) = R_f + β_i * (R_m - R_f)
```

Where:

* $`E(R_i)`$ = Expected return of the asset
* $`R_f`$ = Risk-free rate
* $`β_i`$ = Beta of the asset
* $`R_m`$ = Expected return of the market
* $`(R_m - R_f)`$ = Market risk premium

*Applications:* CAPM is widely used for portfolio management, capital budgeting, and asset valuation. It aids investors in making informed decisions by providing a framework to evaluate the trade-off between risk and expected return.

In summary, CAPM is a foundational concept in finance that helps investors understand how to quantify risk and return, guiding investment decisions and portfolio construction.

## 📖 Data Used

Stock prices for companies: AAPL, BA, T, MGM, AMZN, IBM, TSLA, GOOG, and S&P 500.
Data range: 2012-01-12 to present.
Key Features
Data Normalization: Prices are normalized to visualize percentage changes.
Interactive Visualizations: Create interactive plots using Plotly for enhanced analysis.
Daily Returns Calculation: Computes daily returns to analyze performance.
Beta Calculation: Determines the stock's volatility relative to the market (S&P 500).
CAPM Model: Estimates expected returns using the Capital Asset Pricing Model.


## 📈 Expected Returns (CAPM):

AAPL: 13.757%

BA (Boeing): 16.934%

T (AT&T): 9.423%

MGM (MGM Resorts): 20.119%

AMZN (Amazon): 17.655%

IBM: 8.692%

TSLA: 15.589%

GOOG: 10.424%
