# Edgelite Technologies — Startup Financial Model & Investment Analysis

**Financial Modeling · Startup Valuation · Unit Economics · Scenario Analysis · Runway & Break-Even · Investor Returns**

A complete startup financial modelling and investment analysis project built around **Edgelite Technologies**, an early-stage robotics company targeting consumer and enterprise applications across the GCC and emerging markets.

The project demonstrates how an investment-grade operating model can connect **commercial assumptions → customer acquisition → revenue → costs → cash flow → runway → break-even → capitalization → investor returns**.

> **Note:** Edgelite Technologies is a financial modelling case study created for portfolio and analytical purposes. The analysis demonstrates modelling methodology rather than representing an actual investment recommendation.

---

## Project Overview

The model was designed to answer the questions an investor, FP&A professional, investment analyst, or corporate finance team would typically ask when evaluating an early-stage hardware/software company:

* How does the company acquire customers?
* What drives revenue growth?
* What are the unit economics?
* How does the cost structure scale?
* How much capital is required?
* When does the company run out of cash?
* What level of sales is required to reach break-even?
* How does the business perform under different scenarios?
* How does the proposed financing affect ownership?
* What returns could investors generate under different exit valuations?

The model contains **24 months of operating forecasts**, an annualised Year 3 view, scenario analysis, a three-statement financial model, cap table, investor return analysis, runway analysis, and break-even calculations.

---

# Model Architecture

The workbook is structured into the following modules:

| Sheet                              | Purpose                                                                    |
| ---------------------------------- | -------------------------------------------------------------------------- |
| **ASSUMPTIONS**                    | Centralised operating, pricing, inflation, hiring and scenario assumptions |
| **CUSTOMER ACQUISITION & REVENUE** | DTC funnel, enterprise sales and revenue build                             |
| **COST BUILD**                     | Manufacturing, fulfillment, payroll and operating cost assumptions         |
| **CAP TABLE & INVESTOR RETURNS**   | Financing structure, ownership and exit return analysis                    |
| **MONTHLY P&L**                    | 24-month income statement forecast                                         |
| **CFS & SOFP**                     | Cash flow statement and statement of financial position                    |
| **RUNWAY BURN & BREAKEVEN**        | Cash runway, burn rate and monthly break-even analysis                     |
| **DASHBOARD**                      | Key operating and financial outputs                                        |

The architecture separates **assumptions from calculations and outputs**, allowing changes to core assumptions to flow through the model.

---

# Key Operating Assumptions

### Base Case

| Assumption                |                   Base Case |
| ------------------------- | --------------------------: |
| Annual unit sales growth  |                     **50%** |
| Annual pricing escalation |                      **3%** |
| Cost inflation            |                     **12%** |
| Wage inflation            |                     **10%** |
| DTC price                 |                 **~$1,100** |
| Enterprise price          |                  **$8,000** |
| Fulfillment / shipping    |           **$100 per unit** |
| Paid CPC                  |                   **$0.35** |
| Paid conversion rate      |                    **1.2%** |
| Organic conversion rate   |                    **2.8%** |
| Enterprise deal velocity  | **2 deals/month initially** |
| Rent & facilities         |            **$8,500/month** |

The model also incorporates downside and upside operating scenarios by varying unit growth, pricing, inflation, customer adoption, manufacturing costs, marketing expenditure, and hiring pace.

---

# Customer Acquisition & Revenue Build

The revenue model is built from operating drivers rather than simply applying a top-line growth percentage.

### DTC Acquisition Funnel

The initial monthly funnel includes:

* 3,000 paid visits
* 2,000 organic visits
* 1.2% paid conversion
* 2.8% organic conversion
* 92 initial DTC orders
* ~$101K initial DTC revenue

The model then scales traffic, conversion, pricing and enterprise activity over the forecast period.

### Revenue Mix

Edgelite operates a hybrid:

**DTC hardware + Enterprise robotics**

The DTC channel provides volume while the enterprise product carries substantially higher revenue and gross profit per unit.

---

# Unit Economics

### Home / Pro

| Metric              |     Amount |
| ------------------- | ---------: |
| ASP                 |    ~$1,100 |
| BOM                 |       $433 |
| Fulfillment         |       $100 |
| Gross Profit / Unit |      ~$567 |
| Gross Margin        | **~51.5%** |

### Enterprise

