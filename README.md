



![HR-Analytics](https://github.com/Neelam-Sambnani/HR-Data-Analytics/assets/125915800/feb43251-1d9b-456e-9d4a-2313255b2fb4)












**HR Analytics Project:  Employee Attendance and Leave Patterns Analysis**
---

Welcome to my HR Analytics project, where I leveraged Power BI to conduct a comprehensive analysis of employee attendance and leave patterns within a company. The main objective was to uncover trends and insights that would contribute to more effective workforce management strategies.

**Project Overview**
---
In this project, I harnessed the power of data analytics to gain valuable insights into employee attendance and leave behavior. By analyzing these patterns, I aimed to provide actionable information for optimizing HR processes and enhancing overall workforce productivity.

**Data Description**
---
The HR Analytics project is built upon an Excel dataset containing three main sheets, each providing essential data related to employee attendance and leave patterns. Here's a description of the key fields in the dataset:





![Screenshot (56)](https://github.com/Neelam-Sambnani/HR-Data-Analytics/assets/125915800/26197d7d-25a4-46c5-a012-e63a646b3d53)






**Data Exploration**
---
In the data exploration phase, the following key activities were carried out for each of the three sheets:

**Data Merging:**

**-**  While the sheets represent data for different months, data from all three sheets were merged within Power BI to create a unified dataset. This allowed for comprehensive analysis 
        and visualization.

**Data Transformation:**

**-**  Data cleaning and transformation were performed on each sheet individually to ensure accuracy and consistency. This included handling date formats, addressing missing or 
       inconsistent values, and preparing the data for analysis.

**Key Measures:**
 
 **- Presence %:**  Calculating the percentage of days an employee was present across the three months.

 **- Sick Leave %:**  Determining the percentage of days an employee took sick leave across the three months.
                      
                      SL % = DIVIDE([SL Count],[Total Working Days],0)
 
 **- Work from Home %:**  Analyzing the percentage of days an employee worked remotely across the three months.
 
 **- Total Working Days:**  Count of total working days across the three months.

                            Total Working Days = 
                            Var totaldays = count('Final Data'[Value])
                            Var noworkdays = CALCULATE(COUNT('Final Data'[Value]),'Final Data'[Value] in {"WO","HO"})

                            RETURN
                            totaldays - noworkdays
  
 **- Sick Leave Count:**  Count of sick leave instances across the three months.

 **- Present Days:**  Count of days when the employee was present in the office across the three months.


**Tools and Technologies Used**
---
**Tools:**  Power BI, Excel

**Data Source**
---
For this analysis, I worked with an Excel file consisting of three sheets, each containing essential data:

**Employee Presence:**  This sheet held records of employees' attendance at the office.

**Sick Leave:**  It contained information about sick leave taken by employees.

**Work-from-Home Records:**  This sheet recorded instances of employees working remotely.



**Dashboard Creation**
---
Central to the project's success was the development of an interactive dashboard using Power BI. This dashboard showcased the analysis findings through a variety of visually engaging representations, including bar charts, line charts, and pie charts. The dashboard enabled stakeholders to comprehensively explore employee attendance and leave patterns.





![Screenshot (12)](https://github.com/Neelam-Sambnani/HR-Data-Analytics/assets/125915800/4855c048-604f-486a-b396-fe6a9317bf19)








![Screenshot (13)](https://github.com/Neelam-Sambnani/HR-Data-Analytics/assets/125915800/4a6d02c8-0b6a-4c40-ac7f-de0c39e7843a)










**Key Insights**
---
**Identified Peak Absence Periods:**  By analyzing sick leave data, I pinpointed specific periods with higher sick leave rates, allowing HR to plan accordingly.

**Evaluated Remote Work Trends:**  Insights into work-from-home patterns provided guidance for structuring remote work policies and evaluating its impact on productivity.

**Informed Resource Allocation:**  The presence percentage shed light on employee availability, facilitating efficient resource allocation.





![Screenshot (15)](https://github.com/Neelam-Sambnani/HR-Data-Analytics/assets/125915800/a1570c77-54e4-4bfb-b589-cb5af90fa79c)








**Impact and Significance**
---
The HR Analytics project empowered stakeholders to make informed decisions:

**Strategic Workforce Planning:**  The insights gained guided the HR team in optimizing workforce management strategies.

**Enhanced Productivity:**  By addressing absenteeism patterns and leveraging remote work trends, the company could enhance overall employee productivity.

**Data-Driven Decision-Making:**  The interactive dashboard enabled stakeholders to make data-driven decisions in real-time.

**Conclusion**
---
This HR Analytics project exemplifies my proficiency in data analysis and visualization. By employing Power BI, I transformed raw data into actionable insights, equipping stakeholders with the tools needed for effective workforce management and strategic planning.

**Challenges Faced:**
---
**Data Integration:**  Merging data from diverse Excel sheets with varying formats.

**Data Quality:**  Ensuring accuracy and consistency through rigorous cleansing.

**Interpretation Complexity:**  Understanding HR nuances to derive meaningful insights.

**Future Scope**  
---
**Predictive Analytics:**  Implement predictive models to forecast attendance and leave patterns, aiding in proactive HR planning.

**Employee Satisfaction Analysis:**  Incorporate employee feedback data to gain insights into factors affecting attendance and leave.

**Machine Learning:**  Explore machine learning algorithms to identify early indicators of employee burnout or attrition.

**Benchmarking:**  Compare your company's HR metrics with industry benchmarks for better context and insights.

**Real-Time Analytics:**  Develop real-time dashboards for continuous monitoring and quick decision-making.




