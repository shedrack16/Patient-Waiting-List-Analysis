# Patient Waiting List Analysis (Interactive Dashboard creation using Power BI)

## Project Objective
The project analyzes Ireland's national patient waiting lists from 2018 to 2021, covering Inpatient/Day Case and Outpatient services. The goal is to help healthcare planners understand how waiting list volumes are trending, which specialties carry the heaviest burden, and how wait times vary across age groups, so that resources can be targeted more effectively.

## Dataset used
- [Mapping_Specialty.csv](https://github.com/shedrack16/Patient-Waiting-List-Analysis) - maps individual specialties to broader specialty groups
- [Inpatient/Day Case Waiting List (IN_WL) 2018-2021](https://github.com/shedrack16/Patient-Waiting-List-Analysis)
- [Outpatient Waiting List (Op_WL) 2018-2021](https://github.com/shedrack16/Patient-Waiting-List-Analysis)

## Questions (KPIs)
- What is the total wait list size, and how does it compare to the same period last year?
- Which specialty groups carry the largest share of the wait list?
- What is the average and median wait time by specialty?
- How does the wait list break down by case type - Outpatient, Day Case, and Inpatient?
- How does wait list volume vary by age profile (0-15, 16-64, 65+)?
- How has the wait list trended month-on-month from 2018 to 2021?
- What proportion of patients fall into each wait-time band (0-3 months through 18+ months)?
- Dashboard Interaction [View Dashboard](https://github.com/shedrack16/Patient-Waiting-List-Analysis)

## Process
- Verified data for any missing values and anomalies across the yearly Inpatient/Day Case and Outpatient files, and sorted out the same.
- Made sure data was consistent and clean with respect to data type, date format, and values used.
- Mapped individual specialties to broader specialty groups using the mapping table to enable higher-level analysis.
- Combined the yearly Inpatient/Day Case and Outpatient waiting list files into a single unified model.
- Built average and median wait-time measures by specialty, case type, and age profile.
- Designed a Summary page, a Detail view page, and a Drill-down page, linked with slicers for Archive Date, Case Type, Specialty, Age Profile, and Time Bands to make the report dynamic.

## Dashboard
![Patient Waiting List Summary](https://github.com/shedrack16/Patient-Waiting-List-Analysis)
![Patient Waiting List Detail View](https://github.com/shedrack16/Patient-Waiting-List-Analysis)
![Patient Waiting List Drill Down](https://github.com/shedrack16/Patient-Waiting-List-Analysis)

## Project Insight
- The overall wait list reached 709K in the latest month, up from 640K in the same month the previous year, an increase of roughly 11%.
- Outpatient cases make up the large majority of the wait list (around 74%), with Inpatient and Day Case cases making up the remainder.
- The Outpatient wait list has grown steadily and consistently, rising from about 0.50M in mid-2018 to 0.63M by early 2021, while Day Case and Inpatient volumes have stayed comparatively flat over the same period.
- Paediatric Orthopaedic has by far the longest median wait time at around 140 days, followed by Paediatric Urology (105 days), Otolaryngology/ENT (82 days), Orthopaedics (81 days), and Paediatric Dermatology (77 days).
- General, Bones (Orthopaedics), and Urine (Urology) are the specialty groups with the largest total wait list volumes.
- The majority of patients across all age groups fall within the shorter 0-3 month waiting band, though a meaningful share still falls into longer bands, particularly for the 16-64 age group.

## Final Conclusion:
To reduce the strain on the health system, capacity should be prioritized in the specialty groups carrying the largest wait list volumes, such as General, Orthopaedics, and Urology. Given the steady month-on-month growth in Outpatient waiting lists specifically, targeted investment in Outpatient clinic capacity is likely to have the greatest impact on bringing overall wait times down, particularly for paediatric specialties where median wait times are highest.