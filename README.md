╔══════════════════════════════════════════════════════════════╗
         📊 IBM HR ANALYTICS DASHBOARD
         Workforce Intelligence & Attrition Insights
╚══════════════════════════════════════════════════════════════╝

An interactive Power BI dashboard that transforms raw HR data
into executive-level workforce insights — covering attrition,
headcount, departmental performance, and workforce distribution.

──────────────────────────────────────────────────────────────
 🚀  PROJECT OVERVIEW
──────────────────────────────────────────────────────────────

The IBM HR Analytics Dashboard is an advanced workforce
intelligence solution built in Power BI to help organizations
make smarter, data-driven HR decisions.

  Built for  →  HR Professionals · Recruiters · Managers
                Business Analysts · Executives

  Enables    →  Attrition monitoring & retention strategy
                Workforce composition analysis
                Departmental performance tracking
                Executive-ready reporting & insights

──────────────────────────────────────────────────────────────
 🎯  BUSINESS PROBLEM
──────────────────────────────────────────────────────────────

Employee attrition directly impacts productivity, hiring costs,
and operational continuity. This dashboard answers critical
HR questions:

  ▸ Which departments have the highest attrition?
  ▸ How does overtime influence employee turnover?
  ▸ Which job roles dominate workforce distribution?
  ▸ Are there gender-based workforce trends?
  ▸ Where should retention efforts be prioritized?

──────────────────────────────────────────────────────────────
 📌  CORE KPIs AT A GLANCE
──────────────────────────────────────────────────────────────

   👥  Total Employees        →   1,470
   ✅  Active Employees       →   1,224
   📉  Attrition Rate         →   16.7%
   💰  Avg Monthly Income     →   $9,171
   🏢  Departments Covered    →   3
   💼  Job Roles Tracked      →   9

──────────────────────────────────────────────────────────────
 📊  DASHBOARD FEATURES
──────────────────────────────────────────────────────────────

  1️⃣  EXECUTIVE KPI OVERVIEW
      Quick-glance strip for total headcount, active employees,
      attrition rate, and average monthly income.

  ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─

  2️⃣  HEADCOUNT BY JOB ROLE

      Manager                   ████████████████  371
      Research Director         ██████░░░░░░░░░░  163
      Manufacturing Director    ██████░░░░░░░░░░  160
      Laboratory Technician     █████░░░░░░░░░░░  157
      Healthcare Representative █████░░░░░░░░░░░  154
      Sales Executive           █████░░░░░░░░░░░  149
      Sales Representative      █████░░░░░░░░░░░  145
      Research Scientist        █████░░░░░░░░░░░  139
      Human Resources           █░░░░░░░░░░░░░░░   32

  ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─

  3️⃣  ATTRITION RATE BY DEPARTMENT

      ⚠️  Sales                  18.6%   [ High Risk      ]
      ⚠️  Research & Development 16.4%   [ Above Average  ]
      ✅  Human Resources        10.0%   [ Stable         ]

      ············· Benchmark: 15.0% ·············

  ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─

  4️⃣  WORKFORCE DISTRIBUTION

      🔵  Research & Development   65.17%
      🔷  Sales                    30.07%
      ⬛  Human Resources           4.76%

      → Organization is heavily R&D-oriented. Technical
        workforce stability is critical for continuity.

  ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─

  5️⃣  INTERACTIVE FILTERS (SLICERS)

      🏢 Department    →  HR  /  Sales  /  R&D
      ⏱️ Overtime      →  Yes  /  No
      🧑 Gender        →  Male  /  Female

──────────────────────────────────────────────────────────────
 🛠️  TECH STACK
──────────────────────────────────────────────────────────────

   Power BI Desktop   →  Dashboard development & visualization
   DAX                →  KPI calculations & custom measures
   Power Query        →  Data cleaning & transformation
   IBM HR Dataset     →  Workforce analytics data source

──────────────────────────────────────────────────────────────
 🧮  SAMPLE DAX MEASURES
──────────────────────────────────────────────────────────────

  Attrition Rate:
  DIVIDE(
    CALCULATE(COUNTROWS(HR_Data), HR_Data[Attrition] = "Yes"),
    COUNTROWS(HR_Data)
  )

  Active Employees:
  CALCULATE(COUNTROWS(HR_Data), HR_Data[Attrition] = "No")

  Average Monthly Income:
  AVERAGE(HR_Data[MonthlyIncome])

──────────────────────────────────────────────────────────────
 ⚙️  PROJECT WORKFLOW
──────────────────────────────────────────────────────────────

   📥 Raw HR Dataset (CSV)
        │
        ▼
   🔧 Data Cleaning & Transformation   →  Power Query
        │
        ▼
   🗂️  Data Modeling & Relationships
        │
        ▼
   📐 DAX Measures & KPI Calculations
        │
        ▼
   📊 Interactive Visualizations       →  Power BI
        │
        ▼
   📋 Dashboard Insights & Reporting

──────────────────────────────────────────────────────────────
 💡  KEY BUSINESS INSIGHTS
──────────────────────────────────────────────────────────────

  🔴  At 16.7%, attrition exceeds the 12–15% industry
      benchmark — signalling an active retention challenge.

  🟠  Sales leads attrition at 18.6%, pointing to possible
      workload pressure or incentive misalignment.

  🔵  65%+ of the workforce is in R&D — making technical
      talent retention mission-critical.

  🟢  HR maintains the lowest attrition at 10.0%, sitting
      well below the organizational average.

──────────────────────────────────────────────────────────────
 🎯  STRATEGIC RECOMMENDATIONS
──────────────────────────────────────────────────────────────

  ▸ Launch targeted retention programs in the Sales department
  ▸ Conduct overtime impact analysis to reduce burnout
  ▸ Introduce R&D-specific employee satisfaction initiatives
  ▸ Run monthly attrition KPI reviews for early detection
  ▸ Develop workforce forecasting models for strategic hiring
  ▸ Implement pulse surveys in high-attrition departments

──────────────────────────────────────────────────────────────
 🌟  FUTURE IMPROVEMENTS
──────────────────────────────────────────────────────────────

  ○  Predictive attrition model via Python & ML
  ○  Employee churn risk scoring & classification
  ○  Diversity & inclusion analytics page
  ○  Time-series workforce trend analysis
  ○  Mobile-optimized Power BI layout
  ○  Automated HR alerts & KPI threshold monitoring
  ○  Power BI Service cloud deployment

──────────────────────────────────────────────────────────────
 🙌  ACKNOWLEDGEMENTS
──────────────────────────────────────────────────────────────

  IBM Watson Analytics    →  Original HR dataset
  Kaggle                  →  Dataset hosting
  Microsoft Power BI      →  Visualization platform & community

──────────────────────────────────────────────────────────────
 👨‍💻  AUTHOR
──────────────────────────────────────────────────────────────

  Mohamed Aashiq
  B.Sc Data Science Student
  Aspiring Data Analyst  |  Power BI Enthusiast  |  HR Analytics Learner

  DASHBOARD PREVIEW : 

╔══════════════════════════════════════════════════════════════╗
   ⭐ Star the repo  •  🍴 Fork it  •  📢 Share feedback
╚══════════════════════════════════════════════════════════════╝
