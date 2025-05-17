
# OPERATIONAL EFFICIENCY AND REVENUE ANALYSIS: SILVERLINE MEDICAL CENTRE HEALTHCARE DATASET

## Outline

- [Introduction](#introduction)
- [Story of Data](#story-of-data)
- [Data Splitting and Preprocessing](#data-splitting-and-preprocessing)
- [Pre-Analysis](#pre-analysis)
- [In-Analysis](#in-analysis)
- [Post-Analysis and Insights](#post-analysis-and-insights)
- [Data Visualizations and Charts](#data-visualizations-and-charts)
- [Recommendations and Observations](#recommendations-and-observations)
- [Conclusion](#conclusion)



## Introduction

### Objective of the Project:
This project aimed to perform a comprehensive operational and financial analysis of patient flow, consultation delays, and revenue streams for Silverline Medical Centre, a healthcare service provider. The key objective was to derive actionable insights to enhance service efficiency, maximize resource allocation, and boost profitability.

### Problem Being Addressed:
The facility needed to understand patient volume patterns, identify bottlenecks causing consultation delays, evaluate revenue distribution across financial classes, and assess doctor efficiency. Addressing these issues is crucial for improving patient satisfaction, reducing wait times, and increasing profitability.

### Key Datasets and Methodologies:
- Datasets: Patient visitation logs, financial transactions, doctor allocation records.
- Methodologies: Data cleaning, descriptive statistics, trend analysis, and visualization using Microsoft Excel (Pivot Tables, Advanced Formulas, Time Analysis, KPI Dashboards).

## Story of Data

### Data Source:
Internal operational and financial data collected from Silverline Medical Centre’s electronic health records.

### Data Collection Process:
Data was gathered automatically from patient registration, consultation logging, and financial transaction systems.

### Data Structure:
- Rows: Individual patient visits and financial transactions.
- Columns: Patient demographics, doctor type, visit time, consultation start time, consultation wait time, financial class, revenue, and other KPIs.

### Important Features and Their Significance:
- Consultation Wait Time: Measures operational efficiency and patient service quality.
- Doctor Type: Assesses workload distribution and efficiency.
- Financial Class: Tracks revenue streams and patient affordability.
- Visit Time & Hour: Identifies peak operational hours and staffing needs.

### Data Limitations or Biases:
- Missing timestamps in some records.
- Potential outlier consultation delays not excluded in initial analysis (but reviewed during cleaning).
- Financial class categorizations may not fully capture patient socioeconomic diversity.

## Data Splitting and Preprocessing

### Data Cleaning:
- Removed duplicate records.
- Corrected inconsistencies in doctor type labels.
- Standardized time formats for accurate time-based analysis.

### Handling Missing Values:
- Missing consultation start times were flagged. Records with critical missing data were excluded from certain time-based analyses.

### Data Transformations:
- Created variables for hour of visit, day of week, and consultation delay buckets.
- Calculated derived KPIs such as average consultation wait time and doctor efficiency ratios.

### Data Splitting:
- Dependent Variables: Consultation wait time, revenue.
- Independent Variables: Doctor type, visit hour, patient financial class.

### Industry Context:
Healthcare operations analysis focusing on patient flow optimization and financial performance.

### Stakeholders:
Operations management, financial planners, healthcare administrators.

### Value to the Industry:
Insights from this project can guide healthcare facilities to optimize resource use, enhance patient satisfaction, and improve revenue forecasting.

## Pre-Analysis

### Identify Key Trends:
- Noticeable consultation delays during mid-day and early afternoon hours.
- Certain doctor types consistently handled more patients with varying efficiency levels.

### Potential Correlations:
- Peak patient volume correlated with increased consultation delays.
- Revenue peaks aligned with higher patient volumes but not necessarily with faster service times.

### Initial Insights:
Efficiency appeared to vary significantly between doctor types, suggesting possible process or staffing improvements.

## In-Analysis

### Unconfirmed Insights (Hypotheses):
- Doctors with higher patient loads might have either longer consultation delays or higher efficiency based on specialization.
- Financial class distribution may impact revenue predictability.

### Recommendations (Preliminary):
- Explore scheduling adjustments to reduce mid-day bottlenecks.
- Rebalance doctor workload where feasible.

### Analysis Techniques Used:
- Pivot Tables for slicing data by doctor type, hour, financial class.
- Advanced Formulas (VLOOKUP, IF statements) for cleaning and transforming data.
- Time Series Analysis to assess trends by hour/day.

## Post-Analysis and Insights

### Key Findings:
- Peak Consultation Hours: 10 AM to 2 PM, correlating with the highest consultation delays.
- Doctor Efficiency: Significant variation found, with some doctor types maintaining low delays despite higher patient volume.
- Revenue Streams: Insurance contributed the majority of revenue despite lower patient counts, highlighting a premium service segment.
- Wait Time Impact: Longer wait times were linked to decreased patient return rates (observed indirectly via patient volume trends).

### Comparison with Initial Findings:
While initial assumptions suggested uniform efficiency, analysis revealed distinct performance patterns by doctor type and time of day.

## Data Visualizations & Charts
![image](https://github.com/user-attachments/assets/8896f49c-3a92-4e9f-91ac-e73489300bf7)



## Recommendations and Observations

### Observations

- Silverline medical centre's  total revenue stands at $1,143,889, with Insurance contributing the largest share at $461,540 (40.3%). Corporate accounts for $255,660 (22.3%) and HMO brings in $215,925 (18.9%), showing strong reliance on third-party payers. Private payments contribute $186,225 (16.3%), while Medicare lags significantly at $24,539 (2.1%), suggesting limited reach among senior or government-assisted patients.

- Patient traffic is highest at the start of the week, peaking on Monday with 6,982 visits, followed by Tuesday (5,690). There’s a noticeable midweek drop, reaching the lowest on Thursday (2,673). The weekend shows moderate activity on Saturday (3,010) and the lowest on Sunday (2,549). This pattern suggests a front-loaded demand cycle, with nearly 42% of weekly visits occurring on just Monday and Tuesday.

-  Anchor doctors handled the vast majority of patient visits—21,913 out of 29,998 (73%), indicating they are the primary workforce. Locum doctors managed 6,789 patients (23%), while floating doctors accounted for only 1,296 visits (4%), showing minimal contribution.

- Anchor doctors contributed 17,668.22 hours of patient care, covering 73% of visits (21,913 patients), confirming their central role in operations. Locums handled 6,789 patients over 3,594.20 hours, while floating doctors managed 1,296 visits in just 650.27 hours. This distribution reinforces that anchor doctors bear the heaviest workload in both volume and time commitment.

-  Total consultation wait time over the period sums to 1,167,442 hours, with major spikes on 11/11/2019 (165,833 hrs), 04/11/2019 (139,570 hrs), and 06/11/2019 (114,743 hrs). These peaks suggest recurring system strain, possibly linked to high patient volumes, staffing shortages, or process bottlenecks. In contrast, wait times were significantly lower on 10/11/2019 (34,312 hrs) and 03/11/2019 (39,864 hrs), indicating underutilized capacity on certain days.

-  Patient volume peaks between 8:00 AM and 11:00 AM, with the highest at 9:00 AM (4,297 visits). There’s a dip during midday, followed by a secondary surge at 6:00 PM (2,600) and 7:00 PM (2,269), likely reflecting post-work visits. Activity drops sharply after 9:00 PM, indicating limited late-hour demand or availability.

-  Medicare patients have the longest average visit duration at 0.96 hours, significantly above the overall average of 0.73 hours. Corporate, HMO, and Insurance visits cluster around 0.74–0.77 hours, while Private patients have the shortest visits at 0.66 hours.

### Recommendations

-  To enhance financial performance, the hospital should deepen its collaboration with insurance and corporate partners, which together contribute over $717,000. Expanding corporate and HMO agreements could further boost revenue. Private patient intake may be increased through improved service offerings or flexible payment options. Lastly, Medicare services should be assessed and potentially expanded to tap into an underserved segment and diversify revenue streams.

-  To balance operational load and improve efficiency, staffing and resource allocation should be reinforced early in the week to match peak demand. Midweek and weekend strategies can focus on attracting more patients—through targeted promotions, extended clinic hours, or elective services—to better utilize capacity during slower days. This could ease Monday bottlenecks and improve overall patient flow throughout the week.

-  Silverline's heavy reliance on anchor doctors suggests stability but also a potential risk of over-dependence. To ensure continuity of care and reduce burnout, there should be strategic use of locum and floating staff, particularly during peak days. Upskilling or increasing the availability of floating doctors could also boost flexibility and enhance coverage during gaps or emergencies.

-  To ensure sustainable operations, the hospital should monitor anchor doctor workload for signs of fatigue or inefficiency. Locums and floating doctors should be strategically deployed to relieve pressure on anchor staff, especially during peak periods. Evaluating visit duration per doctor type may also reveal opportunities for efficiency gains through training, process improvements, or better scheduling.

-  The hospital should investigate the root causes behind high-wait-time days, particularly around early and mid-November, and align staffing or resources accordingly. Implementing queue management systems, streamlining triage, or extending consultation hours during peak demand periods could significantly reduce wait times. Additionally, redistributing appointments across lower-demand days can help balance the load and improve patient experience.

-  To optimize patient flow and reduce congestion, morning hours—especially between 8:00 AM and 11:00 AM—should be prioritized for high staffing and operational readiness. Consider extending evening services slightly to accommodate the after-work rush. Midday and late evening shifts could be used to manage overflow or cater to specific appointment types, ensuring balanced resource use throughout the day.

-  The longer duration for Medicare visits may reflect complex cases or administrative delays and warrants further analysis to improve efficiency. Private patient visits, being the shortest, may present an opportunity to enhance service depth or upsell additional care. Standardizing care pathways and introducing time management protocols across payer types can help balance visit durations and improve throughput without compromising care quality.

### Actionable Insights:

-  The hospital depends too much on insurance and company-paid visits. If more older people using Medicare are invited in, the hospital can make money from more places and not be badly affected if one group slows down.
  
-  Most people come on Mondays and Tuesdays, which makes those days really busy and others slow. Encouraging people to book midweek can help reduce stress on staff and make better use of the hospital all week.

-  A small group of doctors are doing most of the work. If any of them can’t show up, things could fall apart. Training and involving more of the other doctors can help share the load and keep things running smoothly.

-  Most people visit the hospital early in the morning or after work. Having doctors available at those times can help serve them better and keep things moving.
  
-  Older patients with Medicare usually need more time during visits. Creating a special process for them could help save time and give them better care.


### Optimizations or Business Decisions:

Adopt flexible staffing models, evaluate patient flow processes, and consider dynamic scheduling.

### Unexpected Outcomes:

Some doctors demonstrated high efficiency under heavy loads, suggesting opportunities for knowledge sharing or procedural standardization.

## Conclusion

### Key Learnings:
Operational efficiency varies significantly by doctor type and time of day. Revenue concentration in premium service segments presents strategic growth opportunities.

###  Limitations:
Data gaps in some time records and potential sample bias in financial class reporting.

### Future Research:
A deeper dive into patient satisfaction metrics and exploring machine learning for predictive scheduling could enhance future analyses.






