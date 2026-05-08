📊 IBM HR Analytics Dashboard
Workforce Intelligence & Attrition Insights

An interactive Power BI dashboard designed to transform raw HR data into executive-level workforce insights covering employee attrition, workforce distribution, departmental performance, and HR trends.

🖼️ Dashboard Preview

[ Insert Dashboard Screenshot Here ]

The dashboard includes:

Executive KPI Overview
Attrition Analysis
Workforce Distribution
Department-Level Insights
Interactive Filters & Drilldowns
🚀 Project Overview

The IBM HR Analytics Dashboard is a workforce intelligence solution built using Power BI to help organizations make smarter, data-driven HR decisions.

Built For
HR Teams
Recruiters
Managers
Business Analysts
Executives
Key Objectives
Monitor employee attrition
Analyze workforce composition
Track departmental performance
Support retention strategies
Enable executive-level reporting
Improve HR decision-making
🎯 Business Problem

Employee attrition directly impacts:

Productivity
Hiring costs
Workforce stability
Operational continuity

This dashboard helps answer key HR questions such as:

Which departments have the highest attrition?
How does overtime affect employee turnover?
Which job roles dominate workforce distribution?
Are there gender-based workforce trends?
Which areas require retention focus?
📌 Core KPIs
KPI	Value
👥 Total Employees	1,470
✅ Active Employees	1,224
📉 Attrition Rate	16.7%
💰 Avg Monthly Income	$9,171
🏢 Departments	3
💼 Job Roles	9
🧠 Skills Demonstrated
HR Analytics
Power BI Dashboard Development
Data Visualization
Business Intelligence Reporting
DAX Calculations
Power Query ETL
KPI Reporting
Workforce Intelligence
Attrition Analysis
Interactive Reporting
Data Cleaning & Transformation
Business Storytelling
📊 Dashboard Features
1️⃣ Executive KPI Overview

Displays:

Total Employees
Active Employees
Attrition Rate
Average Monthly Income

Provides quick executive-level workforce monitoring.

2️⃣ Headcount by Job Role
Job Role	Headcount
Manager	371
Research Director	163
Manufacturing Director	160
Laboratory Technician	157
Healthcare Representative	154
Sales Executive	149
Sales Representative	145
Research Scientist	139
Human Resources	32
Business Value
Understand workforce composition
Support recruitment planning
Identify staffing concentration
Balance organizational hierarchy
3️⃣ Attrition Rate by Department
Department	Attrition Rate	Status
Sales	18.6%	⚠️ High Risk
Research & Development	16.4%	⚠️ Above Average
Human Resources	10.0%	✅ Stable

Benchmark Threshold: 15%

Business Impact
Identify high-risk departments
Improve employee retention strategies
Enable department-level HR planning
Monitor workforce stability trends
4️⃣ Workforce Distribution
Department	Workforce Share
🔵 Research & Development	65.17%
🔷 Sales	30.07%
⬛ Human Resources	4.76%
Insight

The organization is heavily R&D-oriented, making technical talent retention critical for operational continuity.

5️⃣ Interactive Filters

The dashboard supports dynamic filtering by:

🏢 Department
⏱️ Overtime Status
🧑 Gender

These slicers enable personalized workforce analysis and drill-down reporting.

🛠️ Tech Stack
Tool	Purpose
Power BI Desktop	Dashboard Development & Visualization
DAX	KPI Calculations & Custom Measures
Power Query	Data Cleaning & Transformation
IBM HR Dataset	Workforce Analytics Data Source
🧮 Sample DAX Measures
Attrition Rate
Attrition Rate =
DIVIDE(
    CALCULATE(COUNTROWS(HR_Data), HR_Data[Attrition] = "Yes"),
    COUNTROWS(HR_Data)
)
Active Employees
Active Employees =
CALCULATE(
    COUNTROWS(HR_Data),
    HR_Data[Attrition] = "No"
)
Average Monthly Income
Avg Monthly Income =
AVERAGE(HR_Data[MonthlyIncome])
⚙️ Project Workflow

Raw HR Dataset
↓
Data Cleaning & Transformation (Power Query)
↓
Data Modeling & Relationships
↓
DAX Measures & KPI Calculations
↓
Interactive Power BI Visualizations
↓
Dashboard Insights & Reporting

💡 Key Business Insights

🔴 The overall attrition rate of 16.7% exceeds the standard industry benchmark, indicating a workforce retention challenge.

🟠 The Sales department records the highest attrition rate at 18.6%, suggesting possible workload pressure or dissatisfaction.

🔵 More than 65% of employees belong to R&D, making technical talent retention mission-critical.

🟢 Human Resources maintains the lowest attrition rate, remaining well below the organizational average.

🎯 Strategic Recommendations
Launch targeted retention initiatives in Sales
Conduct overtime impact analysis to reduce burnout
Improve employee engagement programs in R&D
Monitor attrition KPIs monthly
Develop workforce forecasting strategies
Implement pulse surveys in high-risk departments
🌟 Future Improvements
Predictive Attrition Model using Python & ML
Employee Churn Risk Classification
Diversity & Inclusion Analytics
Time-Series Workforce Trend Analysis
Mobile-Optimized Dashboard Layout
Automated HR KPI Alerts
Power BI Service Deployment
🙌 Acknowledgements
IBM Watson Analytics — Original HR Dataset
Kaggle — Dataset Hosting
Microsoft Power BI Community — Visualization Inspiration
👨‍💻 Author

Mohamed Aashiq
B.Sc Data Science Student

Aspiring Data Analyst | Power BI Enthusiast | HR Analytics Learner

