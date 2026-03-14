# Bitcoin-Market-Sentiment-Analysis

Problem Statement: Explore the relationship between trader performance and market 
sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading 
strategies.

## Technologies Used-
Python,
Pandas,
Scikit-learn,
Seaborn,
Matplotlib

## Analysis-
1. The "Extreme Greed" Outperformance: Statistically, trades closed during Extreme Greed exhibited the highest win rate at $\approx 89.2\%$. This indicates that the "momentum" or "trend-following" strategy is highly effective in Bitcoin markets during periods of maximum euphoria, as the price continues to push higher than typical logic suggests.
2. Contrarian Fear Performance: Periods of Fear also showed a strong win rate ($\approx 87.3\%$), significantly higher than Greed ($\approx 76.9\%$). This suggests that entering or closing trades during "Fear" is a safer statistical bet than during moderate "Greed," where market reversals are more frequent and unpredictable.
3. The "Neutral" Trap: Interestingly, Neutral sentiment levels show lower profitability compared to the extremes. This implies that "Range-bound" or "Undecided" markets increase the probability of getting "chopped" (losses due to lack of clear direction).
4. Optimal Trading Hours: Trade performance fluctuates significantly by the hour. The most profitable window identified was around 18:00 (6 PM) and 09:00 (9 AM). These likely correspond to the New York market open/close transitions and the Asian market overlap, where "liquidity" is highest, allowing for better fills and clearer price discovery.

## Result -
-Accuracy: ~97–99% (depending on data split)

-Evaluation Metrics: Accuracy Score, Confusion Matrix, Classification Report (Precision, Recall, F1-score)



