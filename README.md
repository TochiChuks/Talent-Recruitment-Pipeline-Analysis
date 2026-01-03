# Talent-Recruitment-Pipeline-Analysis

## Recruitment Performance Analysis: Axiom Recruitment Funnel

## Executive Summary
This analysis reviews recruitment performance over the previous two months using Axiom’s seven-step recruitment funnel. The objective was to assess recruiter effectiveness using leadership-defined KPIs: Phone Screens, Waitlist Adds, and Conversion Rate, while accounting for contextual factors such as candidate seniority (PQE) and practice area.
Overall results show that recruiter performance varies significantly depending on candidate complexity and practice specialization. High conversion rates are frequently associated with junior PQE candidates and high-demand practice areas, while recruiters handling senior candidates and regulated practices demonstrate lower but more operationally sustainable conversion rates. As a result, recruiter performance is best assessed through a balanced lens of activity volume, conversion efficiency, and candidate complexity.

<img width="940" height="399" alt="image" src="https://github.com/user-attachments/assets/acd31a3f-d131-411e-a4a7-af860f600d2b" />

Fig 1. Recruitment Performers Analysis Dashboard 

- Total Phone Screens
- Total Waitlist Adds
- Overall Conversion Rate
________________________________________
## Objectives & Scope
The objectives of this analysis were to:
- Review recruitment performance over the last two months
- Measure outcomes using leadership KPIs
- Compare results globally, regionally, and by recruiter
- Interpret recruiter performance with respect to PQE and practice area
- Identify limitations and provide actionable recommendations
The scope of the analysis focuses on recruiter activity and funnel outcomes rather than individual candidate quality or hiring outcomes beyond the waitlist stage.
________________________________________
## Recruitment Funnel Overview
Axiom’s recruitment process follows a structured seven-stage funnel:
1.	Application Review
2.	Phone Screen
3.	Interview #1
4.	Final Interview
5.	Next Steps
6.	Diligence
7.	Waitlist
Each stage represents a narrowing of candidates as screening rigor increases. Leadership emphasis is placed on Phone Screens (activity), Waitlist Adds (output), and Conversion Rate (efficiency).

________________________________________
## Data Sources & Preparation
Three datasets were used:
-	Recruitment pipeline data (candidate stage progression)
-	Candidate data (Talent ID, Recruiter, PQE, Practice Area)
-	Recruiter roster data (Recruiter to Region mapping)
  
Data Preparation Steps
-	Stage names were standardized into the seven official funnel stages
-	Talent IDs were normalized to resolve data-type mismatches
-	Pipeline data was joined to candidate and recruiter datasets
-	Distinct counts were used to avoid double-counting candidates

<img width="940" height="377" alt="image" src="https://github.com/user-attachments/assets/885d40fd-15e9-49a8-8101-d7bc4b00166a" /> 

Fig 2. Cleaned and processed data set

________________________________________
## KPI Definitions & Methodology
Phone Screens
Count of candidates who reached the Phone Screen stage.
Waitlist Adds
Count of candidates who reached the Waitlist stage.
Conversion Rate
Conversion Rate = Waitlist Adds ÷ Phone Screens

To reduce statistical distortion:
-	Recruiters with very low phone screen volumes were not treated as top performers
-	Conversion rates were interpreted alongside activity volume and candidate complexity

<img width="940" height="351" alt="image" src="https://github.com/user-attachments/assets/0dbf99ce-d878-4497-9af5-4536f43f1199" />

Fig 3. Pivot table showing Global and Regional Count for both Phone Screen and Waitlist

<img width="695" height="510" alt="image" src="https://github.com/user-attachments/assets/e1896f71-a0c7-47a2-b4de-16e82906d837" />

Fig 4. Pivot table showing a Distinct Count of candidates reviewed by relevant recruiters on both Phone Screen and Waitlist funnel stages.

________________________________________
## Results & Key Findings

<img width="940" height="384" alt="image" src="https://github.com/user-attachments/assets/fc960b62-8625-4410-bcae-6bb03039897c" />

