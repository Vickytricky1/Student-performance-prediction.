# Student Pass/Fail Prediction

A machine learning project predicting whether a student passes or fails a course, based on attendance, homework completion, weekly study hours, and midterm scores.

## Overview

This project explores the relationship between student behaviour and academic outcomes, then builds and compares multiple classification models to predict pass/fail status.

## What's included

- **Exploratory Data Analysis**: boxplots, violin plots, and a correlation heatmap examining how attendance, homework, and study habits relate to academic performance
- **Model training and comparison**: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and Support Vector Machine classifiers
- **Model evaluation**: accuracy scores, classification reports, and confusion matrices for each model
- **Feature engineering**: created new features — attendance category (Low/Medium/High), study efficiency ratio, and an overall performance score — to improve interpretability
- **Feature importance analysis**: identified which factors most strongly predict student success using the Random Forest model

## Tools used

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn

## Key finding

Homework completion and attendance were the strongest predictors of whether a student passed, with study hours and midterm scores also contributing meaningfully to the model's predictions.

---
*Built as part of a data analytics training program (PluralCode Academy).*
