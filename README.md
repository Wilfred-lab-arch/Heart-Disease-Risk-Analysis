# Heart-Disease-Risk-Analysis
📌 Project Overview

This project performs exploratory data analysis, advanced visualization, predictive modeling, clustering, and interactive dashboard development on a heart disease dataset.

The goal is to analyze how age, cholesterol, blood pressure, obesity, smoking, and diabetes influence heart attack risk and present insights using both static plots and interactive 3D dashboards.

The project follows a production-style structure with reusable modules instead of one large notebook.

🎯 Objectives

This project demonstrates how to:

✔ Explore health data distributions
✔ Visualize relationships between risk factors
✔ Build predictive models
✔ Perform patient segmentation (clustering)
✔ Create interactive dashboards
✔ Export filtered data

🛠 Technologies Used

Python

Matplotlib (static plots)

Seaborn (statistical visualization)

Plotly (interactive 3D charts)

Dash (web dashboard)

scikit-learn (ML models & clustering)

Pandas & NumPy

📂 Project Structure
heart-disease-analytics/
│
├── data/                 # Dataset
├── notebooks/            # Colab / analysis notebooks
├── src/                  # Reusable Python modules
├── dashboard/            # Dash web app
├── outputs/              # Saved figures & models
├── requirements.txt
└── README.md

📊 Features Implemented
🔹 Exploratory Data Visualization (Assignment 1)
1. Cholesterol Distribution

Histogram + KDE curve

Shows spread, skewness, and outliers

Identifies high-risk cholesterol groups

2. Age vs Cholesterol Relationship

Scatter + trend line

Reveals positive correlation with aging

3. Multi-Axis Plots

Bar chart: cholesterol by gender

Scatter: blood pressure vs age

4. FacetGrid Visualization

Segmented plots by smoking status

Compare outcomes across groups

5. Advanced Bar Charts

Categories with error bars

Group comparisons

🔹 Interactive Visual Analytics (Assignment 2)
6. 3D Risk Factor Scatter

Interactive Plotly chart:

X → Age

Y → Cholesterol

Z → Blood Pressure

Color → Heart Attack Outcome

Hover → extra patient info

Helps visually identify risk clusters.

7. Logistic Regression Risk Surface

Model predicts heart attack probability

Uses Age + Cholesterol

Displays 3D surface of risk zones

Highlights low → high risk regions

8. Clustering Analysis

K-Means segmentation

Groups patients by similar risk profiles

3D cluster visualization

Useful for targeted interventions

9. Dash Interactive Dashboard

Web app features:

Filters (gender, etc.)

Dynamic bar charts

Real-time updates

CSV export
