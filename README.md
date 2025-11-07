# Market Sentiment vs Trader Performance Analysis

## Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and real trading performance metrics.  
By combining sentiment data with historical trading records, it identifies how market emotions influence profitability, trade volume, and decision-making behavior.

---

## Key Features
- Automated data cleaning and timestamp alignment  
- Aggregated daily performance metrics (Execution Price, PnL, Volume, Fees)  
- Integration of Fear & Greed Index with trading performance  
- Correlation and trend analysis between sentiment and returns  
- Predictive modeling using Random Forest Regression  
- Visual analytics for performance and sentiment insights

---

## Datasets Used

### 1. historical_data.csv
| Column Name | Description |
|--------------|-------------|
| Account | Trader Account ID |
| Coin | Cryptocurrency (e.g., BTC, ETH) |
| Execution Price | Trade execution price |
| Size Tokens | Token quantity traded |
| Size USD | Trade value in USD |
| Side | Buy/Sell side |
| Timestamp IST | Trade timestamp in IST |
| Start Posit | Position status |
| Direction | Trade direction |
| Closed PnL | Profit or loss on trade |
| Transaction Hash | Trade identifier |
| Order ID | Unique order reference |
| Crossed | Cross trade indicator |
| Fee | Transaction fee |
| Trade ID | Trade reference |
| Timestamp | UTC timestamp |

### 2. fear_greed_index.csv
| Column Name | Description |
|--------------|-------------|
| timestamp | Recorded timestamp |
| value | Fear & Greed Index (0–100) |
| classification | Market sentiment (Fear, Neutral, Greed) |
| date | Corresponding date |

---

## Tech Stack
- **Language:** Python 3.x  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, datetime, os

---

## Workflow
1. Load and preprocess both datasets  
2. Convert timestamps and align sentiment with trading data  
3. Aggregate daily metrics for execution, volume, and profit/loss  
4. Merge Fear & Greed Index with daily trading performance  
5. Conduct exploratory data analysis (EDA) for correlation and distribution patterns  
6. Train a Random Forest model to predict Total PnL based on sentiment and trade metrics  
7. Visualize relationships between sentiment and profitability

---

## Results and Insights
- Positive correlation between greed-phase sentiment and higher trading profits  
- Fear periods correlate with reduced trade activity and higher volatility  
- Random Forest model achieved low RMSE, showing strong predictive accuracy for daily PnL  
- Sentiment data adds explanatory power to trading behavior analysis

---

## Skills Demonstrated
- Data preprocessing and cleaning  
- Exploratory data analysis (EDA)  
- Financial and behavioral analytics  
- Machine learning regression modeling  
- Feature importance and correlation analysis  
- Data visualization and interpretation
---

## Conclusion
This project demonstrates how integrating emotional market sentiment with quantitative trading data provides actionable insights into trader performance and market behavior.  
It showcases practical expertise in data analytics, visualization, and predictive modeling for real-world financial datasets.
