
# Carbon Emissions Impact Analysis

This project examines how rising atmospheric CO₂ concentrations influence global temperature anomalies using Python-based data analysis and simulation.

## Project Description

Climate change is one of the most critical challenges of our time. Rising carbon emissions play a pivotal role in driving global temperature anomalies. This study explores historical trends, correlations, causality, clustering and “what-if” scenario modelling of CO₂ vs global temperature anomalies to provide data-driven insights for policy and sustainability.

## Project Objectives

* Analyse historical CO₂ concentration and global temperature anomaly data.
* Quantify relationships and test predictive / causal links between CO₂ and temperature change.
* Build and compare statistical models and simulate future “what-if” CO₂ emission scenarios.
* Visualise results via time-series, scatter/heatmap, clustering and an interactive dashboard.

## Tools Used

* Python (Pandas, NumPy) for data manipulation
* Matplotlib, Seaborn, Plotly for visualisation
* Statsmodels, scikit-learn for regression, clustering & modelling
* Dash (Plotly) for interactive dashboard

## Project Details

Screenshots / Visuals:

* Time-series plot showing CO₂ and temperature trends over time
* Scatter plot + heatmap showing strong positive correlation (~0.95) between CO₂ and temperature
* Regression results (R² ~ 0.95) and “what-if” scenario predictions for ±10%/±20% CO₂
* Clustering results segmenting years into “Low CO₂/Low Temp”, “Moderate”, “High CO₂/High Temp” regimes
* Interactive dashboard with tabs for trends, scatter/heatmap and scenario simulation

## Project Conclusion & Learnings

The analysis confirms a very strong positive relationship between CO₂ concentrations and global temperature anomalies. While causality within the tested lag range (1–3 years) wasn’t statistically significant at the 0.05 level, the modelling and scenario simulations highlight the sensitivity of global temperatures to CO₂ levels. Key learnings include the value of interactive dashboards for communicating complex climate data, the importance of careful time-series modelling, and the crucial need for sustained CO₂ emissions mitigation to avoid future warming.
