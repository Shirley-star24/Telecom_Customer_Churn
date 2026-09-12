

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a telecommunications customer dataset to uncover patterns behind customer churn. The goal is to identify key drivers of churn, generate actionable insights for retention strategies, and prepare features for predictive modeling.

---

## 🎯 Objectives
- Segment customers based on **seniority and service usage**.
- Compare service adoption across **genders** (Male vs Female).
- Visualize proportions of customers with/without services (Phone, Multiple Lines, Internet, Online Security).
- Provide interactive dashboards for exploratory analysis.
- Lay the foundation for **predictive modeling** (e.g., tenure prediction).

---

## 🛠️ Tools & Technologies
- **Python** (pandas, numpy, matplotlib, seaborn, plotly)
- **Jupyter Notebook** for interactive exploration
- **Plotly Express** for interactive dashboards
- **ipywidgets** for dropdown-based interactivity
- **Scikit-learn** (planned) for clustering and predictive modeling
-**scipy**to perform some statistivcal analysis Chi square tests and Z-test to determine feature significance
---

## 📊 Key Features
- **Contingency Tables**: Frequency counts of service usage by seniority.
- **Percentage Conversion**: Normalized proportions for fair comparison.
- **Interactive Visualizations**: Grouped bar charts with dropdown filters.
- **Dashboard Function**: Reusable function to generate plots for any service.
- **Totals in Titles**: Each chart shows group sizes (n=Non-Senior, n=Senior) for transparency.



📈 General Insights
📌 Tenure & Seniority: Younger (non‑senior) customers churn at much higher rates, often due to price sensitivity and lower loyalty. Senior customers tend to stay longer, but require support‑focused retention strategies.

📌 Internet Service Type: DSL and Fiber customers churn at nearly equal rates, suggesting dissatisfaction with service quality or pricing. Customers with No Internet Service churn for different reasons (limited product relevance).

📌 Contract Type & Charges: Month‑to‑month contracts and higher monthly charges strongly correlate with churn, while longer contracts reduce churn risk.

📌 Balanced Gender Distribution: Gender alone is not a strong predictor of churn, but provides a reliable dimension for profiling since the dataset is nearly balanced.


📊 Sub‑Segmented Insights (Gender + Seniority Focus)
📌 Gender Segmentation: Overall churn differences between males and females are statistically significant, but most service features (partner status, dependents, phone service, multiple lines, internet service, online security) do not explain gender‑specific churn.

📌 Key Drivers by Gender: Tenure and senior citizen status are the strongest features influencing churn differences across genders.

📌 Service Adoption Patterns: Seniors are more likely to have No Internet Service, while non‑seniors adopt internet‑related add‑ons (like Online Security) at higher rates.

📌 Segmentation Opportunity: Combining tenure and seniority provides actionable retention strategies — e.g., loyalty programs for long‑tenure seniors, onboarding support for new non‑seniors.

📌 Visualization Clarity: Grouped bar charts and dashboards highlight subtle differences in service uptake, making patterns easy to communicate to stakeholders.



