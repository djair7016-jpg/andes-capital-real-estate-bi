# Andes Capital Real Estate: Commercial Performance Dashboard

## Executive Summary

Andes Capital Real Estate needed a consolidated view of its commercial performance to understand which property types, cities, sales channels, and customer segments generated the strongest results.

I developed a three-page Power BI dashboard using a star schema, DAX measures, time intelligence, and cohort analysis. The report evaluates revenue, sales volume, average ticket, commissions, year-over-year performance, customer segments, and repeat-purchase behavior.

The analysis covered 8,500 sales transactions associated with 5,223 properties. Revenue increased by 11.1% year over year. Houses generated 37.3% of total revenue, the Broker channel accounted for 72.8%, and First-time buyers represented 62.9% of revenue.

Based on these results, I recommended prioritizing high-value properties, strengthening customer retention, and evaluating the expansion of the Direct sales channel.

## Business Problem

The project focused on five business questions:

- How is revenue and sales volume evolving over time?
- Which property types generate the highest commercial value?
- Which cities and customer segments contribute most to revenue?
- Which sales channels dominate the business?
- Which customer cohorts show the strongest repeat-purchase behavior?

The objective was to transform transactional sales data into an executive tool that could support commercial planning, channel strategy, and customer retention decisions.

## Data Model

The Power BI model was structured using:

- A sales fact table containing transactions, revenue, commissions, customers, and properties.
- A customer dimension with client segments and identifiers.
- A property dimension with property type, city, and commercial attributes.
- A date dimension used for time-intelligence calculations.

The relationships were organized as a star schema to improve filtering, measure consistency, and report performance.

## Dashboard Structure

### 1. Executive Overview

The executive page summarizes:

- Total revenue
- Number of sales
- Average ticket
- Total commissions
- Revenue trends
- Performance by city
- Year-over-year growth

### 2. Commercial Analysis

The commercial page evaluates:

- Revenue by property type
- Sales-channel participation
- Customer-segment performance
- Sales volume and average ticket
- High-value commercial opportunities

### 3. Cohort Analysis

The cohort page groups customers according to their first purchase and evaluates:

- Revenue by cohort
- Repeat-purchase behavior
- Customer activity over time
- Cohorts with the greatest retention potential

## Key Findings

- Revenue increased by 11.1% compared with the previous year.
- Houses generated 37.3% of total revenue, making them the highest-revenue property type.
- The Broker channel accounted for 72.8% of revenue, showing a strong dependence on intermediated sales.
- First-time buyers contributed 62.9% of revenue.
- Customer cohorts showed differences in repeat-purchase behavior and long-term value.

## Business Recommendations

- Prioritize the promotion of high-value property types while maintaining sales volume in faster-moving categories.
- Develop the Direct sales channel to reduce dependence on brokers and improve channel diversification.
- Implement follow-up strategies for First-time buyers to encourage future purchases.
- Replicate acquisition and retention practices from the cohorts with the strongest repeat-purchase behavior.
- Monitor revenue, ticket size, commissions, and customer recurrence through the Power BI dashboard.

## Tools and Techniques

- Power BI
- DAX
- Star-schema data modeling
- Power Query
- Time intelligence: YTD, MTD, and YoY
- KPI development
- Cohort analysis
- Executive data visualization

## Repository Structure

```text
data/       Source datasets used in the analysis
powerbi/    Interactive Power BI report
images/     Dashboard screenshots
README.md   Project documentation
