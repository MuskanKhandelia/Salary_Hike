# Salary Hike Prediction

## Overview

This repository hosts a simple linear regression model implemented in Python via a Jupyter notebook. The goal of the project is to develop a prediction model for salary hikes based on years of experience.

## Objective

The primary objective of this project is to build a prediction model for salary hikes using the predictor variable of years of experience. The implemented model is a simple linear regression model.

## Implementation

The project utilizes Pandas, Seaborn, and Scikit-learn for data analysis, visualization, and model building. The Jupyter notebook included in this repository provides a step-by-step guide through data preprocessing, exploratory data analysis, and building the linear regression model.

## Exploratory Data Analysis (EDA)

EDA involves analyzing the dataset using Pandas and Seaborn. Key observations include a highly positive correlation (0.97) between salary hike and years of experience. The dataset exhibits no null values or outliers.

## Model Building

Scikit-learn is employed for model building, training, and evaluation. A simple linear regression model is chosen due to the high correlation observed in the exploratory data analysis.

## Model Performance

The model is evaluated using the R2 score, resulting in 0.96 for training data and 0.95 for testing data. The R2 score indicates the proportion of the variance in the dependent variable that is predictable from the independent variable. The project results suggest a high level of predictability for salary hikes based on years of experience.