| Metric              |     Amount |
| ------------------- | ---------: |
| ASP                 |     $8,000 |
| BOM                 |       $970 |
| Fulfillment         |       $100 |
| Gross Profit / Unit |    ~$6,930 |
| Gross Margin        | **~86.6%** |

The model therefore demonstrates how product mix can materially affect blended gross margins.

---

# Financial Forecast

### Base Case

| Financial Metric |   Year 1 |   Year 2 | Year 3 Annualised |
| ---------------- | -------: | -------: | ----------------: |
| Revenue          |   $1.91M |   $3.54M |        **$6.55M** |
| Gross Profit     |   $1.17M |   $2.17M |        **$4.29M** |
| Gross Margin     |    61.1% |    64.7% |         **65.6%** |
| EBITDA           | $(0.79)M | $(0.94)M |      **$(0.61)M** |
| EBITDA Margin    |   -41.5% |   -26.6% |         **-9.3%** |
| Net Income       | $(0.82)M | $(1.02)M |      **$(0.76)M** |

The model demonstrates a typical early-stage scaling profile: revenue grows rapidly while payroll, product development and operating investment keep the company EBITDA-negative during the forecast period.

**Year 3 is presented as an annualised operating view derived from the monthly forecast.**

---

# Scenario Analysis

The model incorporates three operating scenarios:

| Scenario      | Unit Growth | Year 3 Revenue |  Year 3 EBITDA |
| ------------- | ----------: | -------------: | -------------: |
| Downside      |         25% |         ~$4.0M |    Deeper loss |
| **Base Case** |     **50%** |     **$6.55M** |   **$(0.61)M** |
| Upside        |         80% |        ~$9–10M | Near breakeven |

The purpose of the scenario analysis is to show how changes in fundamental operating assumptions affect the financial outcome rather than relying on a single-point forecast.

---

# Cash Runway

The model tracks monthly cash consumption and identifies the point at which additional financing becomes necessary.

### Key outputs

* Initial seed funding: **$2.0M**
* Opening liquidity after first-month operating costs: **~$1.86M**
* Cash falls below the $150K threshold around **Month 20**
* Cash becomes negative around **Month 21**
* The model therefore identifies a clear financing requirement before the end of the 24-month operating forecast

This creates a practical financing milestone:

> **Series A fundraising should begin well before the cash runway is exhausted.**

The model assumes a potential **$8M–$12M Series A** as the bridge toward Year 4 operating breakeven.

---

# Break-Even Analysis

The model calculates the number of units required to cover operating costs at different points in the forecast.

| Period   | Break-Even Units / Month | Actual Units / Month |
| -------- | -----------------------: | -------------------: |
| Month 1  |                     ~170 |                  ~95 |
| Month 24 |                     ~414 |                 ~306 |

This highlights an important feature of the business:

**Revenue growth alone does not guarantee near-term profitability.**

The company must simultaneously increase unit volume, maintain contribution margins and achieve operating leverage against its fixed cost base.

---

# Seed Financing & Cap Table

### Seed Round

| Metric               |      Amount |
| -------------------- | ----------: |
| Seed Raise           |   **$2.0M** |
| Pre-Money Valuation  | **$11.33M** |
| Post-Money Valuation | **$13.33M** |
| Equity Sold          |     **15%** |
| Founder Ownership    |     **85%** |

The cap table demonstrates the relationship between:

**Investment → post-money valuation → ownership → exit proceeds → investor returns**

The current model assumes the seed investor's 15% ownership for the return scenarios.

---

# Investor Return Analysis

The model evaluates potential exit outcomes using revenue-based valuation multiples.

| Exit Scenario         | Revenue Multiple | Enterprise Value | Investor Proceeds* |
| --------------------- | ---------------: | ---------------: | -----------------: |
| Private Equity Exit   |               6× |          ~$39.3M |             ~$5.9M |
| Strategic Acquisition |               8× |          ~$52.4M |             ~$7.9M |
| IPO                   |              12× |          ~$78.6M |            ~$11.8M |
| Breakout Scenario     |             ~15× |           ~$100M |            ~$15.0M |

*Investor proceeds are based on the model's 15% ownership assumption and are presented as scenario outputs.

The purpose of this section is not to predict an exit valuation. It demonstrates how changes in exit valuation translate into investor economics.

---

# Key Investment Metrics

Under the model's illustrative return scenarios:

* **6× exit:** ~2.9× MOIC
* **8× exit:** ~3.9× MOIC
* **12× exit:** ~5.9× MOIC
* **~15× exit:** ~7.5× MOIC

