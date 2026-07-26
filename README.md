# Hospital-Emergency-Room-Dashboard
Interactive Power BI dashboard analyzing Emergency Room performance, patient demographics, and operational efficiency.

## Project Overview 

The Hospital Emergency Room Dashboard is an interactive Power BI report developed to analyze Emergency Room (ER) patient data. The dashboard provides valuable insights into patient demographics, hospital operations, and patient experience through interactive visualizations and key performance indicators (KPIs). It is designed to support data-driven decision-making and identify opportunities to improve Emergency Room efficiency.

## Business Objectives

This dashboard was developed to answer the following business questions:
- How many patients visited the Emergency Room?
- What percentage of patients were admitted?
- How has patient volume changed over time?
- Which departments receive the highest number of referrals?
- What are the demographic characteristics of ER patients?
- Which age groups are more likely to be admitted?
- Which departments experience the longest waiting times?
- Does waiting time influence patient satisfaction?

# Dashboard Pages

## Page 1 – Overview

Provides a high-level summary of Emergency Room performance.

### Key Performance Indicators (KPIs)

- Total Patients
- Admission Rate
- Average Waiting Time
- Average Satisfaction Score

### Filters (Slicers)

The dashboard includes interactive slicers that allow users to filter all visuals dynamically. The available slicers are:

- Year
- Department Referral
- Admission Status
  
### Visuals

- Patient Visits Trend
- Admission Status
- Patients by Department Referral

## Page 2 – Patient Demographics

Provides insights into the characteristics of Emergency Room patients.

### Visuals

- Patients by Gender
- Patients by Race
- Patients by Age Group & Admission Status

## Page 3 – Operations & Patient Experience

Evaluates operational efficiency and patient experience.

### Filters (Slicers)

The available slicers are:

- Year
- Department Referral

### Visuals

- Average Waiting Time by Department
- Satisfaction by Waiting Time Group
- Average Satisfaction by Department
- Satisfaction Score Distribution

# Key Metrics

- *Total Patients:* 9,216
- *Admission Rate:* 50.04%
- *Average Waiting Time:* 35.3 minutes
- *Average Satisfaction Score:* 4.99 / 10*

*Average satisfaction score was calculated using records with available satisfaction scores only.

# Key Insights

- The Emergency Room recorded *9,216 patient visits*, indicating substantial patient demand during the reporting period.
- Approximately *50% of patients were admitted*, while the remaining patients were discharged after assessment or treatment.
- Patient visits fluctuated across different months, reflecting changes in Emergency Room demand over time.
- Department referral patterns identified departments with higher patient volumes, providing insight into referral trends across the hospital.
- Demographic analysis highlighted differences in patient distribution across age groups, gender, and race.
- The average patient waiting time was *35.3 minutes*, providing a useful indicator of operational efficiency.
- Patient satisfaction analysis was performed using only records with completed satisfaction scores because some records contained missing feedback.
- Comparing waiting time groups with satisfaction scores helps assess the relationship between service delays and patient experience.

# Data Preparation

The dataset was cleaned and transformed in Power Query before analysis.

The following steps were performed:

- Checked for missing values.
- Retained missing Satisfaction Score records and excluded them only from satisfaction-related calculations.
- Created Age Group categories for demographic analysis.
- Created Waiting Time Groups for operational analysis.
- Developed DAX measures for KPI calculations.
- Applied data formatting and optimized the data model for reporting.

# Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

# Dataset

The dataset contains *9,216 Emergency Room patient records* and includes the following fields:

- Patient ID
- Admission Date
- Age
- Gender
- Race
- Department Referral
- Admission Status
- Waiting Time
- Satisfaction Score
- Case Management Indicator

# Data Quality Note

Some patient records contained missing *Satisfaction Scores*. These records were retained to preserve patient counts and operational analyses. Satisfaction-related calculations were performed only on records with available satisfaction scores.


# Dashboard Preview

## Overview

![image alt](https://github.com/osakweprecious-5/Hospital-Emergency-Room-Dashboard/blob/9c60d78e64efaebae56e4518edc925d370ef7a03/Overview.png)

## Patient Demographics

![image](

## Operations & Patient Experience

[Operations & Experience Dashboard](https://github.com/osakweprecious-5/Hospital-Emergency-Room-Dashboard/blob/main/Operations%20%26%20Experience.png)

# Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- KPI Development
- Dashboard Design
- Data Visualization
- Business Intelligence
- Data Storytelling

# Author

*Precious Osakwe*

Data Analyst | Power BI | Excel | SQL

## Contact

If you have any questions or feedback about this project, feel free to connect with me on GitHub or LinkedIn.
