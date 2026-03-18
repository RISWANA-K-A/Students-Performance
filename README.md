# Students-Performance
  A data-driven analysis of 6,600+ student records identifying critical drivers of academic success. Features comprehensive EDA, multivariate analysis, and institutional strategy recommendations.
  Strategic Analysis of Student Performance Factors
Transforming raw educational data into actionable institutional insights.

📌 Business Problem

Educational institutions often struggle to identify which "at-risk" students to prioritize. This project analyzes 6,600+ student profiles to identify the most   critical behavioral and environmental variables that drive academic success, providing a data-driven roadmap for intervention.

🔍 Exploratory Data Analysis (EDA)

The goal of the EDA was to uncover the hidden relationships between 20 different variables and final exam scores.

Key Insights Discovered:

* The Attendance Threshold: Discovered a strong positive correlation ($r = 0.58$) between attendance and scores. Crucially, the data shows a performance "tipping point" at 75% attendance; below this, scores collapse regardless of study hours.

* The Digital Ceiling: Multivariate analysis revealed that Internet Access acts as a "Resource Gatekeeper." Students without it are statistically capped from reaching the top 10% performance tier.

* The Safety Net Effect: Parental Involvement serves as a "Score Floor." High involvement significantly reduces score variance, preventing total failure even in low-motivation students.

🛠️ Technical Implementation

* Data Cleaning: Handled missing values, encoded categorical variables, and performed feature scaling.

* Exploratory Analysis: Conducted Univariate, Bivariate, and Multivariate analysis using Seaborn ,Matplotlib and Plotly.

* Statistical Validation: Used Correlation Matrices ,Box Plots and sunburst to validate the significance of environmental factors over purely academic ones.

💡 Recommendations & Impact

Based on the EDA findings, this project proposes three institutional shifts:

* Early Warning System: Monitor attendance and trigger counseling interventions at the 80% mark.

* Digital Equity Initiatives: Prioritize internet subsidies for low-resource demographics to "break the ceiling".

* Mentorship Programs: Provide institutional "Safety Nets" for students identified with low parental involvement.

🏁 Conclusion

This analysis proves that student success is a structural system. By focusing on Attendance and Digital Access, institutions can move from reactive grading to proactive support—potentially reducing overall failure rates by up to 20%.
