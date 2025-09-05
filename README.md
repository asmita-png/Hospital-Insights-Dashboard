# Hospital-Insights-Dashboard

**Introduction**
Created Power BI dashboard to clearly display key hospital visitor trends and help decision-makers quickly find useful insights. It uses data modeling approaches and DAX formulas to break down patient demographics, show department demand, and highlight visitor experiences, all in one place. With these interactive visuals, healthcare staff can better spot patterns, manage resources, and aim for higher patient satisfaction.

**Key Tools  skills used:** 
•	Power BI for dashboard creation
•	Power Query Editor for cleaning and shaping data
•	DAX (Data Analysis Expressions) for custom calculations
•	Excel for preprocessing and exporting data

Data source: Kaggle

**Data Preprocessing**
Data went through ETL (Extract, Transform, Load) steps in the Power Query Editor, including:
•	Normalization to split up tables for easier analysis
•	Imputation to fill missing values and keep the data reliable

**DAX Calculations and Data Modeling**
I used DAX to build custom fields, such as average wait times and satisfaction scores, improving analytical depth. By modeling table relationships, I was able to quickly filter and compare multiple perspectives.

**Visit Trends and Patterns**
•	Daily & Monthly Visits: Both dashboards showcase daily and monthly visit trends, revealing peaks at month-end and a strong seasonal pattern (e.g., higher counts from April–October).
•	Yearly & Quarterly Visits: The visuals compare visits between years and quarters, revealing periods with increased patient flow, observation being that mid-year is busiest.

**Time-Based Distribution**
•	Day of Week Visits: Bar charts show which days are busier (e.g., Mondays and Wednesdays), confirming that weekdays having more visits than weekends.
•	Wait Time Distribution: Visuals reveal that most patients wait between 20 and 60 minutes, with a minority enjoying shorter waits.

**Demographic Insights**
•	Age, Gender, and Race: Pie and bar charts visualize the breakdown by age, gender, and race.

**Satisfaction and Departmental Insights**
•	Satisfaction Scores: The average satisfaction is shown as 5 out of 10, suggesting neutral or average ratings.
•	Department Referrals: Data on which departments receive more or fewer referrals is visualized, with General Practice and Orthopaedics standing out.
•	Admin Flag: The mix of registered and non-registered (visitor) cases is represented in a donut chart, showing about half of hospital visitors being fully registered.

Screenshots:
https://github.com/asmita-png/Hospital-Insights-Dashboard/blob/main/Screenshot%201%20of%20Dashboard.png
https://github.com/asmita-png/Hospital-Insights-Dashboard/blob/main/Screenshot%202%20of%20Dasboard.png
