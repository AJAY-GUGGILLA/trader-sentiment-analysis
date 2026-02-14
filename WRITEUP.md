# Trader Behavior Insights -- One Page Summary

## Methodology

Trade-level data was aggregated to daily trader-level metrics to align
with daily sentiment data. Engineered features included:

-   Daily PnL
-   Trade frequency
-   Win rate
-   Average position size
-   Long ratio

Sentiment was simplified into Fear and Greed regimes. Two segmentation
approaches were applied:

1.  High vs Low Frequency Traders (based on median trade activity)
2.  Consistent vs Volatile Traders (based on PnL standard deviation)

A Logistic Regression model was also trained to predict next-day
profitability using behavioral and sentiment features.

------------------------------------------------------------------------

## Key Insights

1.  Traders increase activity and exposure during Fear regimes,
    indicating higher risk-taking behavior.

2.  Median profitability and win rate improve during Greed regimes,
    suggesting more consistent performance.

3.  High-frequency traders dominate overall profitability and adapt
    better to sentiment conditions.

4.  Volatile traders benefit from Fear volatility but show reduced
    stability during Greed periods.

5.  The predictive model achieved \~64% accuracy, indicating measurable
    predictive signal from sentiment-aware behavioral features.

------------------------------------------------------------------------

## Strategy Recommendations

-   Encourage consistent traders to increase participation during Greed
    regimes.
-   Reduce exposure for volatile traders during Greed.
-   Strengthen risk management during Fear regimes.
-   Incorporate sentiment-aware features into adaptive trading models.

Conclusion: Market sentiment significantly influences trader behavior
and performance. Segment-level insights provide valuable inputs for
sentiment-conditioned trading strategies.
