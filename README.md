Patient Emergency Room Visit Dashboard
Overview
This interactive dynamic dashboard, developed using Power BI, provides precise information about patient visits to the Emergency Room. It offers insights into wait times based on the time of day and differentiates between visits on weekdays and weekends. The dashboard aims to enhance patient understanding and experience by presenting actionable insights derived from comprehensive data analysis.

Project Steps
1. Data Extraction and Cleaning
Extracted data from Kaggle, ensuring data integrity and relevance.
Conducted preliminary cleaning to prepare the dataset for analysis.
2. Date Table Creation
Developed a Date table with custom calculations to categorize visits into weekends, weekdays, and AM/PM admissions, facilitating time-based analysis.
3. Calculation Table
Created a Calculation Table to house all key measures:
Measure 1: Total patients visited
Measure 2: Average wait time
Measure 3: Average satisfaction score
Measure 4: Percentage of referred patients and walk-in patients
Measure 5: Percentage of male, female, and other patients visits
Measure 6: Percentage of administrative and non-administrative patients
Measure 7: Dynamic Heat Map Caption
4. Parameter Implementation
Implemented parameters for Average Wait Time and Satisfaction Score, allowing users to customize their analysis.
Visualization Techniques
Heat Map:
Illustrates Average Satisfaction Score and Average Wait Time based on Age group and Patients Race.
Column Chart:
Displays the distribution of patients visited during weekends and weekdays.
Bar Graph:
Visualizes total patients visited through referrals and walk-ins, categorizing them based on Age buckets.
Line and Area Chart:
Represents the total number of patients visited every month and over the years, providing insights into visit trends.
