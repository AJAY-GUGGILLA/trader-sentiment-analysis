# Trader Performance vs Market Sentiment

This project analyzes how market sentiment (Fear vs Greed) impacts
trader behavior and performance on Hyperliquid.

------------------------------------------------------------------------

##  Overall Performance Summary

  -----------------------------------------------------------------------------
  Sentiment   Avg Daily    Median Daily    PnL Std    Avg Win     Avg Trade
              PnL          PnL                        Rate        Count
  ----------- ------------ --------------- ---------- ----------- -------------
  Fear        4819.67      125.67          28426.60   0.3568      89.88

  Greed       3936.97      260.63          28272.72   0.3615      70.08
  -----------------------------------------------------------------------------

------------------------------------------------------------------------

## Behavioral Summary

  Sentiment   Avg Trade Count   Avg Position Size   Avg Long Ratio
  ----------- ----------------- ------------------- ----------------
  Fear        89.88             9357.60             0.522
  Greed       70.08             6168.43             0.474

------------------------------------------------------------------------

##  High vs Low Frequency Traders

  ------------------------------------------------------------------------------
  Segment     Sentiment   Avg Daily    Median Daily    Avg Win     Avg Trade
                          PnL          PnL             Rate        Count
  ----------- ----------- ------------ --------------- ----------- -------------
  High        Fear        6654.26      230.10          0.3871      139.69
  Frequency                                                        

  High        Greed       4395.64      553.53          0.4269      118.72
  Frequency                                                        

  Low         Fear        2661.63      0.00            0.3212      31.29
  Frequency                                                        

  Low         Greed       3550.31      0.20            0.3063      29.07
  Frequency                                                        
  ------------------------------------------------------------------------------

------------------------------------------------------------------------

## Consistent vs Volatile Traders

  -------------------------------------------------------------------------------
  Segment      Sentiment   Avg Daily    Median Daily    Avg Win     Avg Trade
                           PnL          PnL             Rate        Count
  ------------ ----------- ------------ --------------- ----------- -------------
  Consistent   Fear        239.07       73.75           0.3611      39.41

  Consistent   Greed       1773.34      389.46          0.3923      64.95

  Volatile     Fear        9613.88      569.22          0.3523      142.71

  Volatile     Greed       8220.30      0.00            0.3005      80.23
  -------------------------------------------------------------------------------

------------------------------------------------------------------------

## Key Insights

-   Traders increase activity and position size during Fear regimes.
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

------------------------------------------------------------------------

