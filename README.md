# Power_BI_Retail_Customer_Retention_Analytics-WALMART

## Project Overview

Walmart, a global leader in multichannel retail, faces growing competition from Amazon, Target, and other retailers. Retaining and engaging customers is essential for Walmart's sustained growth. Despite collecting extensive customer, transaction, and loyalty data, Walmart's reporting lacked analytical clarity needed for retention strategy.

---

## Project Objective

- Consolidate customer demographics, purchase history, store/e-commerce, and loyalty program information into a single analytics platform.
- Enable executive-friendly segmentation of high-value, repeat, and churned customers.
- Deliver insights to improve retention, program engagement, and regional/channel strategies.
- Facilitate data-driven decisions through interactive, multi-page Power BI dashboards.

---

## Dashboard Overview

### Page 1: KPIs & Customer Segmentation

![KPI Dashboard](https://github.com/RishavVishnoi/Power_BI_Retail_Customer_Retention_Analytics-WALMART/blob/main/KPIs.jpg)

**Key Metrics Displayed:**
- Total Customers: 300
- Repeat Customers: 251 (84%)
- Churned Customers: 149 (49.7%)
- Average CLV: $126K
- Churn Rate Funnel visualization
- Segmentation by Region, Income Level, and Loyalty Tier

---

### Page 2: Repeat Purchase Analysis

![Repeat Purchase Analysis](https://github.com/RishavVishnoi/Power_BI_Retail_Customer_Retention_Analytics-WALMART/blob/main/Segmentation.jpg)

**Key Metrics Displayed:**
- Average Purchase Frequency: 3.4 purchases
- Frequency by Region and Age Group
- Most Purchased Product Categories by Loyal Customers
- CLV vs Days Since Last Purchase (Scatter Plot)
- Purchase Tier Segmentation (Low/Mid/High)

---

### Page 3: Store & Channel Performance

![Store Performance](https://github.com/RishavVishnoi/Power_BI_Retail_Customer_Retention_Analytics-WALMART/blob/main/Channel_Insights.jpg)

**Key Metrics Displayed:**
- Average Transaction Amount by Store Type
- Churn Rate by Store Type and Channel
- Retention Rate by Store Opening Year
- Channel Performance (Online vs Store)
- Regional insights with slicers

---

### Page 4: Promotion & Loyalty Impact

![Promotion & Loyalty](https://github.com/RishavVishnoi/Power_BI_Retail_Customer_Retention_Analytics-WALMART/blob/main/Loyalty_Impact.jpg)

**Key Metrics Displayed:**
- Transactions with Promotions Applied: 49%
- Average Purchase Amount (With vs Without Promotions)
- Points Earned vs Points Redeemed by Loyalty Tier
- Churn Rate by Loyalty Tier
- CLV by Loyalty Tier
- Average Purchase Frequency by Tier

---

## Key Findings and Insights

### Finding 1: Critical Churn Patterns
- **Overall churn rate is 49.7%**, indicating significant retention challenges across all segments.
- **Elite tier has highest churn (55%)** despite premium benefits - program value not meeting expectations.
- **Online channel shows 53.5% churn** vs 45.5% for stores - digital experience needs improvement.
- **West region leads churn at 60%** followed by Central (58%), lowest in South (41%).

### Finding 2: Loyalty Program Inefficiencies
- **Low redemption rates across all tiers** - Premium tier earned 201K points but redeemed only 171K.
- **Basic tier shows highest CLV (35K)** despite being lowest tier - value proposition misalignment.
- **Low income customers have 53% churn** - pricing or value perception issues for budget-conscious segment.
- **Promotions show 50/50 split** - neutral impact suggests they're not driving incremental retention.

### Finding 3: Store Performance Insights
- **Sam's Club and Neighborhood Market** lead in average transaction amounts ($534-531).
- **Churn rate consistent across all store types (49.7%)** - channel type not the differentiator.
- **Retention rate shows no strong correlation** with store opening year.
- **Online channel needs strategic focus** with higher churn and lower repeat rates.

---

## Recommendations

### 1. Prioritize High-CLV, At-Risk Customers
- Launch personalized win-back campaigns for high-value Elite customers with enhanced benefits
- Target customers with high CLV but increasing days since last purchase
- Offer exclusive, tier-specific redemption events

### 2. Address Underperforming Channels & Regions
- Focus improvement efforts on West and Central regions (60% and 58% churn)
- Enhance online channel experience to match in-store retention rates (45.5%)
- Implement region-specific promotions and loyalty incentives

### 3. Strengthen Loyalty Program Engagement
- Simplify redemption process and communicate clear value to customers
- Create bonus redemption events and tier upgrade challenges
- Run targeted campaigns for low-redemption segments

---

## Dashboard Features

### Interactive Slicers
- **Region:** Central, East, North, South, West
- **Preferred Channel:** Online, Store
- **Income Level:** Low, Medium, High
- **Loyalty Tier:** Basic, Plus, Elite, Premium

### Visualizations
- KPI Cards for quick metric overview
- Bar Charts for comparisons across segments
- Funnel Charts for customer drop-off analysis
- Scatter Plots for correlation analysis
- Matrix views for multi-dimensional analysis

---

## Data Model Structure

**Tables:**
1. Customer_Demographics (300 customers)
2. Customer_Transactions (1000+ transactions)
3. Loyalty_Program (tiered membership data)
4. Churn_Labelled_Customers (churn indicators and reasons)
5. Store_Locations (store types and regions)

**Key Relationships:**
- Customer_Demographics (1) → Many (Transactions, Loyalty, Churn)
- Store_Locations (1) → Many (Transactions)

---

## Technical Implementation

**Tools Used:**
- Microsoft Power BI Desktop
- Power Query for data transformation
- DAX for advanced calculations
- Multi-page report design

---

## How to Use This Dashboard

1. **Start with Page 1 (KPIs)** to understand overall retention metrics and top-level trends
2. **Explore Page 2 (Repeat Purchase)** to identify high-value and at-risk customers
3. **Review Page 3 (Store Performance)** for channel-specific insights
4. **Analyze Page 4 (Promotion & Loyalty)** to understand program effectiveness
5. **Use slicers across all pages** to drill down into specific segments (region, channel, income, tier)
6. **Cross-reference findings** across pages to develop integrated retention strategies

---

**Note:** All dashboard visuals are interactive. Use slicers to filter and explore data for specific business context.
