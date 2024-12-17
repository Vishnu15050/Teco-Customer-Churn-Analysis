# Teco-Customer-Churn-Analysis
○ Executive Summary of Customer Churn Analysis

2. Dataset Overview:
The analysis leverages the Telco Customer Churn dataset, which contains customer
demographics, service subscriptions, and billing details. The primary objective is to
identify patterns in customer churn (leaving the service) and highlight actionable
insights for retention strategies.

4. Churn Distribution:
○ Churned Customers account for approximately 27% of the total customer base,
whereas 73% did not churn.
○ This imbalance highlights the importance of identifying churn predictors to target
at-risk customers effectively.

6. Service-Based Insights:
○ Phone Service:
Customers with Phone Service make up a large majority, yet churn rates remain
similar for customers with and without phone service.

○ Multiple Lines:
■ Customers with No Phone Service have negligible churn.
■ Customers with Multiple Lines churn at a 25% rate, slightly higher than
those with a single line.

○ Internet Service:
■ Customers with Fiber Optic internet show the highest churn rate at
approximately 42%, indicating dissatisfaction or competition in this
segment.
■ In contrast, customers with DSL have lower churn (~25%), while those
with no internet service exhibit the least churn (~8%).

8. Add-On Services and Churn:
Customers without additional services such as Tech Support, Online Security, and
Streaming TV/Movies are more likely to churn:

○ Online Security:
■ Customers with no Online Security: 30% churn.
■ Customers with Online Security: Only 15% churn.

○ Tech Support:
■ Customers with no Tech Support: 32% churn.
■ Customers with Tech Support: 14% churn.

○ Streaming TV and Movies:
■ Customers not using Streaming TV or Movies show higher churn
(~31%), whereas those availing these services churn less (~20%).
10. Insight: Add-on services, like Online Security or Tech Support, correlate strongly with
reduced churn rates.

11. Contract Type and Churn:
Contract duration has a significant impact on churn:
○ Month-to-Month contracts have the highest churn at 45%, indicating a lack of
long-term commitment.
○ One-Year contracts see lower churn at 11%, and Two-Year contracts exhibit
the least churn at 3%.
12. Recommendation: Encouraging customers to switch to longer contracts can
substantially reduce churn.

14. Tenure Impact:
○ Customers with shorter tenure (0–12 months) show the highest churn rate at
52%.
○ Churn declines as tenure increases, with customers staying more than 2 years
exhibiting churn rates below 10%.
15. Insight: Retention efforts should focus on newer customers in the early stages of their
subscription.

17. Payment Methods:
Payment methods reveal interesting churn patterns:
○ Customers paying via Electronic Check experience the highest churn at 41%.
○ Customers using Credit Card, Bank Transfer, or Mailed Checks show much
lower churn rates (~12%–15%).
18. Recommendation: Investigate customer experience with electronic check payments
and promote alternate, more stable payment methods.

20. Visualizations:
Effective use of countplots and stacked bar charts provides visual clarity on churn
distribution across services and customer attributes, highlighting key problem areas.
Key Findings & Recommendations:
● Focus on retaining Fiber Optic internet users and customers on month-to-month
contracts.
● Encourage longer contract durations and bundled services (e.g., Online Security and
Tech Support).
● Pay special attention to newer customers (short tenure) and users relying on
electronic check payments.
● Incentivize add-on services to improve overall satisfaction and reduce churn.
