# Trader Performance vs Market Sentiment

This project explores how market sentiment (Fear vs Greed) impacts
trader behavior and profitability on Hyperliquid. The goal was to
understand whether traders behave differently under different sentiment
regimes and whether those behavioral shifts affect performance.

------------------------------------------------------------------------

## Objective

-   Compare trader performance during Fear vs Greed regimes
-   Analyze behavioral changes (trade frequency, position size, long
    bias)
-   Segment traders based on activity and consistency
-   Propose actionable strategy recommendations
-   Build a simple predictive model (bonus)

------------------------------------------------------------------------

## Setup Instructions

1.  Clone the repository: git clone `<repo_link>`{=html}

2.  Install dependencies: pip install -r requirements.txt

3.  Run the notebook: jupyter notebook trader_sentiment_analysis.ipynb

------------------------------------------------------------------------

## Key Findings

-   Traders increase trade frequency and position size during Fear
    regimes.
-   Median profitability and win rate improve during Greed regimes.
-   High-frequency traders adapt better to sentiment shifts.
-   Volatile traders benefit from Fear volatility but struggle during
    Greed stability.
-   Logistic Regression achieved \~64% accuracy in predicting next-day
    profitability.

------------------------------------------------------------------------

## Strategy Recommendations

1.  Increase activity for consistent traders during Greed regimes.
2.  Volatile traders should reduce exposure during Greed periods.
3.  Apply stronger risk controls during Fear to reduce reliance on
    outlier gains.

This project demonstrates how sentiment-aware behavioral analysis can
improve adaptive trading strategies.