Fig 5. A table showing the relevant recruiters on both Phone Screen and Waitlist funnel stages, their conversion rate, PQE and their practice areas

## Overview of Recruiter Performance
The analysis evaluated recruiter performance across three core KPIs defined by leadership: Phone Screens (volume), Waitlist Adds (output), and Conversion Rate (efficiency). Performance was assessed over the two-month period using cleaned and standardised funnel stages, with additional contextual consideration given to PQE and Practice Area, as these materially influence funnel progression.
The results indicate that recruiter performance varies significantly depending on whether success is measured by scale, efficiency, or balance across metrics. As a result, no single recruiter can be definitively identified as “best” without introducing contextual bias.
________________________________________
## Phone Screen Volume (Workload Contribution)
High phone screen volume indicates recruiters carrying the greatest operational workload and contributing most significantly to top-of-funnel activity.
-	Recruiter1 (133 Phone Screens) and Recruiter2 (132 Phone Screens) recorded the highest volumes.
-	These recruiters also generated the highest absolute number of waitlist additions (44 and 41 respectively).
-	Both recruiters primarily worked with senior PQE candidates (18–35+ years) and specialised practice areas, which typically experience longer and more selective funnel progression.
  
Interpretation:
High volume recruiters play a critical role in sustaining pipeline throughput, even when conversion rates are lower. Lower efficiency in this context does not indicate underperformance but rather reflects the complexity of candidate profiles being handled.
________________________________________
## Waitlist Adds (Output Performance)
Waitlist additions represent the most meaningful downstream outcome of the recruitment funnel.
•	Recruiter1 (44), Recruiter2 (41), Recruiter10 (40), and Recruiter21 (38) were the strongest contributors in absolute waitlist output.
•	Recruiter21 achieved this with significantly fewer phone screens than the top-volume recruiters, indicating stronger funnel efficiency.
Interpretation:
Absolute output remains an essential metric for business impact; however, it must be interpreted alongside volume to avoid overstating efficiency in lower-scale scenarios.
________________________________________
## Conversion Rate (Efficiency)
Conversion rate highlights how effectively recruiters move candidates from Phone Screen to Waitlist.
-	The highest conversion rates were observed for:
-	Recruiter9 (103%)
-	Recruiter28 (88%)
-	Recruiter21 (86%)
-	Recruiters with conversion rates exceeding 100% likely reflect:
-	Candidates entering the funnel at later stages
-	Cross-period timing effects
-	Data aggregation artefacts rather than true overperformance


Notably, the highest conversion rates were concentrated among recruiters handling:
-	Low PQE candidates (1–4 years)
-	High-demand practice areas (e.g., Commercial & Contract Law, Data Privacy)
Interpretation:
While conversion rate is a valuable efficiency metric, it becomes statistically unstable at lower volumes and must not be used in isolation to determine overall performance.
________________________________________
## Best Overall Performance (Balanced Assessment)
When balancing volume, output, and efficiency, Recruiter21 emerges as the strongest all-round performer.
-	44 Phone Screens
-	38 Waitlist Adds
-	86% Conversion Rate
-	PQE: 4 years
-	Practice Area: Commercial & Contract Law
Recruiter21 demonstrates strong throughput while maintaining high efficiency without reliance on anomalous conversion effects, making their performance both scalable and reliable.
________________________________________
## Limitations
-	Stage sequencing inconsistencies affected conversion accuracy
-	The dataset does not distinguish between recruiter-initiated and system-driven stage changes
-	Simplified dummy data limits real-world generalization
________________________________________
## Recommendations
1.	Introduce stage-sequencing validation rules
2.	Evaluate recruiters using volume-adjusted conversion metrics
3.	Monitor extreme conversion values as process indicators
4.	Contextualize recruiter KPIs by candidate complexity where appropriate
________________________________________
## Conclusion
This analysis provides leadership with a nuanced view of recruitment performance, balancing efficiency metrics with operational complexity. By incorporating PQE and practice area context, recruiter performance is interpreted more accurately, enabling better decision-making and fairer evaluation.


