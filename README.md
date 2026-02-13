Project: Trader Performance vs Market Sentiment

Methodology:
- Cleaned datasets
- Converted timestamps (dayfirst=True)
- Merged at daily level
- Created PnL, win rate, trade frequency metrics
- Segmented traders into size, frequency, and consistency groups

Key Insights:
🔎 Insight 1 — Panic Markets Reward Discipline

During Extreme Fear, consistent traders generate significantly higher average PnL (~81) compared to inconsistent traders (~34), indicating that disciplined strategies perform better under high stress conditions.

🔎 Insight 2 — Greed Favors Aggressive Behavior

In Greed and Extreme Greed phases, inconsistent traders outperform consistent traders, suggesting that risk-seeking behavior benefits during bullish sentiment periods.

🔎 Insight 3 — Neutral Markets Are Less Predictable

Consistent traders underperform in neutral conditions, while inconsistent traders maintain moderate profitability, implying lower edge during directionless markets.

Strategy Recommendations:
💡 Strategy Rule 1:

During Extreme Fear days, prioritize systematic or disciplined strategies and reduce discretionary overtrading.

💡 Strategy Rule 2:

During Greed/Extreme Greed periods, allow higher trade frequency and moderate size expansion, particularly for traders with historically aggressive profiles.

How to Run:
- pip install -r requirements.txt
- Run notebook.ipynb