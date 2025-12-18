# Aileen's Data Portfolio

Welcome to my professional data portfolio. This repository showcases projects in **Power BI** and **R Studio**, demonstrating data analysis, visualization, and problem-solving skills. All data used is generic, fictional or anonymized for portfolio purposes.

## Projects

### 1. Power BI Dashboard Mockup
**Context:** Generic refunds data dashboard created as a portfolio mockup. Inspired by a real project.
**Objective:** Demonstrate dashboard design, data visualization, and Power BI skills.  
**Tools Used:** Power BI, Excel, DAX  
**Screenshots:**  
![Refund Dashboard](Power_BI/Dashboard.jpg)  
**Insights:** The dashboard highlights payments and refunds trends, top refund's causes, and percentage of refund by payments.

# Energy Consumption Estimation Optimization  
### Data-Driven Methodology using R & R Markdown

## Project Overview
This project presents a data-driven approach to optimize the methodology used for estimating electrical energy consumption in wastewater treatment plants.

The analysis replaces manual, spreadsheet-based procedures with a reproducible and scalable workflow developed in R, allowing for more robust baseline estimation, performance evaluation, and model comparison.

All data used in this project is anonymized and synthetically generated based on realistic industrial parameters, ensuring confidentiality while preserving methodological validity.

---

## Objectives
- Improve the accuracy and robustness of energy consumption estimation
- Compare multiple predictive modeling approaches
- Evaluate model performance using proper validation techniques
- Demonstrate reproducible analytical workflows using R Markdown

---

## Data Description
The project focuses on a single wastewater treatment plant as a representative case study.

**Target variable**
- Electrical energy consumption (kWh)

**Predictor variables**
- Treated water volume (m³)
- Dissolved Oxygen (DO)
- Mixed Liquor Total Suspended Solids (MLTSS)

Exploratory data analysis revealed that several process-related variables do not follow normal distributions, motivating the use of non-linear and non-parametric models in addition to linear regression.

---

## Methodology

### 1. Data Preparation & Exploration
- Variable renaming and standardization
- Density analysis and distribution diagnostics
- Visual inspection by year and overall behavior

### 2. Data Partitioning
- 80% training / 20% testing split
- 10-fold cross-validation for model tuning
- Reproducibility ensured via fixed random seeds

---

## Models Implemented

### Linear Regression
- Models with two and three predictors
- Performance evaluated using RMSE, MAE, and R²
- Results showed instability and signs of overfitting when additional variables were included

### k-Nearest Neighbors (k-NN)
- Feature scaling and centering via recipes
- Hyperparameter tuning for optimal number of neighbors
- Demonstrated better generalization and stable performance on test data

### Decision Tree Regression
- Tuned cost-complexity parameter, tree depth, and minimum node size
- Cross-validation used for model selection
- Provided interpretable results with controlled model complexity

---

## Key Findings
- Linear regression models showed limited explanatory power and instability
- k-NN achieved better generalization and avoided overfitting
- Decision trees offered a good balance between interpretability and predictive performance
- Model complexity control (pruning, depth, node size) was critical for generalization

---

## Tools & Technologies
- R / R Studio
- R Markdown
- tidyverse
- tidymodels
- ggplot2
- plotly
- kknn
- rpart
- doParallel

---

## Notes
This project was developed for portfolio purposes.  
All datasets are anonymized or synthetically generated and do not represent real operational data.
