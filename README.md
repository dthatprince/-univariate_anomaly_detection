# Univariate Anomaly Detection (Machine Learning Methods)

This project implements univariate anomaly detection using machine learning techniques in Python, within a Jupyter Notebook environment. It focuses on detecting unusual patterns or outliers in single-variable datasets using advanced machine learning methods.

---

## Overview

Anomaly detection is a critical aspect of data analysis and monitoring, used in applications such as fraud detection, quality control, and predictive maintenance. In this project, we explore three popular machine learning models for univariate anomaly detection:

- **Isolation Forest**
- **One-Class SVM**
- **Kernel Density Estimation (KDE)**

Each method is applied to detect anomalies based on a dataset of Twitter mentions for a given company (e.g., *Amazon*). The project includes data loading, cleaning, preprocessing, model training, and visualization to provide a comprehensive approach to anomaly detection.

## Implementation Steps

1. **Data Loading and Preprocessing**  
   Load the dataset, clean, and prepare it for analysis. This includes handling missing values and filtering data for a specific company (e.g., *Amazon*).

2. **Model Training**  
   Train each model on the data to identify anomalies:
   - **Isolation Forest**
   - **One-Class SVM**
   - **Kernel Density Estimation (KDE)**

3. **Anomaly Detection**  
   Apply each model to the dataset and set thresholds to classify data points as "Anomaly" or "Normal".

4. **Visualization**  
   Plot the results using a scatter plot to visualize anomalies over time using Plotly.

