#📌 Project Overview

This project analyzes the global impact of the COVID-19 pandemic using real-world data.
We explore patterns, visualize trends, and build predictive models to understand the spread, mortality, and hospitalization trends.

🎯 Objectives

Perform Exploratory Data Analysis (EDA) to identify trends in cases, deaths, and hospitalizations.

Build classification models to predict mortality severity.

Create visualizations for clear insights.

Summarize findings with metrics and tabulated results.

🔍 Steps Performed
1️⃣ Data Cleaning & Preprocessing

Loaded the dataset DATA COVID 19.csv.

Handled missing values and ensured proper date formatting.

Created new features such as:

Mortality Rate = (total_deaths / total_cases) * 100

Cases per Million = (total_cases / population) * 1,000,000

High Mortality Label (Binary Classification target).

2️⃣ Exploratory Data Analysis (EDA)

Plotted time-series graphs of total cases and deaths.

Compared countries with highest cases & deaths.

Visualized ICU and hospital patient counts.

Created heatmaps & bar charts for regional analysis.

3️⃣ Machine Learning Model

Defined High Mortality Countries (above median mortality rate).

Built classifiers to predict mortality category:

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier

Compared models using Accuracy, Precision, Recall, and F1-Score.

4️⃣ Visualization of Metrics & Results

Confusion Matrices (heatmap-style).

ROC Curves for each classifier.

Tabulated comparison of evaluation metrics.

Clear visual insights on cases, deaths, and hospitalization trends.

📊 Key Insights

Countries with higher cases per million did not always have higher mortality rates.

ICU and hospitalization data correlated strongly with new deaths.

Ensemble methods (Random Forest, Gradient Boosting) outperformed Logistic Regression in mortality classification.

Visualizations revealed waves of cases & deaths and highlighted countries most affected.

🛠️ Tech Stack

Language: Python 🐍

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Jupyter Notebook / Google Colab

📌 Deliverables

Cleaned dataset (DATA COVID 19.csv)

Jupyter Notebook with EDA, Visualizations, and Models

Visual insights (charts, heatmaps, ROC curves)

Tabulated results of model performance

✅ This project provides a comprehensive data science workflow — from data cleaning, visualization, to predictive modeling — applied to real COVID-19 data.
