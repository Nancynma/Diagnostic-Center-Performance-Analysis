 *Diagnostic Centre Operational Performance Analysis.

*Project Overview:
This project examines the operational performance of a diagnostic centre using data analysis. It focuses on patient visits, laboratory test turnaround time, test charges and payment patterns.
The aim is to understand what the data reveals about the centre's operations, identify areas that may require attention and provide practical recommendations to support better decision-making.

*Project Objective:

To analyse diagnostic centre operations, assess laboratory turnaround time, examine test charges and payment patterns, and identify opportunities for operational improvement.

*Tools Used:
PostgreSQL (Neon): Data exploration, querying, data cleaning checks and analysis.
Microsoft Excel: KPI reporting, data summaries and visualisation.
Microsoft Power BI: Interactive dashboards and performance reporting.

*Dataset Overview:

The project uses a synthetic dataset containing four related tables:

| Table | Records |
|---|---:|
| Patients | 1,000 |
| Visits | 1,500 |
| Laboratory Tests | 2,000 |
| Payments | 2,000 |

Note: The dataset is simulated for learning and portfolio demonstration. It does not represent actual patient records or the operations of a real diagnostic centre.

*Key Findings:

- A total of 1,000 patients and 1,500 visits were recorded.
- Laboratory tests had a 92% completion rate, 5% pending rate and 3% cancellation rate.
- KFT and FBC recorded the highest average turnaround time at 13.10 hours each.
- Total recorded test charges amounted to ₦22 million.
- Payment records showed 60% paid, 20% partially paid and 20% unpaid.
- Each of the five departments recorded 300 visits.

*How I Think as an Analyst:

The analysis also considered the limitations of the available data. For example, payment status alone cannot establish the actual amount collected or outstanding. Similarly, equal visit counts across departments should not be interpreted as proof of equal demand in real diagnostic centres because the dataset is synthetic.

*Recommendations:

Based on the findings, the project recommends:

1. Investigating reasons for pending and cancelled laboratory tests.
2. Reviewing workflows for tests with longer turnaround times.
3. Improving payment records to capture actual amounts paid and outstanding balances.
4. Validating department activity using real operational records.
5. Establishing regular monitoring of operational performance indicators.

*Project Limitations:

- The dataset is synthetic and may not reflect real-world operational patterns.
- Actual amounts collected and outstanding balances could not be calculated.
- The reasons behind pending and cancelled tests were not provided.
- Further operational information would be needed to investigate the causes of turnaround time differences.

 *Project Outcome:

This project demonstrates how SQL, Excel and Power BI can be used together to explore operational data, communicate findings and develop recommendations that support informed decision-making.
