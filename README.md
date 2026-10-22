<img width="356" height="62" alt="image" src="https://github.com/user-attachments/assets/e5ae1167-f396-4ea3-9fae-9354c501a1a5" />### PROJECT OVERVEIW
The Hospital Emergency Dashboard analyzes emergency department data to monitor patient admissions, waiting times, treatment outcomes, and operational efficiency. It provides actionable insights through interactive visualizations to support data-driven decision-making and improve healthcare service delivery.

## Business Requirement
To improve operational efficiency and enhance visibility into emergency room performance, a Hospital Emergency Room Analysis Dashboard will be developed using Power BI. The dashboard will enable stakeholders to monitor key performance indicators, analyze patient trends, identify operational bottlenecks, and make data-driven decisions to improve patient management and healthcare service delivery.

## PROBLEM STATEMENT
## (Key Performance Indicators)

**Total Patients:** Number of patients who visited the ER.

**Average Wait Time:** Average time patients waited before being seen.

**Patient Satisfaction Score:** Overall patient rating of their experience.

**Patients Referred:** Number of patients referred to other departments.

## charts Requirement

## Dashboard 1: Monthly View 

**Objective:** Monitor key metrics and trends on a month-by-month basis to identify patterns and areas for improvement.
Charts to Develop:
**Patient Admission Status:** Track admitted vs. non-admitted patients.

**Patient Age Distribution:** Group patients by 10-year age intervals.

**Department Referrals:** Analyze referral trends across different departments.

**Timeliness:** Measure the percentage of patients seen within 30 minutes.

**Gender Analysis:** Visualize patient distribution by gender.

**Racial Demographics:** Analyze patient data by race.

**Time Analysis:** Assess patient volume by day and hour.

## Dashboard 2: Consolidated View 

**Objective:** Provide a holistic summary of hospital performance for a selected date range.

**Charts to Develop:**
Similar metrics as the Monthly View, but aggregated over a customizable date range for broader insights and trend analysis

### Dashboard 3: Patient Details

**Objective:** Offer granular insights into patient-level data to enable detailed analysis and troubleshooting.

Charts to Develop: A grid displaying essential fields:

Patient ID

Patient Full Name

Gender

Age

Admission Date

Patient Race

Wait Time

Department Referral

Admission Status

Dashboard Preview




<img width="818" height="509" alt="hospital_ER_1" src="https://github.com/user-attachments/assets/46fe79f2-0810-48f8-b8ab-865e85f4fa21" />






<img width="687" height="494" alt="hospital_ER_2" src="https://github.com/user-attachments/assets/654c883f-2ffe-4413-8f1b-eb541b2500c4" />




<img width="691" height="506" alt="hospital_ER_3" src="https://github.com/user-attachments/assets/bf67b960-ced1-4791-806c-7727c6d47273" />



## Analytical Highlights

**High Patient Volume:** Served 9,216 patients overall.

**Efficient Wait Times:** Averaged only 35.3 minutes wait.

**Excellent Satisfaction:** Scored 4.99 patient satisfaction.

**Strong Referrals:** Referred 3,816 patients successfully.

## Below is an in-depth analysis of each visual component:

## 1. High-level Key Performance Indicators (KPIs)

## Monthly View (Feb 2024):

Total Patients (no_of_patience): 431

Average Wait Time (avg_wait_time): 36.7 min

Patient Satisfaction Score (patience_satisfaction_score): 4.72

Patients Referred (no_of_patience_referred): 179

## Consolidated View (Apr 2023 – Oct 2024):
Total Patients: 9,216

Average Wait Time: 35.3 min

Patient Satisfaction Score: 4.99

Patients Referred: 3,816

**Insight:** The department handled a high volume of patients with consistently controlled wait times (around 35–37 minutes). Satisfaction remained excellent (close to 5.0), and a substantial portion of patients (about 41% overall) were referred to other departments, showing strong care coordination.

## 2. Patients Admission Status

**It shows:** Percentage and count of patients who were admitted versus not admitted.

**Monthly:** 51.97% admitted (224), 48.03% not admitted (207)

**Consolidated:** 50.04% admitted (4,612), 49.96% not admitted (4,604)