The model therefore connects operating performance with valuation and ultimately with investor return outcomes.

---

# Risk Analysis

The model and executive report identify several key risks:

### Cash & Financing Risk

The company remains EBITDA-negative through the 24-month forecast and requires additional capital before the current runway is exhausted.

### Enterprise Sales Cycle

Enterprise revenue depends on commercial deployments and procurement cycles that may take longer than anticipated.

### DTC Conversion

The revenue model depends on achieving the specified traffic and conversion assumptions.

### Manufacturing

Hardware scaling introduces manufacturing, supply-chain and fulfillment risks.

### Operating Leverage

Payroll and other fixed costs increase ahead of full operating profitability.

### Valuation Risk

Investor returns depend heavily on the valuation multiple achieved at exit.

---

# Executive Investment Analysis

Alongside the financial model, I developed a **17-page executive investment report** covering:

* Investment thesis
* Company and product overview
* Market opportunity
* Business model
* Revenue architecture
* Unit economics
* Financial forecast
* Cash runway
* Break-even analysis
* Competitive landscape
* Risk matrix
* Valuation
* Investor returns
* Investment conditions
* Model assumptions
* Data sources

The report translates the underlying spreadsheet model into an investor-facing analytical document.

---

# Investment Framework

The project does not treat the financial model as an isolated spreadsheet.

The analysis connects:

```text
Market Opportunity
       ↓
Business Model
       ↓
Customer Acquisition
       ↓
Revenue Drivers
       ↓
Unit Economics
       ↓
Cost Structure
       ↓
P&L / Cash Flow / Balance Sheet
       ↓
Runway & Break-Even
       ↓
Capital Requirement
       ↓
Cap Table
       ↓
Exit Valuation
       ↓
Investor Returns
```

This was the primary objective of the project: **to demonstrate the ability to translate a business concept into an integrated financial model and then use that model to support investment analysis.**

---

# Skills Demonstrated

### Financial Modelling

* Integrated P&L, CFS and SOFP
* Monthly forecasting
* Assumption-driven modelling
* Scenario analysis
* Revenue build
* Cost build
* Working capital / cash flow analysis
* Balance sheet modelling
* Runway analysis
* Break-even analysis

### Investment Analysis

* Pre-money / post-money valuation
* Cap table construction
* Ownership analysis
* Exit valuation
* Revenue multiple analysis
* MOIC
* IRR
* Investor proceeds

### Commercial Analysis

* Customer acquisition funnel
* DTC conversion economics
* Enterprise sales assumptions
* Product-level unit economics
* Pricing analysis
* Product mix
* Operating leverage

### Presentation & Communication

* Executive investment report
* Investor-oriented dashboards
* Financial KPI presentation
* Scenario interpretation
* Risk analysis
* Investment conditions and milestones

---

# Repository Structure

```text
EDGELITE-TECHNOLOGIES/
│
├── EDGELITE STARTUP MODEL.xlsx
│
├── EDGELITE TECHNOLOGIES - Executive Report.pdf
│
└── README.md
```

---

# What This Project Demonstrates

This project was built to demonstrate more than the ability to populate an Excel spreadsheet.

It demonstrates the ability to:

1. **Translate business assumptions into financial drivers**
2. **Build an integrated operating model**
3. **Model customer acquisition and revenue from operational inputs**
4. **Analyse unit economics and contribution margins**
5. **Forecast cash requirements and runway**
6. **Identify break-even requirements**
7. **Structure a startup financing and cap table**
8. **Evaluate potential investor returns**
9. **Stress-test the business through scenarios**
10. **Convert financial analysis into an executive investment document**

The model is intended to showcase practical capabilities relevant to **FP&A, investment analysis, corporate finance, financial modelling, venture capital and transaction-oriented roles.**

---

## Project Deliverables

**Excel Financial Model**

A fully integrated 24-month startup operating model covering assumptions, customer acquisition, revenue, costs, P&L, cash flow, balance sheet, cap table, investor returns, runway and break-even.

**Executive Investment Report**

A 17-page investor-facing analysis translating the model into an investment thesis, financial analysis, risk framework and return analysis.

---

## Author

**Opemipo Williams**

Financial Modeling · Investment Analysis · Corporate Finance

This project was developed as part of a financial modelling portfolio to demonstrate practical modelling, analytical and investment evaluation capabilities.
