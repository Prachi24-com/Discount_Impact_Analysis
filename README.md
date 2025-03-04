**Business Case Study Report: Discount Impact Analysis**

### 1. Executive Summary
This report analyses the impact of discount campaigns on customer spending behaviour, identifies customer segments most responsive to discounts, and provides recommendations to maximize revenue while maintaining profitability.

### 2. Objectives
**Key Goals:**
- Compare customer spending before and after discount campaigns.
- Identify high-value and discount-responsive customer segments.
- Recommend optimal discount strategies.

### 3. Methodology
**Data Source:**
- discount_campaign.csv containing customer order counts and spending before and after discounts.

**Tools Used:**
- Python for data analysis.
- K-Means clustering for customer segmentation.

**Analysis Approach:**
- Calculated changes in total and average customer spending.
- Performed clustering to group customers based on order frequency and spending behaviour.

### 4. Analysis and Findings
**1. Change in Average Spending Pattern per Customer After Discount:**
- Average spend per customer before the discount campaign: **$2572.65**
- Average spend per customer after the discount campaign: **$5136.13**

**Insight:** There’s a significant increase in customer spending after the discount campaign.

**2. Spending Behaviour of Customers Segment-wise:**
| Segment   | Average Spend Before | Average Spend After | Increase/Decrease |
|-----------|---------------------|-------------------|------------------|
| Segment 1 | $3654.17           | $7654.61        | +$4000.44       |
| Segment 2 | $1041.59           | $4835.85        | +$3794.26       |
| Segment 0 | $3514.87           | $2345.54        | -$1169.33       |

**Insight:** Segments 1 and 2 showed a significant increase in spending after the discount campaign, indicating they are most responsive to discounts.

**3. Overall Analysis of Demand Pattern After Discount:**
| Customer Type       | Average Spend Before | Average Spend After | Increase       |
|------------------|---------------------|-------------------|---------------|
| Without Discounts | $2538.72           | $5092.11        | +$2553.39    |
| With Discounts    | $2607.67           | $5181.59        | +$2573.92    |

**Insight:** Customers with discounts spent slightly more than those without, indicating moderate discounts are effective without heavily impacting profitability.

### 5. Recommendation
1. **Targeted Discounts:** Focus discounts on **Segment 1** and **Segment 2** as they showed the highest increase in spending.

2. **Optimal Discount Rates:**
   - High-value customers (**Segment 1**): Smaller discounts to maintain profitability.
   - Low-to-mid value customers (**Segment 2**): Higher discounts to encourage spending growth.

3. **Strategy:**
   - Offer **tiered discounts** based on spending history.
   - Use **seasonal and limited-time discounts** to drive peak sales periods while avoiding discount fatigue.

This approach balances increased revenue with controlled discount costs for long-term profitability.

