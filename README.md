How Has KS2 Attainment Recovered Since the Covid-19 Pandemic?



Project Overview



This Power BI dashboard analyses Key Stage 2 (KS2) attainment data published by the Department for Education (DfE) to investigate the impact of the Covid-19 pandemic on pupil attainment and subsequent recovery trends.

The dashboard explores attainment at national, subject and regional levels, allowing users to understand how performance changed following pandemic-related disruption and how recovery patterns have varied across England.



Objectives



The project was designed to answer three key questions:

1. How did Covid-19 affect KS2 attainment nationally?

A national overview page was developed to examine trends in Reading, Writing, Mathematics and Combined attainment over time.

2. Did different subjects recover at the same rate?

A subject analysis page allows users to compare recovery trends across Reading, Writing, Mathematics and Combined attainment, using both Expected Standard and Higher Standard measures.

3. How does regional recovery compare with national performance?

A regional analysis page enables comparison between a selected region and the national average, highlighting geographical variation in performance and recovery.



Data Source



Department for Education (DfE)

Dataset used:https://explore-education-statistics.service.gov.uk/find-statistics/key-stage-2-attainment/2025-26-provisional/explore



KS2 Regional and Local Authority Attainment Data



The dataset contains attainment information for:

England
Regions
Local Authorities

across multiple academic years.



Data Preparation



Data was imported into Power BI and transformed using Power Query.



Key transformation steps included:

Filtering final published results
Removing unnecessary columns
Renaming fields for readability
Creating Academic Year labels
Excluding years where statutory assessments were not conducted
Creating custom fields to improve dashboard usability


Data Validation



Before dashboard development, attainment figures were validated against published DfE statistics.

National Combined Reading, Writing and Mathematics attainment values were compared against official publications to verify the integrity of imported data.

During validation, minor discrepancies were identified between different DfE publications. Investigation confirmed that these differences existed within the source datasets themselves and were not caused by Power BI transformations or calculations.

The imported dataset was therefore treated as the project's source of truth.



Dashboard Pages


Page 1 - England Overview



Provides a national view of attainment recovery.

Features:

Reading, Writing, Mathematics and Combined KPI cards
Interactive Academic Year slicer
National attainment trend chart
Covid disruption annotation


Page 2 - Subject Analysis



Explores whether recovery patterns differed by subject.

Features:

Subject selector
Expected Standard attainment trends
Higher Standard attainment trends
Fixed chart scales for consistent comparison


Page 3 - Regional Comparisons



Compares regional performance against the national benchmark.

Features:

Region selector
Regional attainment KPI
National attainment KPI
Difference from National KPI
Regional trend chart
National trend chart


Skills Demonstrated


Power BI
Interactive dashboard design
Visualisation development
KPI creation
Slicer interactions
Report design and layout
Power Query
Data transformation
Data cleaning
Custom columns
Type conversion
Troubleshooting refresh errors


DAX


Measures
Calculated KPIs
Regional comparison calculations
Data Analysis
Data validation
Trend analysis
Regional benchmarking
Comparative analysis
Insight generation


Key Findings


KS2 attainment declined following Covid-related disruption.
Recovery has occurred across all measures since assessments resumed.
Recovery patterns differ between subjects.
Regional variation remains evident when compared against the national average.
Some regions have recovered more strongly than others.

