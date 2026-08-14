<div align="center">

# 💹 Awesome Finance & Macro

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Stars](https://img.shields.io/github/stars/simonpierreboucher02/awesome-finance-macro?style=flat-square&color=yellow)](https://github.com/simonpierreboucher02/awesome-finance-macro/stargazers)
[![Last Updated](https://img.shields.io/badge/Updated-2026-blue?style=flat-square)](https://github.com/simonpierreboucher02/awesome-finance-macro)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square)](https://www.spboucher.ai)

> A **legendary**, curated list of everything in **Finance & Macroeconomics** — data sources, APIs, Python libraries, macro indicators, dashboards, research, podcasts, books, and more.

**Author:** [Simon-Pierre Boucher](https://www.spboucher.ai) • [spbou4@protonmail.com](mailto:spbou4@protonmail.com) • Co-curated with [Claude](https://claude.ai)

---

⭐ **Star this repo** if you find it useful — it helps others discover it!

</div>

---

## 📑 Table of Contents

- [📊 Macro Indicators & Metrics](#-macro-indicators--metrics)
- [🏛️ Central Banks & Official Sources](#️-central-banks--official-sources)
- [🗄️ Data Sources & Databases](#️-data-sources--databases)
- [🔌 Financial Data APIs](#-financial-data-apis)
- [🐍 Python Libraries](#-python-libraries)
- [📈 Trading & Backtesting Frameworks](#-trading--backtesting-frameworks)
- [🖥️ Dashboards & Platforms](#️-dashboards--platforms)
- [⛓️ On-Chain & Crypto Analytics](#️-on-chain--crypto-analytics)
- [📰 Newsletters & Media](#-newsletters--media)
- [🎙️ Podcasts](#️-podcasts)
- [📚 Books](#-books)
- [🎓 Academic Papers & Research](#-academic-papers--research)
- [🐦 Accounts to Follow (X / Twitter)](#-accounts-to-follow-x--twitter)
- [🛠️ Developer Tools & Infrastructure](#️-developer-tools--infrastructure)
- [🌐 Communities & Forums](#-communities--forums)
- [📋 Awesome Lists to Explore](#-awesome-lists-to-explore)

---

## 📊 Macro Indicators & Metrics

> Key metrics to monitor the health of global economies. These are the signals every macro analyst watches.

### 🔴 Growth Indicators
| Indicator | Description | Source |
|-----------|-------------|--------|
| ![GDP](https://img.shields.io/badge/Metric-GDP-red?style=flat-square) | Gross Domestic Product — total economic output | [FRED](https://fred.stlouisfed.org/series/GDP) |
| ![GDPNow](https://img.shields.io/badge/Metric-GDPNow-orange?style=flat-square) | Real-time GDP nowcast model by Atlanta Fed | [Atlanta Fed](https://www.atlantafed.org/cqer/research/gdpnow) |
| ![PMI](https://img.shields.io/badge/Metric-PMI-yellow?style=flat-square) | Purchasing Managers' Index — leading business activity indicator | [ISM](https://www.ismworld.org) |
| ![LEI](https://img.shields.io/badge/Metric-LEI-blue?style=flat-square) | Leading Economic Index by Conference Board | [Conference Board](https://www.conference-board.org/topics/us-leading-indicators/) |
| ![IP](https://img.shields.io/badge/Metric-Industrial_Production-green?style=flat-square) | Industrial Production Index | [FRED](https://fred.stlouisfed.org/series/INDPRO) |

### 🔵 Inflation Indicators
| Indicator | Description | Source |
|-----------|-------------|--------|
| ![CPI](https://img.shields.io/badge/Metric-CPI-blue?style=flat-square) | Consumer Price Index — headline inflation | [BLS](https://www.bls.gov/cpi/) |
| ![CoreCPI](https://img.shields.io/badge/Metric-Core_CPI-blueviolet?style=flat-square) | CPI ex-food & energy — underlying inflation | [FRED](https://fred.stlouisfed.org/series/CPILFESL) |
| ![PCE](https://img.shields.io/badge/Metric-PCE-purple?style=flat-square) | Personal Consumption Expenditures — Fed's preferred gauge | [BEA](https://www.bea.gov/data/personal-consumption-expenditures-price-index) |
| ![PPI](https://img.shields.io/badge/Metric-PPI-pink?style=flat-square) | Producer Price Index — upstream inflation pressures | [BLS](https://www.bls.gov/ppi/) |
| ![BreakevenInflation](https://img.shields.io/badge/Metric-Breakeven_Inflation-red?style=flat-square) | Market-implied inflation expectations (5Y, 10Y) | [FRED](https://fred.stlouisfed.org/series/T10YIE) |

### 🟢 Labor Market Indicators
| Indicator | Description | Source |
|-----------|-------------|--------|
| ![NFP](https://img.shields.io/badge/Metric-Non--Farm_Payrolls-brightgreen?style=flat-square) | Monthly jobs added in the US economy | [BLS](https://www.bls.gov/bls/newsrels.htm) |
| ![Unemployment](https://img.shields.io/badge/Metric-Unemployment_Rate-green?style=flat-square) | Percentage of unemployed workforce | [FRED](https://fred.stlouisfed.org/series/UNRATE) |
| ![JOLTS](https://img.shields.io/badge/Metric-JOLTS-lime?style=flat-square) | Job Openings and Labor Turnover Survey | [BLS](https://www.bls.gov/jlt/) |
| ![Wages](https://img.shields.io/badge/Metric-Average_Hourly_Earnings-yellow?style=flat-square) | Average hourly earnings YoY growth | [FRED](https://fred.stlouisfed.org/series/CES0500000003) |
| ![InitialJoblessClaims](https://img.shields.io/badge/Metric-Initial_Jobless_Claims-orange?style=flat-square) | Weekly unemployment insurance filings | [FRED](https://fred.stlouisfed.org/series/ICSA) |

### 🟡 Financial Conditions Indicators
| Indicator | Description | Source |
|-----------|-------------|--------|
| ![YieldCurve](https://img.shields.io/badge/Metric-Yield_Curve_2s10s-yellow?style=flat-square) | 10Y minus 2Y Treasury spread — recession predictor | [FRED](https://fred.stlouisfed.org/series/T10Y2Y) |
| ![FedFunds](https://img.shields.io/badge/Metric-Fed_Funds_Rate-gold?style=flat-square) | Target Federal Funds Rate | [FRED](https://fred.stlouisfed.org/series/FEDFUNDS) |
| ![VIX](https://img.shields.io/badge/Metric-VIX-red?style=flat-square) | CBOE Volatility Index — fear gauge | [CBOE](https://www.cboe.com/tradable_products/vix/) |
| ![FCI](https://img.shields.io/badge/Metric-Financial_Conditions_Index-blue?style=flat-square) | Chicago Fed National Financial Conditions Index | [FRED](https://fred.stlouisfed.org/series/NFCI) |
| ![DXY](https://img.shields.io/badge/Metric-DXY_Dollar_Index-green?style=flat-square) | US Dollar strength index vs basket of currencies | [TradingView](https://www.tradingview.com/symbols/TVC-DXY/) |
| ![MOVE](https://img.shields.io/badge/Metric-MOVE_Index-purple?style=flat-square) | Bond market volatility index (ICE BofA) | [Bloomberg](https://www.bloomberg.com) |
| ![SOFR](https://img.shields.io/badge/Metric-SOFR-cyan?style=flat-square) | Secured Overnight Financing Rate | [NY Fed](https://www.newyorkfed.org/markets/reference-rates/sofr) |

### 🔶 Trade & External Indicators
| Indicator | Description | Source |
|-----------|-------------|--------|
| ![TradeBalance](https://img.shields.io/badge/Metric-Trade_Balance-orange?style=flat-square) | Difference between exports and imports | [BEA](https://www.bea.gov) |
| ![CurrentAccount](https://img.shields.io/badge/Metric-Current_Account-darkorange?style=flat-square) | Broadest measure of a country's trade | [IMF](https://data.imf.org) |
| ![GlobalTrade](https://img.shields.io/badge/Metric-Global_Trade_Volume-red?style=flat-square) | World merchandise trade volume | [WTO](https://www.wto.org/english/res_e/statis_e/statis_e.htm) |

---

## 🏛️ Central Banks & Official Sources

> Primary sources — the institutions that shape global monetary policy and publish essential economic data.

| Institution | Description | Badges |
|-------------|-------------|--------|
| 🇺🇸 [Federal Reserve (Fed)](https://www.federalreserve.gov) | US central bank — monetary policy, rates, financial stability | ![Fed](https://img.shields.io/badge/Central%20Bank-Federal%20Reserve-blue?style=flat-square) |
| 🇪🇺 [European Central Bank (ECB)](https://www.ecb.europa.eu) | Eurozone monetary authority | ![ECB](https://img.shields.io/badge/Central%20Bank-ECB-003399?style=flat-square) |
| 🇬🇧 [Bank of England (BoE)](https://www.bankofengland.co.uk) | UK central bank with rich research output | ![BoE](https://img.shields.io/badge/Central%20Bank-BoE-darkred?style=flat-square) |
| 🇯🇵 [Bank of Japan (BoJ)](https://www.boj.or.jp/en/) | Japan's central bank — yield curve control pioneer | ![BoJ](https://img.shields.io/badge/Central%20Bank-BoJ-red?style=flat-square) |
| 🇨🇦 [Bank of Canada (BoC)](https://www.bankofcanada.ca) | Canadian monetary authority | ![BoC](https://img.shields.io/badge/Central%20Bank-BoC-darkred?style=flat-square) |
| 🌍 [Bank for International Settlements (BIS)](https://www.bis.org) | Central bank of central banks — macro-financial research | ![BIS](https://img.shields.io/badge/Institution-BIS-orange?style=flat-square) |
| 🌐 [International Monetary Fund (IMF)](https://www.imf.org) | Global economic stability, WEO database | ![IMF](https://img.shields.io/badge/Institution-IMF-blue?style=flat-square) |
| 🌍 [World Bank](https://data.worldbank.org) | Development data, World Development Indicators | ![WB](https://img.shields.io/badge/Institution-World%20Bank-green?style=flat-square) |
| 🌐 [OECD](https://stats.oecd.org) | Economic statistics for developed countries | ![OECD](https://img.shields.io/badge/Institution-OECD-blue?style=flat-square) |
| 🇺🇸 [US Treasury](https://home.treasury.gov) | Fiscal policy, bond yields, TBAC statements | ![Treasury](https://img.shields.io/badge/Institution-US%20Treasury-darkgreen?style=flat-square) |
| 🇺🇸 [New York Fed](https://www.newyorkfed.org) | SOFR, TIPS breakevens, global supply chain pressure | ![NYFed](https://img.shields.io/badge/Fed-New%20York-blue?style=flat-square) |
| 🇺🇸 [Atlanta Fed](https://www.atlantafed.org) | GDPNow, Wage Growth Tracker, macroblog | ![AtlantaFed](https://img.shields.io/badge/Fed-Atlanta-blue?style=flat-square) |
| 🇺🇸 [Cleveland Fed](https://www.clevelandfed.org) | Yield curve & GDP growth predictor | ![ClevelandFed](https://img.shields.io/badge/Fed-Cleveland-blue?style=flat-square) |
| 🇺🇸 [NBER](https://www.nber.org) | National Bureau of Economic Research — official recession dating | ![NBER](https://img.shields.io/badge/Research-NBER-darkblue?style=flat-square) |

---

## 🗄️ Data Sources & Databases

> Where to get the data — free, open, and premium sources for macro and financial research.

### 🆓 Free & Open Data
| Source | Description | Coverage |
|--------|-------------|----------|
| [FRED](https://fred.stlouisfed.org) | 840,000+ economic time series from 118 sources | ![Coverage](https://img.shields.io/badge/Coverage-Macro%20%7C%20Finance-blue?style=flat-square) |
| [World Bank Open Data](https://data.worldbank.org) | Development, poverty, GDP, demographics | ![Coverage](https://img.shields.io/badge/Coverage-Global-green?style=flat-square) |
| [IMF Data](https://data.imf.org) | WEO, IFS, BOP, GFSR datasets | ![Coverage](https://img.shields.io/badge/Coverage-International-blue?style=flat-square) |
| [BIS Data Portal](https://stats.bis.org) | Cross-border banking, FX, securities stats | ![Coverage](https://img.shields.io/badge/Coverage-Financial-orange?style=flat-square) |
| [OECD Stats](https://stats.oecd.org) | National accounts, trade, employment | ![Coverage](https://img.shields.io/badge/Coverage-OECD%20Countries-blue?style=flat-square) |
| [Yahoo Finance](https://finance.yahoo.com) | Free market data, historical prices | ![Coverage](https://img.shields.io/badge/Coverage-Equities%20%7C%20ETFs-purple?style=flat-square) |
| [Stooq](https://stooq.com) | Free historical financial data | ![Coverage](https://img.shields.io/badge/Coverage-Global%20Markets-grey?style=flat-square) |
| [EDGAR (SEC)](https://www.sec.gov/edgar) | US company filings, 10-K, 10-Q | ![Coverage](https://img.shields.io/badge/Coverage-US%20Equities-blue?style=flat-square) |
| [Eurostat](https://ec.europa.eu/eurostat) | EU economic and social statistics | ![Coverage](https://img.shields.io/badge/Coverage-Eurozone-003399?style=flat-square) |
| [US Census Bureau](https://www.census.gov/economic-indicators/) | US economic indicators, retail, housing | ![Coverage](https://img.shields.io/badge/Coverage-US%20Economy-red?style=flat-square) |
| [EIA](https://www.eia.gov) | US Energy Information Administration | ![Coverage](https://img.shields.io/badge/Coverage-Energy-yellow?style=flat-square) |
| [LongtermTrends](https://www.longtermtrends.net) | Long-term macro charts and ratios | ![Coverage](https://img.shields.io/badge/Coverage-Historical-teal?style=flat-square) |

### 💰 Premium Data
| Source | Description | Type |
|--------|-------------|------|
| [Bloomberg Terminal](https://www.bloomberg.com/professional/) | Industry standard — $32K/year | ![Type](https://img.shields.io/badge/Type-Premium-black?style=flat-square) |
| [Refinitiv Eikon](https://www.refinitiv.com/en/products/eikon-trading-software) | Real-time market data & analytics | ![Type](https://img.shields.io/badge/Type-Premium-darkblue?style=flat-square) |
| [FactSet](https://www.factset.com) | Financial data aggregation, analytics | ![Type](https://img.shields.io/badge/Type-Premium-orange?style=flat-square) |
| [Quandl (Nasdaq Data Link)](https://data.nasdaq.com) | Alternative & institutional datasets | ![Type](https://img.shields.io/badge/Type-Freemium-blue?style=flat-square) |
| [S&P Global Market Intelligence](https://www.spglobal.com/marketintelligence/) | Credit ratings, financials, research | ![Type](https://img.shields.io/badge/Type-Premium-red?style=flat-square) |

---

## 🔌 Financial Data APIs

> Programmatic access to financial and macro data.

### Market Data APIs
| API | Free Tier | Best For |
|-----|-----------|----------|
| [Alpha Vantage](https://www.alphavantage.co) | 25 calls/day | ![Best For](https://img.shields.io/badge/Best%20For-Stocks%20%7C%20FX%20%7C%20Crypto-blue?style=flat-square) |
| [Polygon.io](https://polygon.io) | Limited real-time | ![Best For](https://img.shields.io/badge/Best%20For-US%20Markets%20%7C%20High%20Freq-orange?style=flat-square) |
| [Finnhub](https://finnhub.io) | 60 calls/min | ![Best For](https://img.shields.io/badge/Best%20For-Dev%20%7C%20Prototyping-green?style=flat-square) |
| [EODHD](https://eodhd.com) | Limited | ![Best For](https://img.shields.io/badge/Best%20For-Global%20Fundamentals-purple?style=flat-square) |
| [Financial Modeling Prep](https://financialmodelingprep.com) | 250 calls/day | ![Best For](https://img.shields.io/badge/Best%20For-Fundamentals%20%7C%20DCF-blue?style=flat-square) |
| [Marketstack](https://marketstack.com) | 1,000 calls/mo | ![Best For](https://img.shields.io/badge/Best%20For-EOD%20Stock%20Data-grey?style=flat-square) |
| [Tiingo](https://www.tiingo.com) | Yes | ![Best For](https://img.shields.io/badge/Best%20For-Stocks%20%7C%20Crypto%20%7C%20NLP-teal?style=flat-square) |

### Macro & Economic APIs
| API | Description | Access |
|-----|-------------|--------|
| [FRED API](https://fred.stlouisfed.org/docs/api/fred/) | 840K+ macro series | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392) | Global development indicators | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [IMF API](https://www.imf.org/en/Data) | WEO, IFS, BOP data | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [BIS API](https://stats.bis.org/api-doc/v1/) | Banking & financial statistics | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [ECB SDW API](https://sdw-wsrest.ecb.europa.eu) | ECB Statistical Data Warehouse | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [OECD API](https://data.oecd.org/api/) | OECD macro data | ![Access](https://img.shields.io/badge/Access-Free-brightgreen?style=flat-square) |
| [FXMacroData](https://fxmacrodata.com/documentation/reference) | FX-focused macro indicators, release calendars, central-bank decisions, COT, commodities, and FX data | ![Access](https://img.shields.io/badge/Access-Freemium-blue?style=flat-square) |

---

## 🐍 Python Libraries

> The essential Python toolkit for finance and macro analysis.

### 📦 Data & Analysis
| Library | Stars | Description |
|---------|-------|-------------|
| [![pandas](https://img.shields.io/github/stars/pandas-dev/pandas?style=flat-square&label=pandas)](https://github.com/pandas-dev/pandas) | ⭐⭐⭐⭐⭐ | Time-series data manipulation — backbone of financial analysis |
| [![numpy](https://img.shields.io/github/stars/numpy/numpy?style=flat-square&label=numpy)](https://github.com/numpy/numpy) | ⭐⭐⭐⭐⭐ | Matrix math, linear algebra for quantitative models |
| [![scipy](https://img.shields.io/github/stars/scipy/scipy?style=flat-square&label=scipy)](https://github.com/scipy/scipy) | ⭐⭐⭐⭐ | Statistical functions, optimization |
| [![statsmodels](https://img.shields.io/github/stars/statsmodels/statsmodels?style=flat-square&label=statsmodels)](https://github.com/statsmodels/statsmodels) | ⭐⭐⭐⭐ | Econometrics — OLS, ARIMA, VAR, GARCH |
| [![arch](https://img.shields.io/github/stars/bashtage/arch?style=flat-square&label=arch)](https://github.com/bashtage/arch) | ⭐⭐⭐ | GARCH volatility modeling |

### 📡 Data Fetching
| Library | Description | Source |
|---------|-------------|--------|
| `yfinance` | Yahoo Finance historical & fundamental data | ![pip](https://img.shields.io/badge/pip-yfinance-blue?style=flat-square) |
| `pandas-datareader` | FRED, World Bank, OECD, BIS connector | ![pip](https://img.shields.io/badge/pip-pandas--datareader-blue?style=flat-square) |
| `fredapi` | Official FRED API Python wrapper | ![pip](https://img.shields.io/badge/pip-fredapi-blue?style=flat-square) |
| `wbgapi` | World Bank API client | ![pip](https://img.shields.io/badge/pip-wbgapi-blue?style=flat-square) |
| `imf-reader` | IMF data access in Python | ![pip](https://img.shields.io/badge/pip-imf--reader-blue?style=flat-square) |
| `alpha_vantage` | Alpha Vantage API wrapper | ![pip](https://img.shields.io/badge/pip-alpha--vantage-blue?style=flat-square) |

### 📊 Visualization
| Library | Description | Best For |
|---------|-------------|----------|
| `matplotlib` | Foundational plotting library | ![Best For](https://img.shields.io/badge/Best%20For-Static%20Charts-blue?style=flat-square) |
| `plotly` | Interactive charts, candlesticks | ![Best For](https://img.shields.io/badge/Best%20For-Interactive%20%7C%20Dashboards-purple?style=flat-square) |
| `mplfinance` | Financial charts (OHLCV) built on matplotlib | ![Best For](https://img.shields.io/badge/Best%20For-OHLCV%20Charts-green?style=flat-square) |
| `seaborn` | Statistical visualization | ![Best For](https://img.shields.io/badge/Best%20For-Correlation%20%7C%20Stats-teal?style=flat-square) |
| `altair` | Declarative statistical visualization | ![Best For](https://img.shields.io/badge/Best%20For-Exploratory%20Analysis-orange?style=flat-square) |

### 🔬 Quantitative Finance
| Library | Description | Use Case |
|---------|-------------|----------|
| [QuantLib](https://www.quantlib.org) | Pricing derivatives, yield curves, bonds | ![Use Case](https://img.shields.io/badge/Use-Derivatives%20%7C%20Fixed%20Income-blue?style=flat-square) |
| [QuantEcon](https://quantecon.org) | Computational economics (Python & Julia) | ![Use Case](https://img.shields.io/badge/Use-Macro%20Modeling-green?style=flat-square) |
| [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) | Portfolio optimization, efficient frontier | ![Use Case](https://img.shields.io/badge/Use-Portfolio%20Optimization-purple?style=flat-square) |
| [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) | Advanced portfolio optimization with risk models | ![Use Case](https://img.shields.io/badge/Use-Risk%20Modeling-red?style=flat-square) |
| [TA-Lib](https://ta-lib.org) | 150+ technical indicators (RSI, MACD, BB) | ![Use Case](https://img.shields.io/badge/Use-Technical%20Analysis-orange?style=flat-square) |
| [pandas-ta](https://github.com/twopirllc/pandas-ta) | Technical analysis extension for pandas | ![Use Case](https://img.shields.io/badge/Use-Technical%20Analysis-yellow?style=flat-square) |
| [ffn](https://github.com/pmorissette/ffn) | Financial functions — drawdowns, Sharpe, Calmar | ![Use Case](https://img.shields.io/badge/Use-Performance%20Analysis-teal?style=flat-square) |
| [QuantStats](https://github.com/ranaroussi/quantstats) | Tear sheet reports — Sharpe, Sortino, drawdowns | ![Use Case](https://img.shields.io/badge/Use-Strategy%20Reporting-blue?style=flat-square) |

### 🤖 Machine Learning for Finance
| Library | Description | Use Case |
|---------|-------------|----------|
| `scikit-learn` | Classical ML models (regression, clustering) | ![Use Case](https://img.shields.io/badge/Use-Prediction%20%7C%20Classification-blue?style=flat-square) |
| `XGBoost` | Gradient boosting — top performer on tabular data | ![Use Case](https://img.shields.io/badge/Use-Alpha%20Models-green?style=flat-square) |
| `LightGBM` | Fast gradient boosting by Microsoft | ![Use Case](https://img.shields.io/badge/Use-Factor%20Models-teal?style=flat-square) |
| `PyTorch` | Deep learning for time-series, NLP in finance | ![Use Case](https://img.shields.io/badge/Use-Deep%20Learning-orange?style=flat-square) |
| `prophet` | Facebook time-series forecasting | ![Use Case](https://img.shields.io/badge/Use-Forecasting-red?style=flat-square) |
| `NeuralForecast` | Neural architectures for time-series | ![Use Case](https://img.shields.io/badge/Use-Advanced%20Forecasting-purple?style=flat-square) |

---

## 📈 Trading & Backtesting Frameworks

> Build, test, and deploy systematic strategies.

| Framework | Language | Description |
|-----------|----------|-------------|
| [Zipline-Reloaded](https://github.com/stefan-jansen/zipline-reloaded) | Python | Open-source backtesting — successor to Zipline |
| [Backtrader](https://github.com/mementum/backtrader) | Python | Feature-rich backtesting with live trading support |
| [VectorBT](https://github.com/polakowo/vectorbt) | Python | Vectorized backtesting — extremely fast |
| [Lean (QuantConnect)](https://github.com/QuantConnect/Lean) | C# / Python | Production-grade algorithmic trading engine |
| [bt](https://github.com/pmorissette/bt) | Python | Flexible backtesting for systematic strategies |
| [Nautilus Trader](https://github.com/nautechsystems/nautilus_trader) | Python / Rust | High-performance algo trading platform |
| [Jesse](https://github.com/jesse-ai/jesse) | Python | Simple & elegant crypto backtesting |
| [PyAlgoTrade](https://github.com/gbeced/pyalgotrade) | Python | Event-driven backtesting library |

---

## 🖥️ Dashboards & Platforms

> Tools for charting, research, and professional financial analysis.

### Bloomberg Alternatives
| Platform | Cost | Best For |
|----------|------|----------|
| [TradingView](https://www.tradingview.com) | Free / $15–$60/mo | ![Best For](https://img.shields.io/badge/Best%20For-Charts%20%7C%20Screening-blue?style=flat-square) |
| [Koyfin](https://www.koyfin.com) | Free / ~$20/mo | ![Best For](https://img.shields.io/badge/Best%20For-Macro%20%7C%20Equity%20Dashboards-green?style=flat-square) |
| [Fiscal.ai](https://fiscal.ai) | Free / $49/mo | ![Best For](https://img.shields.io/badge/Best%20For-Fundamentals%20%7C%2013F-purple?style=flat-square) |
| [Macrotrends](https://www.macrotrends.net) | Free | ![Best For](https://img.shields.io/badge/Best%20For-Long--Term%20Macro%20Charts-orange?style=flat-square) |
| [Simply Wall St](https://simplywall.st) | Freemium | ![Best For](https://img.shields.io/badge/Best%20For-Equity%20Research-teal?style=flat-square) |
| [Seeking Alpha](https://seekingalpha.com) | Freemium | ![Best For](https://img.shields.io/badge/Best%20For-News%20%7C%20Analysis-red?style=flat-square) |

### Macro Dashboards
| Platform | Description |
|----------|-------------|
| [Global Macro Investor](https://globalmacroinvestor.com) | Raoul Pal's macro research platform |
| [LongtermTrends](https://www.longtermtrends.net) | Long-term macro ratio charts |
| [Multpl](https://www.multpl.com) | S&P 500 P/E, Shiller CAPE, historical ratios |
| [gurufocus](https://www.gurufocus.com) | Buffett indicator, Shiller PE, macro metrics |
| [Current Market Valuation](https://www.currentmarketvaluation.com) | Market overvaluation indicators |
| [Wisesheets](https://wisesheets.io) | Financial data directly in Google Sheets / Excel |

---

## ⛓️ On-Chain & Crypto Analytics

> Blockchain data and crypto macro indicators.

| Platform | Description | Specialty |
|----------|-------------|-----------|
| [Glassnode](https://glassnode.com) | Institutional-grade on-chain metrics | ![Specialty](https://img.shields.io/badge/Specialty-Bitcoin%20%7C%20ETH%20Macro-orange?style=flat-square) |
| [Nansen](https://www.nansen.ai) | 500M+ labeled wallets, smart money tracking | ![Specialty](https://img.shields.io/badge/Specialty-Wallet%20Intelligence-purple?style=flat-square) |
| [Dune Analytics](https://dune.com) | SQL-based on-chain queries & dashboards | ![Specialty](https://img.shields.io/badge/Specialty-Custom%20Analytics-pink?style=flat-square) |
| [DeFiLlama](https://defillama.com) | TVL tracking across all DeFi protocols | ![Specialty](https://img.shields.io/badge/Specialty-DeFi%20%7C%20TVL-blue?style=flat-square) |
| [CoinGlass](https://www.coinglass.com) | Futures, funding rates, liquidations, OI | ![Specialty](https://img.shields.io/badge/Specialty-Derivatives-red?style=flat-square) |
| [The Block](https://www.theblock.co) | Crypto research & data | ![Specialty](https://img.shields.io/badge/Specialty-Crypto%20Research-teal?style=flat-square) |
| [Arkham Intelligence](https://arkhamintelligence.com) | Entity-level blockchain intelligence | ![Specialty](https://img.shields.io/badge/Specialty-Entity%20Mapping-grey?style=flat-square) |

### Key On-Chain Metrics
| Metric | Description |
|--------|-------------|
| ![MVRV](https://img.shields.io/badge/Metric-MVRV_Ratio-orange?style=flat-square) | Market Value to Realized Value — BTC cycle indicator |
| ![NUPL](https://img.shields.io/badge/Metric-NUPL-orange?style=flat-square) | Net Unrealized Profit/Loss |
| ![SOPR](https://img.shields.io/badge/Metric-SOPR-yellow?style=flat-square) | Spent Output Profit Ratio |
| ![StockToFlow](https://img.shields.io/badge/Metric-Stock_to_Flow-gold?style=flat-square) | BTC scarcity model by Plan B |
| ![FundingRate](https://img.shields.io/badge/Metric-Funding_Rate-blue?style=flat-square) | Perpetual futures funding rate |
| ![OpenInterest](https://img.shields.io/badge/Metric-Open_Interest-purple?style=flat-square) | Total open futures/options contracts |

---

## 📰 Newsletters & Media

> Stay informed with the best macro and finance newsletters.

| Newsletter | Author / Publisher | Focus |
|------------|-------------------|-------|
| [The Macro Compass](https://themacrocompass.substack.com) | Alfonso Peccatiello (MacroAlf) | ![Focus](https://img.shields.io/badge/Focus-Global%20Macro-blue?style=flat-square) |
| [Global Macro Investor](https://globalmacroinvestor.com) | Raoul Pal | ![Focus](https://img.shields.io/badge/Focus-Macro%20%7C%20Crypto-purple?style=flat-square) |
| [Macro Musings Blog](https://www.mercatus.org/macro-musings) | David Beckworth | ![Focus](https://img.shields.io/badge/Focus-Monetary%20Policy-blue?style=flat-square) |
| [Morning Brew](https://www.morningbrew.com) | Morning Brew | ![Focus](https://img.shields.io/badge/Focus-Daily%20Markets%20%7C%20News-teal?style=flat-square) |
| [The Daily Upside](https://www.thedailyupside.com) | The Daily Upside | ![Focus](https://img.shields.io/badge/Focus-Finance%20%7C%20Business-green?style=flat-square) |
| [Finimize](https://finimize.com) | Finimize | ![Focus](https://img.shields.io/badge/Focus-Markets%20%7C%20Investing-orange?style=flat-square) |
| [Verdad Research](https://verdadcap.com/archive) | Dan Rasmussen | ![Focus](https://img.shields.io/badge/Focus-Quant%20%7C%20Value-red?style=flat-square) |
| [Epsilon Theory](https://www.epsilontheory.com) | Ben Hunt | ![Focus](https://img.shields.io/badge/Focus-Narrative%20%7C%20Markets-purple?style=flat-square) |
| [Concoda](https://concoda.substack.com) | Concoda | ![Focus](https://img.shields.io/badge/Focus-Monetary%20System-darkblue?style=flat-square) |
| [Odd Lots](https://www.bloomberg.com/oddlots-newsletter) | Bloomberg | ![Focus](https://img.shields.io/badge/Focus-Markets%20%7C%20Economy-black?style=flat-square) |

---

## 🎙️ Podcasts

> The best audio content for macro, finance, and economics.

| Podcast | Host(s) | Focus |
|---------|---------|-------|
| [Macro Trading Floor](https://open.spotify.com/show/6aaCFGDmW50FLMG0rRDhZq) | Alfonso Peccatiello & Brent Donnelly | ![Focus](https://img.shields.io/badge/Focus-Macro%20%7C%20Trades-blue?style=flat-square) |
| [Macro Musings](https://www.mercatus.org/macro-musings) | David Beckworth | ![Focus](https://img.shields.io/badge/Focus-Monetary%20Policy-green?style=flat-square) |
| [MacroVoices](https://www.macrovoices.com) | Erik Townsend | ![Focus](https://img.shields.io/badge/Focus-Global%20Macro%20%7C%20Commodities-orange?style=flat-square) |
| [Odd Lots](https://www.bloomberg.com/oddlots) | Tracy Alloway & Joe Weisenthal | ![Focus](https://img.shields.io/badge/Focus-Markets%20%7C%20Finance-black?style=flat-square) |
| [The Grant Williams Podcast](https://www.grant-williams.com/podcast) | Grant Williams | ![Focus](https://img.shields.io/badge/Focus-Macro%20%7C%20Gold-gold?style=flat-square) |
| [Capital Ideas](https://www.capitalgroup.com/individual/planning-and-tools/podcast.html) | Capital Group | ![Focus](https://img.shields.io/badge/Focus-Investing%20%7C%20Markets-blue?style=flat-square) |
| [Monetary Policy Podcast](https://www.brookings.edu/series/the-hutchins-center-podcast/) | Brookings Institution | ![Focus](https://img.shields.io/badge/Focus-Fed%20%7C%20Monetary%20Policy-darkblue?style=flat-square) |
| [We Study Billionaires](https://theinvestorspodcast.com) | The Investors Podcast Network | ![Focus](https://img.shields.io/badge/Focus-Value%20Investing-purple?style=flat-square) |
| [Invest Like the Best](https://www.joincolossus.com/episodes) | Patrick O'Shaughnessy | ![Focus](https://img.shields.io/badge/Focus-Investing%20%7C%20Business-teal?style=flat-square) |
| [Real Vision](https://www.realvision.com/shows) | Raoul Pal & guests | ![Focus](https://img.shields.io/badge/Focus-Macro%20%7C%20Finance%20Video-red?style=flat-square) |

---

## 📚 Books

> The essential reading list for macro, finance, and quantitative investing.

### Macroeconomics & Monetary Theory
| Book | Author | Badge |
|------|--------|-------|
| *Principles of Macroeconomics* | N. Gregory Mankiw | ![Level](https://img.shields.io/badge/Level-Foundational-green?style=flat-square) |
| *Macroeconomics* | Olivier Blanchard | ![Level](https://img.shields.io/badge/Level-Foundational-green?style=flat-square) |
| *The General Theory of Employment, Interest and Money* | John Maynard Keynes | ![Level](https://img.shields.io/badge/Level-Classic-gold?style=flat-square) |
| *A Monetary History of the United States* | Friedman & Schwartz | ![Level](https://img.shields.io/badge/Level-Classic-gold?style=flat-square) |
| *This Time Is Different* | Reinhart & Rogoff | ![Level](https://img.shields.io/badge/Level-Essential-blue?style=flat-square) |
| *Our Dollar, Your Problem* | Kenneth Rogoff | ![Level](https://img.shields.io/badge/Level-2025-red?style=flat-square) |
| *The Price of Time* | Edward Chancellor | ![Level](https://img.shields.io/badge/Level-Modern-purple?style=flat-square) |
| *Principles for Dealing with the Changing World Order* | Ray Dalio | ![Level](https://img.shields.io/badge/Level-Modern-purple?style=flat-square) |

### Quantitative Finance & Investing
| Book | Author | Badge |
|------|--------|-------|
| *Options, Futures, and Other Derivatives* | John C. Hull | ![Level](https://img.shields.io/badge/Level-Essential%20Quant-blue?style=flat-square) |
| *The Intelligent Investor* | Benjamin Graham | ![Level](https://img.shields.io/badge/Level-Classic-gold?style=flat-square) |
| *Quantitative Value* | Wesley Gray & Tobias Carlisle | ![Level](https://img.shields.io/badge/Level-Quant%20Investing-purple?style=flat-square) |
| *Advances in Financial Machine Learning* | Marcos López de Prado | ![Level](https://img.shields.io/badge/Level-Advanced%20ML-red?style=flat-square) |
| *Machine Learning for Asset Managers* | Marcos López de Prado | ![Level](https://img.shields.io/badge/Level-Advanced%20ML-red?style=flat-square) |
| *Expected Returns* | Antti Ilmanen | ![Level](https://img.shields.io/badge/Level-Factor%20Investing-teal?style=flat-square) |
| *The Psychology of Money* | Morgan Housel | ![Level](https://img.shields.io/badge/Level-Behavioral-green?style=flat-square) |
| *A Man for All Markets* | Edward Thorp | ![Level](https://img.shields.io/badge/Level-Quant%20Pioneer-gold?style=flat-square) |

### Fixed Income & Interest Rates
| Book | Author | Badge |
|------|--------|-------|
| *The Bond Book* | Annette Thau | ![Level](https://img.shields.io/badge/Level-Foundational-green?style=flat-square) |
| *Fixed Income Securities* | Frank J. Fabozzi | ![Level](https://img.shields.io/badge/Level-Advanced-red?style=flat-square) |
| *Developments in Macro-Finance Yield Curve Modelling* | Chadha et al. | ![Level](https://img.shields.io/badge/Level-Academic-darkblue?style=flat-square) |

---

## 🎓 Academic Papers & Research

> Landmark papers in macro-finance, monetary economics, and quantitative research.

### Foundational Papers
| Paper | Authors | Link |
|-------|---------|------|
| *Macro-Finance* | John H. Cochrane | [NBER w22485](https://www.nber.org/papers/w22485) |
| *A Macro-Finance Model of the Term Structure* | Rudebusch & Wu | [SF Fed](https://www.frbsf.org/wp-content/uploads/wp03-17bk.pdf) |
| *Real Business Cycles* | Kydland & Prescott | NBER |
| *A Contribution to the Theory of Economic Growth* | Robert Solow | Classic |

### Research Hubs
| Institution | Resource |
|-------------|----------|
| [NBER Working Papers](https://www.nber.org/papers) | ![Badge](https://img.shields.io/badge/Type-Working%20Papers-blue?style=flat-square) |
| [SSRN Finance](https://ssrn.com/en/index.cfm/finance/) | ![Badge](https://img.shields.io/badge/Type-Preprints-orange?style=flat-square) |
| [BIS Working Papers](https://www.bis.org/list/wppdf/index.htm) | ![Badge](https://img.shields.io/badge/Type-Central%20Bank-red?style=flat-square) |
| [IMF Working Papers](https://www.imf.org/en/publications/wp) | ![Badge](https://img.shields.io/badge/Type-International-blue?style=flat-square) |
| [Fed Reserve Research](https://www.federalreserve.gov/econres.htm) | ![Badge](https://img.shields.io/badge/Type-Monetary%20Policy-darkblue?style=flat-square) |
| [ECB Working Paper Series](https://www.ecb.europa.eu/pub/research/working-papers/html/index.en.html) | ![Badge](https://img.shields.io/badge/Type-Eurozone-003399?style=flat-square) |
| [BoE Staff Working Papers](https://www.bankofengland.co.uk/working-paper) | ![Badge](https://img.shields.io/badge/Type-Monetary%20Policy-darkred?style=flat-square) |
| [SF Fed 2nd Annual Macro-Finance Conference](https://www.frbsf.org/news-and-media/events/conferences/2025/10/conference-on-macro-finance-research/) | ![Badge](https://img.shields.io/badge/Event-2025-green?style=flat-square) |

### Online Learning & Courses
| Resource | Description |
|----------|-------------|
| [QuantEcon Lectures](https://lectures.quantecon.org) | Computational economics (Python & Julia) |
| [Coursera — Financial Markets (Yale)](https://www.coursera.org/learn/financial-markets-global) | Robert Shiller's famous course |
| [MIT OpenCourseWare Finance](https://ocw.mit.edu/courses/finance/) | MIT Finance Department materials |
| [Khan Academy — Macroeconomics](https://www.khanacademy.org/economics-finance-domain/macroeconomics) | Free foundational macro |
| [CFA Institute Learning](https://www.cfainstitute.org/learning) | Professional finance education |

---

## 🐦 Accounts to Follow (X / Twitter)

> The best voices in macro, finance, and economics.

### Macro Economists & Strategists
| Account | Description |
|---------|-------------|
| [@MacroAlf](https://x.com/MacroAlf) | Alfonso Peccatiello — Macro Compass, institutional macro |
| [@paulkrugman](https://x.com/paulkrugman) | Nobel laureate, NYT columnist, 4M+ followers |
| [@elerian](https://x.com/elerian) | Mohamed El-Erian — Allianz Chief Economic Advisor |
| [@IanShepherdson](https://x.com/IanShepherdson) | Chief Economist, Pantheon Macroeconomics |
| [@LynAldenContact](https://x.com/LynAldenContact) | Macro — monetary policy, fiscal dynamics, global systems |
| [@davidbeckworth](https://x.com/davidbeckworth) | Senior Fellow Mercatus, monetary policy expert |
| [@brentdonnelly](https://x.com/brentdonnelly) | FX macro trader, macro floor podcast host |

### Finance & Investing
| Account | Description |
|---------|-------------|
| [@AswathDamodaran](https://x.com/AswathDamodaran) | NYU Stern — "Dean of Valuation" |
| [@morganhousel](https://x.com/morganhousel) | Author, *The Psychology of Money* |
| [@RaoulGMI](https://x.com/RaoulGMI) | Raoul Pal — Global Macro Investor, Real Vision |
| [@jesselivermore](https://x.com/philosophical_e) | Philosophical Economics — long-form macro |
| [@JustinWolfers](https://x.com/JustinWolfers) | U Michigan professor, labor economics |
| [@Nouriel](https://x.com/Nouriel) | Nouriel Roubini — "Dr. Doom," NYU economist |

---

## 🛠️ Developer Tools & Infrastructure

> Infrastructure for building financial applications.

| Tool | Description | Category |
|------|-------------|----------|
| [Jupyter](https://jupyter.org) | Notebooks for research & analysis | ![Cat](https://img.shields.io/badge/Category-Research-blue?style=flat-square) |
| [DuckDB](https://duckdb.org) | Fast analytical SQL for financial datasets | ![Cat](https://img.shields.io/badge/Category-Database-green?style=flat-square) |
| [Apache Arrow](https://arrow.apache.org) | Columnar data — fast financial data exchange | ![Cat](https://img.shields.io/badge/Category-Data%20Format-orange?style=flat-square) |
| [Redis](https://redis.io) | In-memory store for real-time market data pipelines | ![Cat](https://img.shields.io/badge/Category-Infrastructure-red?style=flat-square) |
| [Apache Kafka](https://kafka.apache.org) | High-throughput financial event streaming | ![Cat](https://img.shields.io/badge/Category-Streaming-purple?style=flat-square) |
| [Prefect](https://www.prefect.io) | Workflow orchestration for data pipelines | ![Cat](https://img.shields.io/badge/Category-Orchestration-teal?style=flat-square) |
| [Airflow](https://airflow.apache.org) | DAG-based ETL for financial data ingestion | ![Cat](https://img.shields.io/badge/Category-Orchestration-blue?style=flat-square) |
| [Streamlit](https://streamlit.io) | Build financial dashboards in pure Python | ![Cat](https://img.shields.io/badge/Category-Dashboard-red?style=flat-square) |
| [Grafana](https://grafana.com) | Time-series dashboards for market monitoring | ![Cat](https://img.shields.io/badge/Category-Monitoring-orange?style=flat-square) |

---

## 🌐 Communities & Forums

> Where macro & finance minds gather.

| Community | Platform | Focus |
|-----------|----------|-------|
| [r/Economics](https://reddit.com/r/economics) | Reddit | General economics discussions |
| [r/MacroEconomics](https://reddit.com/r/MacroEconomics) | Reddit | Macro-specific discussions |
| [r/QuantFinance](https://reddit.com/r/QuantFinance) | Reddit | Quantitative finance |
| [r/investing](https://reddit.com/r/investing) | Reddit | Long-term investing |
| [QuantLib Forum](http://quantlib.org/mailinglists.shtml) | Mailing List | QuantLib development |
| [Quantocracy](https://quantocracy.com) | Aggregator | Quant finance blog aggregator |
| [Nuclear Phynance](http://www.nuclearphynance.com) | Forum | Quant finance forum |
| [Wilmott Forums](https://forum.wilmott.com) | Forum | Quantitative finance |
| [Stack Exchange — Quant Finance](https://quant.stackexchange.com) | Q&A | Quantitative finance Q&A |

---

## 📋 Awesome Lists to Explore

> More awesome resources discovered by the community.

| List | Description |
|------|-------------|
| [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) | Insanely awesome quant finance libraries |
| [awesome-economics](https://github.com/antontarasenko/awesome-economics) | Curated list for economists |
| [awesome-finance](https://github.com/awesomelistsio/awesome-finance) | Tools, platforms, datasets for finance |
| [awesome-sustainable-finance](https://github.com/open-risk/awesome-sustainable-finance) | ESG and sustainable finance resources |
| [awesome-investing](https://github.com/mr-karan/awesome-investing) | Investment & finance resources |
| [OpenSourcedMacroModels](https://github.com/dkgaraujo/OpenSourcedMacroModels) | Open-source central bank macro models |

---

<div align="center">

## 🤝 Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

1. Fork this repo
2. Add your resource in the appropriate category
3. Ensure it follows the format: `[Resource Name](URL) — Short description`
4. Submit a Pull Request

---

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under the **CC0 1.0 Universal** public domain dedication.

---

**Curated with ❤️ by [Simon-Pierre Boucher](https://www.spboucher.ai)**
📧 [spbou4@protonmail.com](mailto:spbou4@protonmail.com) • 🌐 [spboucher.ai](https://www.spboucher.ai)
🤖 Co-curated with [Claude Sonnet 4.6](https://claude.ai) by Anthropic

*Last updated: February 2026*

</div>
