# Indian Startup Funding Analysis (2015–2020)

**An end-to-end data analytics project exploring Indian startup funding trends, industry concentration, startup hubs, funding stages, and investor activity.**

## 1. Business Problem

Analyze Indian startup funding data from 2015 to 2020 to uncover trends in investment activity, identify industries and cities attracting the most capital, understand funding-stage distributions, and examine key investors.

## 2. Business Questions

This project addresses six core questions:

1. How did funding amounts and deal counts change monthly and yearly?
2. Which industries attracted the most funding, and how did their rankings change over time?
3. Which cities had the highest disclosed funding volumes?
4. How was funding distributed across investment stages and types?
5. Which investor entries ranked highest by deal count and disclosed funding?
6. How did average and median deal sizes vary across industries and funding stages?

## 3. Tools and Technologies

- **Power BI:** Interactive dashboards and KPI reporting
- **DAX:** Measures and calculated columns
- **Power Query:** Data transformation and cleaning
- **Python / Pandas:** Data cleaning and exploratory analysis
- **MySQL:** Business analysis queries

## 4. Dashboard Pages

**Page 1 — Executive Overview**  
Funding KPIs, annual funding trends, industry concentration, and leading cities.

**Page 2 — Industry, City & Investor Analysis**  
Industry funding, geographic distribution, city rankings, and investor comparisons.

**Page 3 — Funding Stage & Deal Size Analysis**  
Funding-stage distribution, yearly stage mix, deal-size bands, and average-versus-median comparisons.

## 5. Key Findings

Based on the supplied cleaned dataset:

| Metric | Result |
|---|---:|
| Total funding records | 3,044 |
| Records with numeric funding amounts | 2,073 |
| Records with missing funding amounts | 971 |
| Total disclosed funding | Approximately $38.14 billion |
| Average disclosed deal size | Approximately $18.40 million |
| Median disclosed deal size | Approximately $1.75 million |

The funding amounts are treated as USD because that is the source field's stated currency label; the currency metadata has not been independently verified.

## 6. Data Quality and Limitations

- Approximately 31.9% of records have no usable numeric funding amount.
- The supplied 2020 data contains January-only records, so full-year comparisons are incomplete.
- Industry and funding-type labels may be inconsistent.
- Investor fields can contain multiple names in one cell; rankings therefore may reflect source strings rather than individually normalized investors.
- Missing funding amounts are excluded from funding-value calculations rather than treated as zero.

## 7. Project Files

The repository contains the available Power BI dashboard, raw and cleaned datasets, Python notebook, SQL queries, project report, management presentation, and supporting dashboard screenshots.

## 8. Conclusion

This project demonstrates a data analytics workflow from data preparation and exploratory analysis to SQL-based business questions, Power BI visualisation, and evidence-based recommendations.

The findings describe disclosed funding in the supplied dataset and should not be interpreted as a complete estimate of the Indian startup funding market.

## Author

**Vikant Kumar**  
Data Analyst Project
