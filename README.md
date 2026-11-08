# DATA-DRIVEN ANALYSIS OF SECURE HEALTH GENERAL HOSPITAL 2024 - 2025
## **INTRODUCTION.**
![](image_3e550caa.jpg) 

In this project, I analysed Hospital Patient records in the Microsoft Excel and built an interactive dashboard to help management review service demand, billing, payment status and insurance coverage. The analysis covers 1,000 recorded patient visits in 2024 and 2025.

## ABOUT DATASET

### Fields and Analysis Method.

The original fields are patient ID, patient name, age, gender and admission date, discharge date, department, diagnosis, total bill amount, insurance coverage and payment status. Patient id identifies a visit or record. The number of records should therefore be interpreted as patient visits rather than a count of different people.
The workbook uses excel formulas, pivot tables, pivot charts and slicers. Length of stay is the number of days between admission and discharge. Departmental length of stay and insurance coverage are arithmetic averages across visit totals are calculated by counting Patient ID. Admission dates are grouped by Year, Quarter and month for the trend charts.
The age groups are under 18, 18 to 35, 36 to 50, 51 to 65, 66 and above. Estimated insured amounts are calculated from the bill and the insurance coverage percentage. These estimates describe coverage and do not establish that an insurer has transferred the money.

### Payment Calculation and Interpretation

For the dashboard calculation, the full bill is counted as paid when Payment status is Paid. Pending and Partially Paid records are assigned zero in the amount paid calculation because actual payment amounts are not available. Subtracting this calculated amount from total billed gives the full value of bills that are not fully paid.
Accordingly, the dashboard figure labelled Outstanding Balance includes the full bill value of partially paid records. It overstates the actual unpaid amount by any partial receipts already received. The figure labelled Total Bill Paid represents the value of fully paid bills. The dataset cannot establish the hospital bank balance. Payment status percentages in the doughnut chart represent shares of billed money.

## PROBLEM STATEMENT.

Management needs a consolidated view of hospital activity, billing and insurance coverage. Without a single report, it’s difficult to compare department workloads, monitor payment categories and identify changes in admissions and billing over time.
### The project addresses the following management questions:
1. How many patient visits has the hospital recorded?
2. Which departments receive the highest number of patients?
3. Which departments generate the highest total bills?
4. What is the average length of stay for patients across different departments?
5. What proportion of patient bills has been paid, remains pending, or has been partially paid?
6. How much has the hospital billed, and how much remains outstanding?
7. How does insurance coverage vary across departments and diagnoses?
8. Which age groups account for the highest number of patient visits?
9. How do admissions and billing amounts change over time?
10. Which areas may require management attention based on the analysis?

## VISUALISATION

![](Screenshot5.png)

The dashboard brings the main activity and financial measures together on one worksheet. The image below shows the final layout with full dataset selected.
Using the dashboard
Use the Year, Department, Payment Status and Diagnosis slicers to focus the connected reports on a selected group of visits. Clear the slicer filters to return to the overall view. A diagnosis selection supports a closer review of the visit count, billing and average insurance coverage for a particular condition.
The headline figures are rounded for display. The tables in this report provide the more precise supporting values.
INSIGHTS
The dataset contains 1,000 visits with 4.8 average day of stay, record of more Females than Males and decline in recorded admission from 2024 to 2025 as well as Total Bill amounting to $ 8,053,143.44 Million. The average insurance coverage was 74.86% displayed as 75%.
