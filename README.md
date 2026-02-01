[project.md](https://github.com/user-attachments/files/24989787/project.md)
# 🏎️ Lamborghini Stock Market Analysis: 45-Year Financial Performance Dataset (1980-2025)

## 📊 Project Description

**Lamborghini Stock Market Analysis: 45-Year Financial Performance Dataset (1980-2025)** is a comprehensive time-series dataset containing monthly stock market data for Automobili Lamborghini S.p.A. spanning nearly half a century. This meticulously curated dataset provides researchers, data scientists, financial analysts, and machine learning enthusiasts with a rich historical perspective on one of the world's most iconic luxury automotive brands.

The dataset captures the complete financial journey of Lamborghini from its early years in the 1980s through multiple economic cycles, including the dot-com bubble, the 2008 financial crisis, and the recent global pandemic. With 553 monthly observations and 20 comprehensive features, this dataset enables deep-dive analysis into stock price movements, volatility patterns, market capitalization evolution, dividend policies, and corporate actions such as stock splits.

### Key Highlights:

- **45+ Years of Historical Data**: From January 1980 to December 2025
- **20 Rich Features**: Price data, volume metrics, financial ratios, and performance indicators
- **Complete Market Lifecycle**: Covers multiple economic cycles and market conditions
- **Corporate Events**: Includes stock splits (2:1 in 2015, 3:1 in 2020) and dividend history
- **Ready for Analysis**: Clean, structured format ideal for time-series analysis, forecasting, and machine learning

This dataset is perfect for:

- **Time-Series Forecasting**: Predict future stock prices using historical patterns
- **Volatility Analysis**: Study market risk and price fluctuations over decades
- **Financial Modeling**: Build valuation models and assess company performance
- **Machine Learning**: Train models for stock prediction, anomaly detection, and trend analysis
- **Economic Research**: Analyze the impact of economic events on luxury brand stocks
- **Portfolio Analysis**: Understand long-term investment performance and risk-return characteristics

---

## 🏷️ Top 5 Kaggle Tags

1. **`time-series`** - Comprehensive 45-year monthly time-series data perfect for forecasting and trend analysis
2. **`finance`** - Complete financial dataset with price, volume, market cap, and financial ratios
3. **`stock-market`** - Historical stock market data covering multiple economic cycles and market conditions
4. **`luxury-brands`** - Unique dataset focusing on luxury automotive sector performance
5. **`forecasting`** - Ideal for predictive modeling, price prediction, and volatility forecasting

---

## 📈 Dataset Coverage

### Temporal Coverage

- **Start Date**: January 1, 1980
- **End Date**: December 31, 2025
- **Duration**: 45 years and 12 months (46 years total)
- **Frequency**: Monthly observations
- **Total Records**: 553 data points
- **Decade Breakdown**:
  - **1980s**: 1980-1989 (120 months)
  - **1990s**: 1990-1999 (120 months)
  - **2000s**: 2000-2009 (120 months)
  - **2010s**: 2010-2019 (120 months)
  - **2020s**: 2020-2025 (73 months)

### Feature Coverage

#### Price Data (5 features)

- **Open**: Opening price for each month
- **High**: Highest price during the month
- **Low**: Lowest price during the month
- **Close**: Closing price for each month
- **Adj Close**: Adjusted closing price (accounts for splits and dividends)

#### Trading Volume (2 features)

- **Volume**: Total number of shares traded
- **Trading Volume (M)**: Volume in millions of shares

#### Financial Metrics (4 features)

- **Dividend**: Dividend per share (mostly 0.0 until 2010, then regular payments)
- **Stock Split**: Corporate actions (2:1 split in 2015, 3:1 split in 2020)
- **PE Ratio**: Price-to-Earnings ratio
- **Market Cap ($M)**: Market capitalization in millions of USD

#### Performance Indicators (5 features)

- **52W High**: 52-week high price
- **52W Low**: 52-week low price
- **Volatility (%)**: Monthly price volatility percentage
- **Daily Return (%)**: Daily return percentage
- **Monthly Return ($)**: Monthly return in dollars

#### Metadata (4 features)

- **Date**: Trading date (YYYY-MM-DD format)
- **Year**: Year (1980-2025)
- **Month**: Month (1-12)
- **Decade**: Categorical grouping (1980s, 1990s, 2000s, 2010s, 2020s)

### Data Quality

- **Completeness**: 99.8% data completeness across all features
- **Missing Values**: Minimal missing values in early years (1980) for return calculations
- **Data Consistency**: Consistent monthly frequency throughout the dataset
- **Price Range**: Stock price evolution from ~$2.31 (1980) to ~$20.31 (2025)
- **Market Cap Growth**: From ~$13M (1980) to ~$900M+ (2020s)

### Key Events Captured

- **Stock Splits**:
  - 2:1 split in January 2015
  - 3:1 split in January 2020
- **Dividend Policy**: Transition from no dividends (1980-2009) to regular dividend payments (2010-2025)
- **Economic Cycles**:
  - 1980s: High inflation period
  - 1990s: Dot-com era
  - 2000s: Financial crisis (2008)
  - 2010s: Recovery and growth
  - 2020s: COVID-19 pandemic and recovery

### Use Cases Supported

✅ Time-series forecasting and prediction  
✅ Volatility modeling and risk analysis  
✅ Financial ratio analysis  
✅ Dividend policy impact studies  
✅ Stock split effect analysis  
✅ Market capitalization trend analysis  
✅ Decade-wise comparative analysis  
✅ Machine learning model training  
✅ Economic event impact assessment  
✅ Portfolio performance evaluation

---

## 📁 Dataset Structure

```
lamborghini_stock_data.csv
├── 553 rows (excluding header)
├── 20 columns
└── File size: ~50 KB
```

### Column Names

1. Date
2. Year
3. Month
4. Open
5. High
6. Low
7. Close
8. Adj Close
9. Volume
10. Dividend
11. Stock Split
12. PE Ratio
13. Market Cap ($M)
14. 52W High
15. 52W Low
16. Volatility (%)
17. Trading Volume (M)
18. Decade
19. Daily Return (%)
20. Monthly Return ($)

---

## 🎯 Target Audience

- **Data Scientists**: Building predictive models and time-series forecasts
- **Financial Analysts**: Conducting fundamental and technical analysis
- **Researchers**: Studying long-term market trends and economic impacts
- **Students**: Learning time-series analysis and financial data science
- **Machine Learning Engineers**: Training models for stock prediction
- **Quantitative Analysts**: Developing trading strategies and risk models

---

## 📝 Citation

If you use this dataset in your research or projects, please cite:

```
Lamborghini Stock Market Analysis Dataset (1980-2025)
Automobili Lamborghini S.p.A. Historical Stock Data
Time Period: January 1980 - December 2025
```

---

## 📧 Contact & Support

For questions, suggestions, or contributions related to this dataset, please refer to the project repository or create an issue.

---

---

## 📅 Temporal and Geospatial Scope

### Temporal Coverage

| Attribute      | Details                                      |
| -------------- | -------------------------------------------- |
| **Start Date** | 01/01/1980                                   |
| **End Date**   | 12/31/2025                                   |
| **Duration**   | 45 years and 12 months (552 monthly records) |
| **Frequency**  | Monthly (first day of each month)            |
| **Time Zone**  | UTC (Coordinated Universal Time)             |

### Geospatial Scope

| Attribute                | Details                               |
| ------------------------ | ------------------------------------- |
| **Company Headquarters** | Sant'Agata Bolognese, Italy           |
| **Country of Origin**    | Italy 🇮🇹                              |
| **Parent Company**       | Volkswagen Group (Germany) since 1998 |
| **Stock Exchange**       | Global OTC Markets (Simulated)        |
| **Currency**             | USD (United States Dollar)            |
| **Market Coverage**      | Global luxury automotive sector       |

> [!NOTE]
> Automobili Lamborghini S.p.A. is a privately held company under Volkswagen AG. This dataset represents simulated stock market data for educational and analytical purposes.

---

## 📜 Data Provenance

### Source Description

This dataset represents **synthetic/simulated stock market data** generated for Automobili Lamborghini S.p.A., designed to mirror realistic financial market patterns observed in luxury automotive companies. The data is intended for:

- **Educational purposes**: Learning time-series analysis and financial modeling
- **Research applications**: Testing predictive models and algorithms
- **Portfolio analysis**: Understanding stock market dynamics

### Data Generation Methodology

1. **Base Price Generation**: Initial stock prices were generated using historical luxury automotive sector benchmarks
2. **Trend Incorporation**: Long-term growth trends were modeled based on industry patterns
3. **Volatility Modeling**: Monthly volatility was calibrated using GARCH-like stochastic processes
4. **Corporate Events**: Stock splits (2:1 in 2015, 3:1 in 2020) and dividend initiation (2010) were incorporated
5. **Economic Cycles**: Major economic events (1987 crash, 2008 crisis, COVID-19 pandemic) were reflected in price movements

### Data Transformations Applied

| Transformation            | Description                                                    |
| ------------------------- | -------------------------------------------------------------- |
| **Date Parsing**          | Converted to YYYY-MM-DD format                                 |
| **Adjusted Close**        | Calculated to reflect splits and dividends                     |
| **Decade Classification** | Added categorical decade grouping (1980s-2020s)                |
| **Return Calculations**   | Daily and monthly returns computed from closing prices         |
| **Volume Normalization**  | Trading Volume (M) derived by dividing raw volume by 1,000,000 |
| **52-Week Metrics**       | Rolling 52-week high/low calculated from historical data       |

---

## 🔬 Dataset Collection Methodology

### Data Generation Process

```
1. Parameter Initialization
   ├── Initial Price: $2.58 (Jan 1980)
   ├── Annual Growth Rate: 4-8% (variable by decade)
   ├── Monthly Volatility: 15-45% range
   └── Trading Volume: 1M-50M shares/month

2. Time-Series Simulation
   ├── Geometric Brownian Motion for price paths
   ├── ARIMA components for trend persistence
   ├── Jump-diffusion for extreme events
   └── Mean-reversion for valuation metrics

3. Financial Metrics Derivation
   ├── P/E Ratio: Market Cap / Estimated Earnings
   ├── Market Cap: Price × Shares Outstanding
   ├── Dividends: Initiated 2010, variable payout
   └── 52-Week Ranges: Rolling window calculations

4. Quality Assurance
   ├── No-arbitrage condition checks
   ├── Volume-price correlation validation
   ├── Statistical distribution tests
   └── Historical event alignment
```

### Data Quality Standards

- **Completeness**: 99.8% complete across all features
- **Consistency**: Monthly frequency maintained throughout
- **Accuracy**: Price movements within realistic bounds
- **Timeliness**: Data covers through December 2025

---

## 📊 Complete Column Details (Kaggle Dataset Specification)

| #   | Column Name            | Data Type | Description                                            | Example Value | Missing Values    |
| --- | ---------------------- | --------- | ------------------------------------------------------ | ------------- | ----------------- |
| 1   | **Date**               | datetime  | Trading date (first day of each month)                 | 2025-01-01    | 0                 |
| 2   | **Year**               | int64     | Calendar year                                          | 2025          | 0                 |
| 3   | **Month**              | int64     | Calendar month (1-12)                                  | 1             | 0                 |
| 4   | **Open**               | float64   | Opening price for the month ($)                        | 19.68         | 0                 |
| 5   | **High**               | float64   | Highest price during the month ($)                     | 19.80         | 0                 |
| 6   | **Low**                | float64   | Lowest price during the month ($)                      | 19.42         | 0                 |
| 7   | **Close**              | float64   | Closing price for the month ($)                        | 19.56         | 0                 |
| 8   | **Adj Close**          | float64   | Adjusted closing price (accounts for splits/dividends) | 19.55         | 0                 |
| 9   | **Volume**             | int64     | Total trading volume (shares)                          | 3846483       | 0                 |
| 10  | **Dividend**           | float64   | Dividend per share ($)                                 | 0.31          | 0                 |
| 11  | **Stock Split**        | object    | Stock split ratio (e.g., 2:1, 3:1)                     | 2:1           | 540 (most months) |
| 12  | **PE Ratio**           | float64   | Price-to-Earnings ratio                                | 17.7          | 0                 |
| 13  | **Market Cap ($M)**    | float64   | Market capitalization in millions USD                  | 75.3          | 0                 |
| 14  | **52W High**           | float64   | 52-week high price ($)                                 | 22.50         | 0                 |
| 15  | **52W Low**            | float64   | 52-week low price ($)                                  | 16.63         | 0                 |
| 16  | **Volatility (%)**     | float64   | Monthly price volatility percentage                    | 31.14         | 0                 |
| 17  | **Trading Volume (M)** | float64   | Volume in millions of shares                           | 3.85          | 0                 |
| 18  | **Decade**             | object    | Categorical decade grouping                            | 2020s         | 0                 |
| 19  | **Daily Return (%)**   | float64   | Daily return percentage                                | 3.16          | 1 (first row)     |
| 20  | **Monthly Return ($)** | float64   | Monthly return in dollars                              | 0.60          | 1 (first row)     |

### Column Categories

#### 📈 Price Data (5 columns)

- **Open, High, Low, Close, Adj Close**: Standard OHLC price data representing monthly trading activity

#### 📊 Volume Metrics (2 columns)

- **Volume**: Raw trading volume in shares
- **Trading Volume (M)**: Normalized volume in millions

#### 💰 Financial Metrics (4 columns)

- **Dividend**: Per-share dividend payments (started 2010)
- **Stock Split**: Corporate action indicators
- **PE Ratio**: Valuation metric
- **Market Cap ($M)**: Company valuation

#### 📉 Performance Indicators (5 columns)

- **52W High/Low**: Trading range context
- **Volatility (%)**: Risk measurement
- **Daily/Monthly Return**: Performance metrics

#### 📅 Temporal Metadata (4 columns)

- **Date, Year, Month, Decade**: Time-based indexing

---

## 🔗 Data Source

### Primary Source

> [!IMPORTANT]
> **Dataset Type**: Synthetic/Simulated Financial Data
>
> This dataset was **synthetically generated** for educational and research purposes. It is NOT official stock market data from any exchange.

### Source Details

| Attribute           | Information                                            |
| ------------------- | ------------------------------------------------------ |
| **Creation Method** | Programmatic simulation using Python                   |
| **Base Reference**  | Luxury automotive sector patterns                      |
| **Purpose**         | Educational data science and financial analysis        |
| **Availability**    | [Kaggle Dataset](https://www.kaggle.com/datasets/)     |
| **License**         | CC BY-SA 4.0 (Creative Commons Attribution-ShareAlike) |

### Reference Resources

- **Company Information**: [Lamborghini Official Website](https://www.lamborghini.com/)
- **Parent Company**: [Volkswagen Group](https://www.volkswagenag.com/)
- **Market Context**: Financial Times, Bloomberg (for sector trends)

### Disclaimer

```
⚠️ IMPORTANT DISCLAIMER:
This dataset is SIMULATED and does not represent actual trading data.
Automobili Lamborghini S.p.A. is a privately held subsidiary and does
not have publicly traded stock. This data is intended solely for:
- Data science education
- Machine learning model development
- Financial analysis practice
- Academic research

Do NOT use this data for actual investment decisions.
```

---

## ⚠️ Problems and Challenges

### Data-Related Challenges

#### 1. **Synthetic Data Limitations**

- **Issue**: As simulated data, it may not capture all real-world market dynamics
- **Impact**: Models trained on this data may not generalize to actual markets
- **Mitigation**: Use as educational tool, validate findings with real data

#### 2. **Missing Value Handling**

- **Issue**: First row lacks Daily Return (%) and Monthly Return ($) values
- **Impact**: Minor - only affects first observation
- **Mitigation**: Standard imputation or exclusion for return calculations

#### 3. **Stock Split Sparsity**

- **Issue**: Stock Split column is mostly null (only 2 events in 45 years)
- **Impact**: Limited data for split-effect analysis
- **Mitigation**: Focus on before/after comparison for existing splits

### Analytical Challenges

#### 4. **Regime Changes**

- **Issue**: Different market conditions across decades (1980s inflation, 2008 crisis, COVID-19)
- **Impact**: Non-stationary time series requiring careful modeling
- **Mitigation**: Decade-based segmentation, regime-switching models

#### 5. **Volatility Clustering**

- **Issue**: High volatility periods cluster together (heteroskedasticity)
- **Impact**: Standard models may underestimate risk during crisis periods
- **Mitigation**: GARCH modeling, volatility-adjusted metrics

#### 6. **Corporate Structure Changes**

- **Issue**: Lamborghini changed ownership multiple times (1998 VW acquisition)
- **Impact**: Fundamental value drivers may differ across periods
- **Mitigation**: Acknowledge structural breaks in analysis

### Technical Challenges

#### 7. **Dividend Policy Shift**

- **Issue**: No dividends 1980-2009, then regular payments 2010-2025
- **Impact**: Total return calculations differ by period
- **Mitigation**: Separate analysis for dividend and non-dividend periods

#### 8. **Volume Interpretation**

- **Issue**: Volume patterns in simulated data may not reflect real liquidity
- **Impact**: Volume-based indicators may have limited validity
- **Mitigation**: Use volume as relative metric, not absolute measure

#### 9. **Survivorship Bias**

- **Issue**: Data assumes continuous operation for 45 years
- **Impact**: Does not account for potential bankruptcy scenarios
- **Mitigation**: Include risk analysis and stress testing in models

### Research Opportunities Despite Challenges

✅ Time-series forecasting methodology development  
✅ Volatility modeling and risk analysis  
✅ Corporate event impact studies (splits, dividends)  
✅ Long-term trend analysis across economic cycles  
✅ Machine learning model benchmarking

---

**Last Updated**: February 2025  
**Dataset Version**: 1.0  
**License**: CC BY-SA 4.0 (Creative Commons Attribution-ShareAlike)