**Insight:** Admission rates are almost perfectly balanced at ~50%. This indicates stable clinical decision-making and consistent triage practices across both the single month and the full period.

## 3. % of Patients Seen Within 30 Minutes (Donut Chart)

**It shows:** Proportion of patients who met the 30-minute wait-time target versus those who did not.

**Monthly:** 65.66% within target (283), 34.34% outside (148)

**Consolidated:** 59.3% within target (~5.5K), 40.68% outside (~4K)

**Insight:** Performance is solid, with nearly 6 out of 10 patients seen within the target overall, improving to almost two-thirds in February. This highlights effective peak-hour management while still leaving room to further reduce the 35–40% who wait longer.

## 4. No of Patients by Day (Bar Chart)

**It shows:** Daily patient volume from Monday to Sunday.

**Insight:** Volume is relatively stable across the week with no extreme day-of-week spikes. This supports predictable staffing levels rather than heavy weekend or mid-week surges.

## 5. No of Patients by Age Group (Bar Chart)

**It shows:** Distribution of patients across age bands.

**Insight:** The highest volumes fall in the working-age groups (especially 20–49 years). Pediatric and elderly groups are lower, which can help prioritize resource allocation for the dominant adult working population.

 ## 6. No of Patients by Gender (Donut Chart)
 
**It shows:** Gender breakdown (Male, Female, Not Confirmed).

**Monthly:** ~54% Female, ~45% Male

**Consolidated:** ~51% Female, ~49% Male

**Insight:** Gender distribution is nearly equal, with a slight female majority. This suggests balanced demand and no strong gender skew in emergency visits.

## 7. No of Patients by Hours (Table)
   
**It shows:** Hourly patient counts broken down by day of the week.

**Insight:** Clear morning-to-early-afternoon peaks (especially 07:00–12:00) appear consistently. Night and late-evening hours are quieter. This pattern is useful for optimizing shift staffing and reducing wait times during high-demand windows.

## 8. No of Patients by Departmental Referral (Bar Chart)

**It shows:** Number of referrals by specialty (None/General Practice leading, followed by Orthopedics, Physiotherapy, etc.).

**Insight:** The majority of referrals go to “None” / General Practice, with Orthopedics and Physiotherapy as the next largest. This reveals the main downstream pathways and can guide capacity planning in those departments.

## 9. No of Patients by Patient Race (Bar Chart)

**It shows:** Patient volume by racial category.

**Insight:** White patients form the largest group, followed by African American and Two or More Races. The distribution provides useful demographic context for equity monitoring and culturally appropriate care planning.

## Overall Insight

The Emergency Room demonstrates solid performance, managing high patient volumes (9,216 overall) with controlled average wait times of 35–37 minutes and excellent satisfaction scores of 4.72–4.99. Admission rates remain balanced at approximately 50%, while nearly 60% of patients are seen within the 30-minute target. Demand follows predictable morning peaks among working-age adults, supported by strong referral activity to key specialties.

## Overall Recommendations

**Match staffing to demand peaks** – Concentrate senior clinicians and rapid-assessment resources between 07:00–12:00, the consistently busiest window. This is the single most effective lever to reduce wait times and overtime costs.

**Expand fast-track pathways** – Create dedicated low-acuity streams to raise the percentage of patients seen within 30 minutes from the current ~60% toward 75%+.

**Strengthen top referral pathways** – Establish formal liaison roles and capacity agreements with General Practice, Orthopedics, and Physiotherapy to speed transfers and reduce ER boarding.

**Set real-time KPI alerts** – Trigger automatic notifications when average wait time exceeds 40 minutes or satisfaction drops below 4.7, enabling rapid operational response.

**Use demographic data for equity and planning** – Continuously monitor wait times, admissions, and satisfaction by age, gender, and race to close any emerging care gaps and align resources with the dominant working-age patient population

## TOOL USED

•	Power BI Desktop

•	Power Query

•	DAX(Data Analysis Expression

•	Microsoft Excel(for raw data preparation)

## Technique Applied

•	Data Cleaning and Transformation(Power Query)

•	DAX Calculation(eg, Number of Patients, Average Wait Time, Patient Satisfaction Score, Patient Satisfaction Score)

•	Interactive filtering(slicers)

•	Dynamic Visualization(column,bar,donut)

•	Dashboard Design













