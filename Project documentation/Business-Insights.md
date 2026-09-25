# Business Insights
## E-Commerce Sales & Operations Analytics Dashboard

**Project:** E-Commerce Sales & Operations Analytics  
**Tool:** Microsoft Power BI  
**Analysis Period:** 2015–2018  
**Data Source:** Sample Superstore-style transactional sales dataset

---

## 1. Executive Summary

This project uses an interactive Power BI dashboard to explore e-commerce sales performance and shipping operations. The analysis covers sales trends over time, product category performance, geographic sales distribution, and shipping methods.

The dashboard provides a descriptive overview of the available data and helps identify patterns that may warrant further investigation.

### Key Performance Indicators

| KPI | Full Dataset Result |
|---|---:|
| Total Sales | Approximately $2.26 million |
| Total Orders | Approximately 5,000 |
| Average Order Value | $459.48 |
| Average Shipping Days | 4.0 days |

*Figures are rounded based on the dashboard display and represent the full dataset before slicers are applied.*

---

## 2. Key Findings and Business Relevance

### Finding 1: Annual Sales Increased Across the Period

**Observation:** Annual sales increased across 2015–2018, with 2018 recording the highest annual sales.

**Business relevance:** Reviewing sales over time gives stakeholders a historical view of performance and helps identify periods for deeper analysis.

**Suggested follow-up analysis:**
- Calculate year-over-year sales growth.
- Review monthly trends for recurring seasonal patterns.
- Compare order volume and average order value across years to understand which metrics moved alongside sales.

### Finding 2: Technology Had the Highest Sales by Category

**Observation:** Technology recorded the highest sales among Technology, Furniture, and Office Supplies.

**Business relevance:** Category-level sales comparisons show where sales are concentrated and help prioritize more detailed product analysis.

**Suggested follow-up analysis:**
- Identify the products and sub-categories contributing most to Technology sales.
- Compare order counts and average order value across categories.
- Review category performance by region.

### Finding 3: The West Region Recorded the Highest Sales

**Observation:** The West region recorded the highest sales, while the South recorded the lowest among the four regions.

**Business relevance:** Regional comparisons reveal how sales are distributed geographically and can help focus additional market and product analysis.

**Suggested follow-up analysis:**
- Compare state-level sales within each region.
- Examine category and sub-category performance by region.
- Compare order volume and average order value across regions.

### Finding 4: Average Shipping Duration Differed by Ship Mode

**Observation:** Standard Class had the highest average shipping duration, while Same Day had the lowest.

**Business relevance:** Comparing shipping duration by shipping method provides visibility into the time between an order being placed and being shipped.

**Suggested follow-up analysis:**
- Compare shipping duration by region and product category.
- Review the distribution of shipping days, not only the average.
- Investigate orders with unusually long order-to-ship durations.

**Measurement note:** Shipping Days is calculated as Ship Date minus Order Date. It measures the time from order placement to shipment, not the time until delivery to the customer.

### Finding 5: Standard Class Had the Highest Sales by Ship Mode

**Observation:** Standard Class accounted for the highest sales among shipping modes, while Same Day accounted for the lowest.

**Business relevance:** This shows how sales are distributed across the shipping methods recorded in the dataset.

**Suggested follow-up analysis:**
- Compare order counts by ship mode.
- Calculate average order value by ship mode.
- Compare ship-mode usage across regions and customer segments.

**Interpretation note:** Higher sales associated with a shipping mode do not establish that the shipping mode caused higher sales. Order volume, customer choices, and other factors may contribute.

### Finding 6: California Ranked Highest in the Top 10 States Chart

**Observation:** California recorded the highest sales among the states displayed in the Top 10 States by Sales chart.

**Business relevance:** State-level analysis provides a more detailed view of geographic sales concentration.

**Suggested follow-up analysis:**
- Compare sales and order counts across the top states.
- Examine category performance within California.
- Compare average order value across states.

---

## 3. Business Questions Addressed

| Business Question | Dashboard Component |
|---|---|
| How did sales change over time? | Sales by Year and Monthly Sales Trend |
| Which categories and sub-categories had the highest sales? | Sales by Category and Sales by Sub-Category |
| Which regions and states recorded the highest sales? | Sales by Region and Top 10 States by Sales |
| How were sales distributed across shipping methods? | Sales by Ship Mode |
| How did shipping duration differ by shipping method? | Average Shipping Days by Ship Mode |
| How do results vary across selected business segments? | Order Year, Region, and Category slicers |

---

## 4. Data Limitations and Assumptions

The dataset includes sales and shipping fields but does not contain profit, cost, or discount data.

As a result:

- Profit, margin, and profitability cannot be calculated.
- Discount effectiveness cannot be evaluated.
- The dashboard cannot establish why sales increased or why one category or region performed differently.
- Shipping Days measures order-to-ship time, not end-to-end delivery time.
- Findings describe the historical dataset and should not automatically be treated as current business performance.

Additional data and analysis would be needed before drawing causal conclusions or making operational decisions.

---

## 5. Conclusion

The dashboard provides an interactive overview of e-commerce sales and order-to-ship duration. It highlights historical sales patterns, differences across categories and regions, state-level sales concentration, and variation in shipping duration by ship mode.

The project demonstrates how transactional data can be prepared with Power Query, analyzed with DAX, and presented through interactive Power BI visualizations. The findings also identify opportunities for further analysis, including year-over-year growth, product-level performance, regional category mix, and shipping-duration distributions.
