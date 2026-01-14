
# Intrusion Detection using NSL-KDD Dataset

## Overview
This project focuses on building an intrusion detection system using the NSL-KDD dataset.  
The objective is to classify network connections as either **normal** or **malicious** based on behavioral patterns in network traffic.

## Dataset
The NSL-KDD dataset represents real-world network traffic with features describing:
- Connection behavior
- Traffic volume
- Connection frequency
- Error rates
- Host-based activity

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Verified missing values
- Removed non-informative features
- Converted multi-class labels into binary classification (Normal vs Attack)
- Prepared dataset for machine learning models

### 2. Exploratory Data Analysis
- Analyzed behavioral differences between normal and attack traffic
- Studied error rates, data volume, and connection repetition
- Identified key indicators of intrusion through visual and statistical analysis

### 3. Modeling
- Build and evaluate classification models
- Handle class imbalance
- Optimize detection performance

## Key Insights
- Attack connections exhibit significantly higher error rates
- Malicious traffic shows aggressive repetition patterns
- Certain features strongly correlate with intrusion behavior

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Author
Hrutuja Patil
