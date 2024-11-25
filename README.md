# Introduction
This project analyzes SpaceX Falcon 9 rocket launches to uncover key factors that contribute to successful first-stage landings, leveraging data science and machine learning techniques. By examining variables like payload mass, launch site proximity, and orbit type, we aim to provide actionable insights to optimize rocket reusability, a cornerstone of SpaceX's cost-effective space exploration strategy.

#  Objectives
* Investigate how factors such as payload mass, launch sites, orbital parameters, and flight frequency influence first-stage landing success.
* Analyze trends in launch success rates over time.
* Identify the most effective machine learning model for predicting first-stage landing success, focusing on binary classification.

# Methodology
1. Data Collection:

Utilized the SpaceX REST API and web scraping techniques to retrieve comprehensive launch data.
Processed raw data into structured formats for analysis, addressing missing values and focusing on Falcon 9 launches.
Data Wrangling and Preparation:

Cleaned and transformed data by implementing one-hot encoding and converting categorical data into numerical formats.
Added a binary target variable to represent landing success (1) or failure (0).
Exploratory Data Analysis (EDA):

Conducted in-depth analysis using SQL, data visualization tools, and interactive geographic maps (e.g., Folium).
Examined correlations between payload mass, flight numbers, orbit types, and launch outcomes.
Predictive Modeling:

Built and evaluated multiple classification models, including Logistic Regression, SVM, Decision Trees, and K-Nearest Neighbors.
Used GridSearchCV for hyperparameter tuning and evaluated models with metrics such as accuracy, Jaccard Score, and F1 Score.
Determined that the SVM model achieved the best performance across all metrics.
Data Visualization:

Visualized results through interactive dashboards created with Plotly Dash, including features like dropdowns, sliders, and scatter plots.
