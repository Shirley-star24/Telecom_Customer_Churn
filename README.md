

## Project Overview
This project explores customer service usage patterns in a telecom dataset, focusing on **seniority (Non-Senior vs Senior)** and **gender differences**.  
Since churn labels were not available, the analysis emphasizes **customer segmentation, tenure prediction, and service adoption trends** to provide actionable insights for retention strategies.

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

---

## 📈 Actionable Insights
- 📌 **Gender Segmentation**: Overall churn differences between males and females are statistically significant, but most service features (partner status, dependents, phone service, multiple lines, internet service, online security) do not explain gender-specific churn.  
- 📌 **Key Drivers**: Tenure and senior citizen status are the strongest features influencing churn differences across genders.  
- 📌 **Service Adoption**: Seniors and non-seniors show different adoption rates for services like Online Security and Internet. Seniors are more likely to have "No Internet Service," while non-seniors adopt internet-related add-ons at higher rates.  
- 📌 **Balanced Gender Distribution**: Dataset is nearly balanced (≈50% male, 50% female), making gender-based comparisons reliable.  
- 📌 **Segmentation Opportunity**: Tenure-based segmentation combined with seniority can guide targeted retention strategies (e.g., loyalty programs for long-tenure seniors, onboarding support for new non-seniors).  
- 📌 **Visualization Clarity**: Grouped bar charts and dashboards highlight subtle differences in service uptake, making patterns easy to communicate to stakeholders.  

---



