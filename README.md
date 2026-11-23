# Diagnostic Centre Operational Performance Analysis

## Project Overview

This project examines the operational performance of a diagnostic centre using data analysis. It focuses on patient visits, laboratory test turnaround time, test charges and payment patterns.

The aim is to understand what the data reveals about the centre's operations, identify areas that may require attention and provide practical recommendations to support better decision-making.

## Project Objective

To analyse diagnostic centre operations, assess laboratory turnaround time, examine test charges and payment patterns, and identify opportunities for operational improvement.

## Tools Used

- **PostgreSQL (Neon):** Data exploration, querying, data quality checks and analysis.
- **Microsoft Excel:** KPI reporting, data summaries and visualisation.
- **Microsoft Power BI:** Interactive dashboards and performance reporting.

## Dataset Overview

The project uses a synthetic dataset containing four related tables:

| Table | Records |
|---|---:|
| Patients | 1,000 |
| Visits | 1,500 |
| Laboratory Tests | 2,000 |
| Payments | 2,000 |

**Data note:** The dataset is simulated for learning and portfolio demonstration. It does not contain real patient information or represent the actual operations of a diagnostic centre.

## Key Findings

- A total of 1,000 patients and 1,500 visits were recorded.
- Laboratory tests had a 92% completion rate, 5% pending rate and 3% cancellation rate.
- KFT and FBC recorded the highest average turnaround time at 13.10 hours each.
- Total recorded test charges amounted to ₦22 million.
- Payment records showed 60% paid, 20% partially paid and 20% unpaid.
- Each of the five departments recorded 300 visits.

## How I Think as an Analyst

Good data analysis is not just about finding numbers. It is also about understanding what those numbers can and cannot tell us.

For example, 20% of payment records were marked as unpaid. However, the dataset did not contain actual amounts paid or outstanding balances. Therefore, I could identify the percentage of unpaid records but could not calculate the actual amount owed.

I also observed that all five departments recorded exactly 300 visits. Since the dataset is synthetic, I would not conclude that all departments have equal patient demand in a real diagnostic centre.

These observations demonstrate the importance of understanding data limitations before making conclusions or recommendations.

## From Findings to Next Action

Based on my analysis, I identified the following areas that deserve further attention:

- **Pending and cancelled tests:** Investigate why 5% of tests were pending and 3% were cancelled.
- **Laboratory turnaround time:** Review the processes involved in KFT and FBC tests to understand their longer average turnaround times.
- **Payment records:** Capture actual amounts paid and outstanding balances to monitor collections accurately.
- **Department activity:** Compare department visit figures with real operational records before making staffing decisions.
- **Performance monitoring:** Regularly review patient visits, test completion, turnaround time, cancellations and payment patterns.

My overall recommendation is to strengthen operational record-keeping and establish regular performance monitoring to support better management decisions.

## Project Limitations

- The dataset is synthetic and may not reflect real-world operational patterns.
- Actual amounts collected and outstanding balances could not be calculated.
- Reasons for pending and cancelled tests were not provided.
- Additional operational information would be required to investigate the causes of turnaround time differences.

## Project Outcome

This project demonstrates how PostgreSQL, Microsoft Excel and Power BI can be used together to explore operational data, communicate findings and develop practical recommendations to support informed decision-making.
