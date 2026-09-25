# Sales & Finance Dashboard
### Understanding what drives revenue—and where the business needs to act
## Why I Built This Dashboard
Revenue alone does not explain whether a business is performing well. Sales can increase while customers buy less, customer relationships weaken, or reporting gaps hide changes in channel performance.
I built this Power BI dashboard to investigate the drivers behind sales performance: customer acquisition and retention, cylinder demand, revenue per cylinder, and the contribution of different products, industries, and order channels.
The objective was to identify where management should focus its attention and turn the analysis into practical recommendations.
## Business Context
The dataset contains 224,670 order items covering January 2017 to 21 November 2022, representing:
- **€28.30 million in revenue**
- **615,067 cylinders**
- **€46.02 average revenue per cylinder**
These are totals across the full dataset. Year-over-year comparisons use comparable periods through 21 November because 2022 is incomplete.
## Main Findings
### 1. Revenue growth masks declining cylinder demand
The dashboard shows approximately **3% revenue growth**, alongside an **8% decline in cylinder volume** and a **12% increase in revenue per cylinder** in the displayed year-over-year comparison.
This is the central finding: the business is generating more revenue per cylinder while selling fewer cylinders.
Higher average revenue per cylinder is offsetting the reduction in volume. However, this measure reflects both pricing and sales mix, so the analysis does not establish that price increases alone caused the improvement.
**Why this matters:** focusing only on revenue growth could hide weakening demand. If volume continues to decline, maintaining revenue may become increasingly dependent on higher prices or a more valuable product mix.
**What I would do:**
- Break the volume decline down by customer, product, and industry.
- Identify whether it comes from lost customers, lower order frequency, or smaller orders.
- Compare the same products over time to separate pricing changes from product mix.
- Add margin data to assess whether higher revenue per cylinder also improves profitability.
### 2. Retention deserves attention alongside acquisition
The customer analysis reports **72% retention**, while **20.4% of revenue comes from customers classified as new**.
Acquisition is contributing to sales, but the retention result highlights a group of previously active customers who did not purchase in the comparable period.
**Why this matters:** winning new customers may not produce sustainable growth if existing customers stop buying or reduce their activity. Some apparent losses may also reflect irregular purchasing cycles, so they require investigation before being treated as permanent churn.
**What I would do:**
- Prioritise previously valuable customers whose purchases stopped or declined.
- Give account managers a customer list ranked by lost revenue and reduced volume.
- Investigate service issues, pricing concerns, product availability, and changing customer needs.
- Track customer reactivation, repeat purchasing, and retained revenue to assess whether interventions work.
### 3. Missing channel attribution limits reliable decisions
The data quality review shows that **39.6% of 2022 revenue is attributed to `UNKNOWN SOURCE`**.
This makes it difficult to explain how the channel mix is changing. An apparent decline in a known channel could partly reflect orders being recorded without a channel.
**Why this matters:** management cannot confidently assess channel performance or allocate resources when a substantial share of revenue lacks attribution.
**What I would do:**
- Investigate where channel information is lost in the order process.
- Standardise channel definitions across source systems.
- Make channel capture mandatory where operationally appropriate.
- Monitor the percentage of unattributed orders and revenue each month.
The customer transition visual helps identify observed changes in channel use, but it does not prove why those changes occurred.
### 4. Revenue exposure is uneven across products and industries
Construction is the largest revenue-generating industry segment in the report, while Cylinder Helium leads product supergroups by revenue and average revenue per cylinder.
**Why this matters:** performance in these areas has a disproportionate influence on the overall result. Strong total revenue can conceal weaker performance elsewhere, while a downturn in a major segment could materially affect sales.
**What I would do:**
- Monitor volume, revenue, and retention within the largest segments.
- Review dependence on major customers within those segments.
- Evaluate smaller segments using both growth rates and absolute revenue contributions.
- Use margin and market information before deciding where to expand or reduce investment.
## Why I Structured the Analysis This Way
I began with the overall revenue and volume picture, then examined customers, products, and channels to understand the underlying drivers.
The customer analysis tests whether growth is supported by lasting relationships. The volume and value analysis explains how revenue can rise despite lower demand. Segment and channel analysis identifies where changes are concentrated.
Finally, the methodology page makes the limitations visible so that business decisions reflect what the data can actually support.
## Methodology and Data Quality
- Counted distinct customers and orders to avoid duplication from multiple order items.
- Used comparable year-to-date periods to account for incomplete 2022 data.
- Defined new customers by their first observed purchase in the dataset.
- Retained **373 zero-value records** for review rather than automatically deleting them.
- Flagged **19 unclassified customers** and retained unknown channel values.
- Treated revenue per cylinder as an average value measure affected by sales mix.
## Conclusion
The main concern is that **revenue growth is being supported by higher average revenue per cylinder while cylinder demand is declining**.
My priorities would be to investigate the volume decline, protect valuable customer relationships, and repair missing channel attribution. These actions would help management distinguish sustainable growth from changes that temporarily support the headline revenue figure.
The purpose of this dashboard is to move the discussion from “How much did we sell?” to **“What changed, why does it matter, and where should we act?”**
## Tools
Power BI · DAX · Power Query · Excel
## Author
**Muiz Ajiboye**
