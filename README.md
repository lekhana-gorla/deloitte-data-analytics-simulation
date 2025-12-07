# deloitte-data-analytics-simulation
Deloitte Data Analytics Job Simulation — completed through Forage. This repository contains two end-to-end analytics tasks: (1) factory telemetry downtime analysis using Tableau, and (2) gender pay equality score classification using Excel. Includes dashboards, logic formulas, analysis steps, and project documentation.
deloitte-data-analytics-simulation/
│
├── Task1-Telemetry-Downtime/
│   ├── dashboard_screenshot.pdf
│   ├── README_Task1.md
│
├── Task2-Gender-Equality-Analysis/
│   ├── Equality_Table_Completed.xlsx
│   ├── Objective: Classify Equality Scores into Fair, Unfair, or Highly Discriminative
        Files: Equality_Table_Completed.xlsx
        Formula Used: =IF(ABS(C2) <= 10, "Fair", IF(ABS(C2) <= 20, "Unfair", "Highly Discriminative"))
        Explanation (short): Uses ABS to treat negative and positive scores equally.
        Fair: ±10
        Unfair: 11–20
        Highly Discriminative: >20
        Outcome: Automatically classifies each job role based on its Equality Score.
