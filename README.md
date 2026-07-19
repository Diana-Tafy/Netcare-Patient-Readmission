# Patient Readmission & Clinical Segmentation Dashboard

Dashboard:    https://stats-chums.lovable.app

## Project Overview
This project focuses on analyzing hospital patient data to segment demographics, analyze lengths of stay, and evaluate clinical risk factors (Blood Pressure and Blood Sugar levels). The goal is to provide healthcare administrators with actionable insights into patient resource allocation.

## Interactive Dashboard
👉 https://datastudio.google.com/embed/reporting/7572cfc1-970e-4351-b341-af4a526b4122/page/bdg2F

### Dashboard Preview
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3d8c2b4b-c9e8-4b9b-8b81-b87ce2058483" />


## Key Insights & Features
* **Patient Segmentation:** Developed custom SQL `CASE` logic to categorize patients into meaningful clinical and demographic brackets (e.g., Age Groups, Length of Stay brackets, and Health Risk Levels).
* **Resource Optimization:** Highlighted total length of stay metrics across age populations to pinpoint high-utilization groups.
* **Data Integrity:** Cleansed and transformed underlying data fields using SQL to ensure accurate metrics without truncated axis values.

## Tech Stack Used
* **Data Transformation:** SQL
* **Data Visualization:** Google Looker Studio
* **Data Source:** Netcare Hospital Patient Readmission Dataset

📊 1. Core Analytics Insights 
Based on the hospital performance data, here are the key findings from the patient metrics:

👥 Demographic Distribution & Resource Load
Senior Dominance: Seniors make up the vast majority of the patient database at 46.4%, followed by "Old Folks" at 28.3%, and "Young Adults" at 25.3%.

Gender Balance: Across all age groups, the split between Male and Female patients remains remarkably balanced. Seniors reflect the highest total patient counts, with 3,497 Males and 3,329 Females.

🏥 Hospital Stay & Readmission Trends
Uniformly High Length of Stay: The overall average hospital stay is a massive 15.23 days. Alarmingly, this high duration remains completely flat across all age brackets:

Seniors: 15.26 days (with 1,390 readmissions)

Old Folks: 15.15 days (with 853 readmissions)

Young Adults: 15.25 days (with 757 readmissions)

The Insight: Because young adults are staying just as long as senior citizens, the long length of stay is likely driven by general clinical protocol or complex diagnosis severities rather than age-related frailty alone.

🩺 Clinical Risk & Diagnosis Complexity
High Complexity in Older Populations: The Diagnoses Complexity by Age Group chart reveals that Seniors significantly outnumber other demographics in the "High" complexity category (~600 patients).

Blood Pressure Breakdown: The massive bulk of the patient population falls into the Low Blood Pressure Group (2,064 patients), while Medium (472) and High (464) present smaller, targeted risk segments.

Elevated Blood Sugar: The average blood sugar level sits at 133.54, which borders on pre-diabetic/diabetic levels globally, marking a key area for clinical focus.

💡 2. Actionable Recommendations 
Targeted Chronic Care Paths: Since Seniors represent nearly half of all patients and dominate high-complexity diagnoses, the hospital should introduce a dedicated Senior Managed Care Track focusing on metabolic health (targeting that high 133.54 average blood sugar).

Investigate Young Adult Discharge Bottlenecks: Because Young Adults have an average stay of 15.25 days—virtually identical to Seniors—the clinical operations team should review why lower-risk, younger demographics are not being discharged sooner.

Readmission Intervention Programs: With 1,390 Senior readmissions, implementing a Post-Discharge Follow-up Protocol (telehealth checks within 48 hours of leaving the facility) could significantly deflate these recurring admission numbers.
