# Predicting Athletic Performance Using Big Data

This project was developed as part of the **Big Data (DS331)** course at Princess Nourah University.  
It focuses on analyzing sleep and wellness data collected from wearable devices and wellness reports to predict **athlete readiness** using Apache Spark MLlib.

## Dataset
- **PMData**: 16 participants
- Fitbit data (calories, heart rate, sleep scores)
- PMSys data (training sessions, wellness reports, injuries)
- Google Forms data (daily reports)

## Methods
- Data preprocessing and cleaning in PySpark
- Exploratory Data Analysis (EDA) with visualizations
- Machine Learning Models:
  - Random Forest (best model, Accuracy: 0.72, F1: 0.71)
  - Decision Tree
  - Logistic Regression

## Key Insights
- Deep sleep and resting heart rate strongly correlate with readiness.
- Objective wearable data gives better predictions than self-reported fatigue or mood.
- Readiness forecasts can help coaches adjust training loads to reduce injury risk.

## Tools & Libraries
- Apache Spark
- PySpark MLlib
- Pandas, Matplotlib, Seaborn

## Team Members
- Nourah Albarrak  
- Baylasan Almuqati  
- Leen Alharbi  
- Lina Aljasir
