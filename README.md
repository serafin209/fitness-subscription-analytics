Fitness Subscription Analysis

Project Overview

This project analyzes customer retention, subscription revenue, and customer acquisition cost (CAC) using Tableau. The analysis uses two tables from Fitness_Subscriptions_Dataset.xlsx: customers and transactions, related through Customer_ID.

The report contains three analytical views:

Customer Cohort: Tracks monthly retention by customer signup cohort.

Revenue Forecast: Forecasts subscription revenue for the next 12 months.

CAC vs. LTV: Compares cumulative customer lifetime value with acquisition cost for the 2024 and 2025 cohorts.

Customer Cohort Analysis

Customer retention remains approximately 85% after one month and 78% after two months, but falls sharply to approximately 50% in month three. This is the largest and most consistent decline across the monthly cohorts. Therefore, customers typically appear to cancel after about two months, entering their third month.

The business should focus its retention efforts before this drop occurs. Onboarding support, engagement campaigns, progress check-ins, and renewal incentives should be delivered during the first two months of a customer's subscription.

Method note: The dataset does not contain a separate cancellation date. Cancellation behavior is inferred from customers no longer producing monthly subscription transactions.

Revenue Forecast

The Tableau forecast projects continued subscription revenue growth over the next 12 months. Estimated monthly revenue increases from approximately $187,000 at the beginning of the forecast to approximately $268,000 by the end. Based on the forecast line, expected subscription revenue over the full 12-month period is approximately $2.7 million.

The forecast does not show strong repeating seasonal peaks and valleys. Its most visible pattern is a sustained upward trend, while the widening 95% prediction interval indicates that uncertainty increases further into the forecast period. Actual results should therefore be monitored and the forecast refreshed as new monthly data becomes available.

CAC vs. LTV Analysis

The 2024 cohort reaches its CAC break-even point in month 4. At that point, cumulative LTV is approximately $505,199, exceeding total CAC of approximately $501,537.

The 2025 cohort reaches break-even in month 6. At that point, cumulative LTV is approximately $1,208,333, exceeding total CAC of approximately $1,162,459.

The 2024 cohort therefore recovered its acquisition costs approximately two months faster than the 2025 cohort. Although the 2025 cohort generates more total revenue, its larger acquisition investment takes longer to recover. The business should review the acquisition channels and CAC composition of the 2025 cohort to identify opportunities to improve marketing efficiency and shorten the payback period.

Recommendations

Launch retention interventions during customers' first two months, before the large month-three decline.

Continue planning for subscription revenue growth while monitoring the widening forecast uncertainty.

Compare acquisition channels within the 2025 cohort and shift spending toward channels with faster CAC recovery.

Refresh the cohort, forecast, and break-even analyses monthly as new transaction data becomes available.
