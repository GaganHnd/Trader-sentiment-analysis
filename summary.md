Trader Performance vs Market Sentiment

Data Science Intern – Round 0 Assignment

1️⃣ Objective

The goal of this analysis was to examine how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance on Hyperliquid, and to extract actionable strategy insights.

2️⃣ Methodology

Cleaned and standardized both datasets (sentiment + historical trades).

Converted timestamps using dayfirst=True to handle IST format.

Aggregated trades at daily level and merged with sentiment classification.

Created performance metrics:

Daily PnL per trader

Win rate

Trade frequency

Average trade size (Size USD)

PnL volatility (risk proxy)

Segmented traders into:

Frequent vs Infrequent traders

Consistent (>60% win rate) vs Inconsistent traders

High vs Low position size traders

Leverage was not available in the dataset; therefore, position size and PnL volatility were used as proxies for risk exposure.

3️⃣ Key Findings
🔹 1. Extreme Fear Rewards Discipline

Consistent traders significantly outperform inconsistent traders during Extreme Fear periods
(~81 vs ~34 average PnL).

This suggests structured, rule-based trading performs better in panic-driven markets.

🔹 2. Greed Favors Aggressive Behavior

During Greed and Extreme Greed phases, inconsistent traders outperform consistent traders.

This indicates that higher-risk, aggressive strategies benefit during bullish sentiment.

🔹 3. Neutral Markets Reduce Edge

Consistent traders underperform during Neutral conditions, while inconsistent traders maintain moderate profitability.

This implies reduced directional clarity lowers systematic trading edge.

🔹 4. Sentiment Influences Risk Distribution

PnL dispersion (volatility proxy) increases during Fear regimes, indicating higher uncertainty and wider performance spread among traders.

4️⃣ Behavioral Observations

Trade frequency increases during Greed phases.

Position sizes are moderately larger during optimistic sentiment.

Performance asymmetry exists between panic vs optimism regimes.

This confirms that traders adjust behavior based on sentiment conditions.

5️⃣ Strategy Recommendations
💡 Strategy 1: Risk Calibration During Fear

During Extreme Fear days:

Reduce discretionary overtrading.

Favor systematic or historically consistent traders.

Monitor drawdown exposure due to higher volatility.

💡 Strategy 2: Tactical Expansion During Greed

During Greed / Extreme Greed:

Allow moderate increase in trade frequency.

Allocate slightly more capital to aggressive trader segments.

Monitor for volatility compression before reversal risk.

6️⃣ Conclusion

Market sentiment significantly influences both trader performance and behavior.
Panic regimes reward discipline, while optimism benefits aggressive participation.

Incorporating sentiment-aware position sizing and trader segmentation can improve risk-adjusted returns.