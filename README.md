# trader-sentiment-analysis
Trader Performance vs Market Sentiment Analysis
Data Science Intern Assignment – Primetrade.ai

Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader behavior on Hyperliquid. The goal is to identify performance patterns, behavioral shifts, and actionable strategy insights.

Datasets Used

Historical Trader Data (Hyperliquid)

211,224 trades

Fields: Account, Size, PnL, Side, Timestamp, etc.

Bitcoin Fear & Greed Index

Daily sentiment classification

Categories: Fear, Greed, Extreme Greed, Neutral

Dates were aligned at daily resolution after converting trade timestamps from Unix milliseconds.

Final merged dataset: 184,263 rows

Methodology

Cleaned and standardized column names

Converted timestamps to datetime

Merged datasets by daily date

Engineered key metrics:

Daily PnL per trader

Win rate

Trade frequency

Average trade size

Trader segmentation (volume & consistency)

Analysis was conducted across sentiment regimes.

Key Findings
1️⃣ Greed Is the Most Profitable Regime

Highest average PnL: 87.89

Strong trend-following behavior observed

2️⃣ Fear Increases Activity but Reduces Efficiency

Highest trade frequency (133k+ trades)

Lower win rate (41.5%)

Suggests overtrading during uncertainty

3️⃣ Inconsistent Traders Are Vulnerable in Extreme Regimes

Large losses during Extreme Greed and Fear

Consistent traders remain stable across regimes

4️⃣ High-Volume Traders Outperform

Strong performance during Greed

Better resilience during volatile regimes

Actionable Strategy Recommendations
Strategy 1: Sentiment-Based Risk Adjustment

Reduce position sizing during Fear (–20–30%)

Increase trade participation during Greed with tighter trailing stops

Strategy 2: Trader-Specific Risk Controls

Restrict leverage for inconsistent traders during Extreme Greed

Allow dynamic exposure scaling for consistent high-volume traders

Business Implications

Sentiment regimes significantly influence behavioral risk

Platform-level risk controls can reduce extreme drawdowns

Trader segmentation improves capital efficiency

Conclusion:
Market sentiment acts as a behavioral amplifier.
Greed enhances profitability, while Fear increases trading intensity but lowers efficiency.
Adaptive risk management based on sentiment and trader type can significantly improve outcomes.
