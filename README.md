Marketing A/B Testing

Goal: Evaluate the results of an A/B test (new ad vs. old ad) and determine which campaign is more effective.

Data
- Files: control_group.csv (Control), test_group.csv (Test).
- Description: 30-day metrics (Impressions, Clicks, Purchases, Spend).

Completed Tasks
1. Preprocessing:
   - Handled non-standard delimiters (;).
   - Filled missing values with mean values.

2. Metrics Calculation:
   - CTR (Click-Through Rate): Test Group (8.09%) > Control Group (4.86%).
   - Conversion Rate (CR): Control Group (9.83%) > Test Group (8.64%).

3. Hypothesis Testing:
   - Chi-Squared Test: P-value < 0.05. The difference in conversion rates is statistically significant.
   - T-Test: The difference in daily average purchases is not statistically significant.

Conclusion and Recommendation
The new campaign attracts more attention (higher CTR), but the old campaign drives more sales (higher CR).
Recommendation: Use the creatives from the Test Group to drive traffic, but optimize the sales funnel on the website to improve the conversion rate to match the Control Group level.
