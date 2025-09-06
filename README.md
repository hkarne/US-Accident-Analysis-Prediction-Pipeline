# Accident Severity Prediction Pipeline

This project leverages advanced data engineering and machine learning techniques to accurately predict accident severity based on a variety of environmental and temporal factors. The dataset includes detailed records of accidents along I-95 and US-1, featuring columns such as windspeed, precipitation, and timestamps. As a Data Engineer, my focus was on transforming raw, messy data into actionable insights through robust data pipelines and modeling.

## Project Overview

**Objective:**  
Develop a scalable pipeline to clean, analyze, and model accident data, enabling accurate severity predictions and supporting data-driven decision making for traffic safety.

## Step 1: Data Engineering & Cleaning

The initial dataset required significant preprocessing. I engineered automated workflows to clean, transform, and convert columns to appropriate datatypes (e.g., parsing accident times to Date-Time format). This process ensured consistency and reliability for downstream analysis.

## Step 2: Exploratory Data Analysis

I performed comprehensive analyses to uncover key patterns, including:

- I-95 experiences the highest accident frequency.
- Daytime accidents are more common in rainy and cloudy conditions.
- Miami reports the most accidents among cities studied.
- Peak accident times occur during morning (7-9 AM) and afternoon (3-6 PM) hours.

These insights were visualized through dynamic charts and dashboards, supporting rapid hypothesis testing and data exploration.

## Step 3: Predictive Modeling

I implemented and compared multiple machine learning models:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosted Classifier

Throughout model development, I addressed issues such as multi-collinearity, heteroskedasticity, and endogeneity. Feature engineering and selection were used to optimize model accuracy. Model performance was evaluated using feature importance, partial dependence plots, and SHAP values.

---

**This pipeline demonstrates end-to-end data engineering, from raw data ingestion to impactful predictive analytics, empowering stakeholders to make informed decisions for traffic safety.**