⭐ Star the repo • 🍴 Fork it • 📢 Share feedback

ADD THE SCREENSHOT OPTION AT THE END
📊 IBM HR Analytics Dashboard
Workforce Intelligence & Attrition Insights

An interactive Power BI dashboard designed to transform raw HR data into executive-level workforce insights covering employee attrition, workforce distribution, departmental performance, and HR trends.

🚀 Project Overview

The IBM HR Analytics Dashboard is a workforce intelligence solution built using Power BI to help organizations make smarter, data-driven HR decisions.

Built For
HR Teams
Recruiters
Managers
Business Analysts
Executives
Key Objectives
Monitor employee attrition
Analyze workforce composition
Track departmental performance
Support retention strategies
Enable executive-level reporting
Improve HR decision-making
🎯 Business Problem

Employee attrition directly impacts:

Productivity
Hiring costs
Workforce stability
Operational continuity

This dashboard helps answer key HR questions such as:

Which departments have the highest attrition?
How does overtime affect employee turnover?
Which job roles dominate workforce distribution?
Are there gender-based workforce trends?
Which areas require retention focus?
📌 Core KPIs
KPI	Value
👥 Total Employees	1,470
✅ Active Employees	1,224
📉 Attrition Rate	16.7%
💰 Avg Monthly Income	$9,171
🏢 Departments	3
💼 Job Roles	9
🧠 Skills Demonstrated
HR Analytics
Power BI Dashboard Development
Data Visualization
Business Intelligence Reporting
DAX Calculations
Power Query ETL
KPI Reporting
Workforce Intelligence
Attrition Analysis
Interactive Reporting
Data Cleaning & Transformation
Business Storytelling
📊 Dashboard Features
1️⃣ Executive KPI Overview

Displays:

Total Employees
Active Employees
Attrition Rate
Average Monthly Income

Provides quick executive-level workforce monitoring.

2️⃣ Headcount by Job Role
Job Role	Headcount
Manager	371
Research Director	163
Manufacturing Director	160
Laboratory Technician	157
Healthcare Representative	154
Sales Executive	149
Sales Representative	145
Research Scientist	139
Human Resources	32
Business Value
Understand workforce composition
Support recruitment planning
Identify staffing concentration
Balance organizational hierarchy
3️⃣ Attrition Rate by Department
Department	Attrition Rate	Status
Sales	18.6%	⚠️ High Risk
Research & Development	16.4%	⚠️ Above Average
Human Resources	10.0%	✅ Stable

Benchmark Threshold: 15%

Business Impact
Identify high-risk departments
Improve employee retention strategies
Enable department-level HR planning
Monitor workforce stability trends
4️⃣ Workforce Distribution
Department	Workforce Share
🔵 Research & Development	65.17%
🔷 Sales	30.07%
⬛ Human Resources	4.76%
Insight

The organization is heavily R&D-oriented, making technical talent retention critical for operational continuity.

5️⃣ Interactive Filters

The dashboard supports dynamic filtering by:

🏢 Department
⏱️ Overtime Status
🧑 Gender

These slicers enable personalized workforce analysis and drill-down reporting.

🛠️ Tech Stack
Tool	Purpose
Power BI Desktop	Dashboard Development & Visualization
DAX	KPI Calculations & Custom Measures
Power Query	Data Cleaning & Transformation
IBM HR Dataset	Workforce Analytics Data Source
🧮 Sample DAX Measures
Attrition Rate
Attrition Rate =
DIVIDE(
    CALCULATE(COUNTROWS(HR_Data), HR_Data[Attrition] = "Yes"),
    COUNTROWS(HR_Data)
)
Active Employees
Active Employees =
CALCULATE(
    COUNTROWS(HR_Data),
    HR_Data[Attrition] = "No"
)
Average Monthly Income
Avg Monthly Income =
AVERAGE(HR_Data[MonthlyIncome])
⚙️ Project Workflow

Raw HR Dataset
↓
Data Cleaning & Transformation (Power Query)
↓
Data Modeling & Relationships
↓
DAX Measures & KPI Calculations
↓
Interactive Power BI Visualizations
↓
Dashboard Insights & Reporting

💡 Key Business Insights

🔴 The overall attrition rate of 16.7% exceeds the standard industry benchmark, indicating a workforce retention challenge.

🟠 The Sales department records the highest attrition rate at 18.6%, suggesting possible workload pressure or dissatisfaction.

🔵 More than 65% of employees belong to R&D, making technical talent retention mission-critical.

🟢 Human Resources maintains the lowest attrition rate, remaining well below the organizational average.

🎯 Strategic Recommendations
Launch targeted retention initiatives in Sales
Conduct overtime impact analysis to reduce burnout
Improve employee engagement programs in R&D
Monitor attrition KPIs monthly
Develop workforce forecasting strategies
Implement pulse surveys in high-risk departments

🌟 Future Improvements
Predictive Attrition Model using Python & ML
Employee Churn Risk Classification
Diversity & Inclusion Analytics
Time-Series Workforce Trend Analysis
Mobile-Optimized Dashboard Layout
Automated HR KPI Alerts
Power BI Service Deployment

🙌 Acknowledgements
IBM Watson Analytics — Original HR Dataset
Kaggle — Dataset Hosting
Microsoft Power BI Community — Visualization Inspiration
👨‍💻 Author

Mohamed Aashiq
B.Sc Data Science Student

Aspiring Data Analyst | Power BI Enthusiast | HR Analytics Learner

📸 Dashboard Screenshots
Main Dashboard View:

⭐ Star the repo • 🍴 Fork it • 📢 Share feedback
