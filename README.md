NEET Counselling Predictor Dashboard
📌 Project Overview

This project simulates NEET counselling analysis using Python for synthetic data generation and Power BI for visualization. It provides insights into student admissions, competition across categories, department preferences, and state/college analysis to support students and decision-makers in the counselling process.

🎯 Goals

Generate a synthetic dataset (~50,000 rows) representing NEET aspirants.

Build an interactive Power BI dashboard for analysis.

Provide KPIs and visual insights for better counselling decisions.

🔄 Process

Data Generation – Python (Faker & Pandas) used to create 30K–50K synthetic student records with details like rank, marks, category, state, college, and preferred department.

Data Cleaning – Processed dataset into neet_cleaned_dataset for visualization.

Visualization (Power BI) – Built dashboards with KPIs, funnel chart, bar chart, and map visuals.

Insights – Category-wise competition, state & college distribution, top department demand, government vs private analysis.

📊 Dashboard Features

KPI Cards: Total Colleges, Total States, Total Cities, Govt/Private Colleges.

Funnel Chart: Category-wise distribution of admissions.

Bar/Column Charts: Department and college demand trends.

Map: State-wise student distribution and college locations.

🛠️ Tools & Technologies

Python – Pandas, Faker (data generation & processing)

Power BI – Dashboarding & Visualization

Excel – Initial data validation and checks

📂 Dataset

neet_cleaned_dataset.csv → Cleaned synthetic dataset (~50,000 rows).

Columns: Rank, Marks, Category, Admit_College_Name, Admit_College_State, Admit_College_City, Admit_Ownership, Preferred_Department, etc.

📌 Insights

GEN & OBC categories show highest competition.

MBBS has the maximum demand, followed by BDS and AYUSH.

Govt colleges dominate high-demand admissions, while private colleges attract lower ranks.

Certain states emerge as hotspots for NEET admissions.

🚀 Future Enhancements

Add historical real data (if available).

Build predictive analytics (seat allotment probability).

Deploy dashboard online (Power BI Service / Streamlit).
