# Mutual-Funds-Analysis
Analyze Nifty 50 closing prices to create a mutual fund plan based on high ROI and low risk.
Overview  
### 🎯 Objective  
To create a **mutual fund investment plan** that balances **high return on investment (ROI)** with **low risk (volatility)** using Python.

### 🧹 Data Cleaning  
- Loaded **NIFTY 50 closing prices** from a CSV dataset.  
- Converted the `Date` column to datetime format.  
- Checked and confirmed there were **no missing values**.  

### 📊 Data Analysis  
- **Volatility**: Calculated as the standard deviation of closing prices for each stock.  
- **Growth Rate**: Computed as the average percentage change over time.  
- **ROI (Return on Investment)**: Measured as the percentage increase in price over the analysis period.  
- Identified **high-ROI** and **low-risk** companies suitable for stable, long-term investment.  

### 💡 Insights  
- **High ROI + Low Volatility** stocks are ideal for a balanced mutual fund portfolio.  
- High growth stocks often show higher volatility (higher risk).  
- Companies with **moderate returns** and **low risk** demonstrate **steady compounding growth**, suitable for long-term investors.  

### 📦 Deliverable  
A **Mutual Fund Plan** that includes:
- Recommended **investment ratios** for selected companies.  
- **Projected portfolio growth** over time based on monthly investments and compounding.  

---

## 🚀 Extended Overview (Milestone 0)

### 🧾 Data Collection & Cleaning  
- Imported **NIFTY 50 closing prices** from `nifty50_closing_prices.csv`.  
- Converted dates using `pd.to_datetime()` for time-series analysis.  
- Verified dataset completeness — no missing data found.  

### 📈 Data Analysis  
- Calculated:
  - **Volatility** = standard deviation of daily returns (risk).  
  - **Growth Rate** = average daily % change.  
  - **ROI** = (Final Price − Initial Price) / Initial Price × 100.  
- Classified companies by **risk vs return** and selected the optimal subset.  

### 🖼️ Data Visualization  
- **Line plots** of stock price trends over time for selected NIFTY 50 companies.  
- **Bar charts** comparing volatility vs ROI across all companies.  
- **Scatter plots** highlighting the balance between growth and stability.  

### 📊 Trend Analysis  
- Observed that stock prices fluctuate dynamically across sectors.  
- **High-growth companies** show higher volatility, indicating higher short-term risk.  
- **Low-volatility companies** with moderate ROI provide **consistent long-term gains**, aligning with mutual fund investment philosophy.  

### 🧮 Summary & Mutual Fund Construction  
- **Selection Criteria:**  
  - ROI > median ROI  
  - Volatility < median volatility  
- **Weight Allocation:**  
  - Investment ratios were assigned **inversely proportional to volatility**, giving higher weight to stable companies.  
- **Projection Model:**  
  - Simulated **monthly SIP (Systematic Investment Plan)** contributions.  
  - Incorporated **annual increase** in investment and **compound growth**.  
  - Projected **future portfolio value** over 5, 10, and 15 years to demonstrate compounding benefits.  

---

## 💰 Result  
A **Mutual Fund Plan** consisting of the top performing low-risk NIFTY 50 stocks, along with:  
- Calculated investment weights per stock.  
- Simulated total portfolio growth over time.  
- Visualization of fund performance vs. high-growth portfolios.

This demonstrates **how professional mutual funds are designed** — by combining diversification, stable growth, and compounding for long-term wealth creation.  

---

## 🧰 Tools & Technologies  
- **Python 3.x**  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
