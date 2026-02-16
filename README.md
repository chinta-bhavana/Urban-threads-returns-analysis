📊 Urban Threads: Operations & Returns Analytics (Q4 2024)

📌 Business Problem
Urban Threads (D2C Fashion brand) experienced a sharp increase in return rates, jumping from 12% to 19% in Q4 2024. This spike is costing the company approximately ₹18-22 Lakhs per month in reverse logistics and refunds.
The goal of this analysis is to identify the root causes of these returns and provide actionable recommendations to bring the rate below 15% without hurting sales.

🛠️ Data Cleaning & Validation (Section 1 & 2)
To ensure data reliability, the following steps were taken:
Missing Value Analysis: Handled missing return_reason and delivery_date based on business logic.
Format Standardization: Fixed inconsistent date formats and typos (e.g., "Delievered" vs "Delivered").
Logical Checks: Verified that order_total = unit_price × quantity after discounts and ensured delivery_date is not before order_date.
Outlier Detection: Flagged unusually high quantities and invalid discount percentages.

📈 Key Performance Indicators (KPIs)
I calculated the following core metrics to evaluate business health:
| KPI | Definition |
| Net Revenue | Total order value after applying all discounts. |
| Return Rate | (Orders with return initiated) / (Total Delivered orders). |
| RTO Rate | (Orders marked as Return to Origin) / (All shipped orders). |
| AOV | Average Order Value post-discounts.

🔍 Key Insights
Segment Risk: New customers have a significantly higher return rate (28%) compared to returning customers (10%).

Top Return Reason: 45% of returns are due to "Size Issues," indicating a major gap in product sizing information.

Channel Analysis: Instagram Shop shows the highest return rate despite having high engagement.

COD Impact: Cash on Delivery (COD) orders correlate with higher RTO rates compared to prepaid methods.


💡 Recommendations
Optimize Size Guides: Implement detailed size charts and a "Fit Assistant" tool to address the 45% size-related returns.

Prepaid Incentives: Offer small discounts for prepaid orders to reduce the RTO risk associated with COD.

Instagram Strategy: Review product photography and descriptions for Instagram Shop to ensure they match the physical product accurately.
