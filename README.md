# SQL-Road-Accidents-Analysis
This project focuses on analyzing road accident data using SQL to uncover meaningful insights and patterns. It involves querying large datasets to examine factors such as accident frequency, location, time, By using SQL operations like joins, aggregations, and filtering.

## Project Overview
This project aims to analyze the distribution of incidents across various cities, focusing only on those where the count exceeds 15 cases. By filtering and ranking cities based on their incident frequency, we can identify areas with a higher occurrence of minor injuries and assess the underlying factors contributing to these accidents. Understanding these patterns is essential for recognizing high-risk urban zones and addressing road safety concerns effectively.
Using SQL-based data analysis, the project extracts meaningful insights from road accident records, categorizing incidents by city and cause. This structured approach allows us to pinpoint cities with frequent minor injury cases and examine which cause categories are most prevalent. The findings can help policymakers, traffic authorities, and urban planners develop targeted safety measures to reduce road accidents and improve overall traffic management. 

## Questions
.Top Cities with the Highest Incident Count
.Distribution of "Minor Injury" Incident Outcomes Across Cities (Greater Than 15)
.Top Cities for Each Specific Cause Category
.Most common outcome across all cities
.City-wise distribution of accidents caused.
.Cities with lowest number of accidents.
.PERCENTAGE OF EACH OUTCOME TYPE.
.CITY WITH HIGHEST ACCIDENT FOR A SPECIFIC CAUSE CATEGORY.
Most common outcome across all cities<img width="1880" height="159" alt="image" src="https://github.com/user-attachments/assets/d1820b2f-98f6-4b71-a0fc-c6ef3886823f" />


## Analysis Approach
The analysis was carried out using SQL aggregation and grouping techniques on pre aggregated accident data. Since the dataset already contained summarized incident counts, functions such as SUM(Count) were used instead of record counting. City wise, cause identify high-- wise, and outcome level based queries were executed to risk cities, dominant accident causes, and frequently occurring outcomes. Special attention was given to minor injury cases, as they represent recurring safety issues that often go underreported compared to fatal accidents.

## Key Insights
Major metropolitan cities such as Delhi, Mumbai, and Bengaluru report the highest number of accident incidents, indicating a strong correlation between traffic density and accident frequency. • Cities like Coimbatore, Trichy, and Gwalior show comparatively lower accident counts, suggesting relatively safer traffic conditions or lower vehicle density. • Minor Injury emerges as the most common outcome across all cities, accounting for the majority of reported incidents, while fatal and grievous injury cases form a smaller proportion
Over Speeding and Drunken Driving are among the most frequently reported accident causes across multiple cities, highlighting behavioral factors as key contributors to road accidents. City wise analysis reveals that different cities exhibit different dominant causes; for example, overspeeding is more prominent in larger metros, whereas other causes appear more evenly distributed in smaller cities. • During analysis, it was observed that certain city could not be derived due to level cause combinations limitations in data granularity importance of structured and detailed data collection. 

## Summary
This project successfully analyzed regulatory road accident data using SQL to identify city wise accident trends, dominant causes, and outcome distributions. By focusing on aggregated data, the study efficiently highlighted high risk cities and recurring minor injury cases that require regulatory attention. The findings emphasize the importance of targeted road safety measures rather than uniform policies across cities. Overall, the structured SQL based analysis demonstrates how data driven insights can assist traffic authorities and policymakers in improving urban road safety planning and decision making.



