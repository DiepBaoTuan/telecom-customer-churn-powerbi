# Telecom Customer Churn Dashboard (Power BI)

An interactive Power BI report that explains **who is leaving a telecom provider and why**, by comparing churned customers against the whole customer base.

**File:** [`MP1.pbix`](MP1.pbix). Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).

## Report pages

| Page | What it shows |
|---|---|
| **Customer Overview** | Churn profile vs. all customers: age group (under/over 30), tenure, contract type, payment method, average monthly and total charges |
| **Customer Detail** | One-customer view selected with a slicer: plan, services, charges, calls, churn status and reason |
| **Churn Reason** | Churn by category, top 5 churn reasons, and a decomposition tree to drill into the drivers |
| **Ask a Question** | Q&A visual for natural-language questions about the data |

## Key metrics

- Churn count and churn share for each segment, shown side by side with the overall share
- Service adoption among churners vs. all customers: international plan, unlimited data plan, group plan, device protection and online backup
- Average monthly charge and average total charge: churned vs. all customers

## Skills demonstrated

Data modelling · DAX measures (segment percentages, comparison metrics) · Binning (tenure groups) · Drill-down with the decomposition tree · Report design with KPI cards
