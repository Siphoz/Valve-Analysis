# Machine Learning-Based Valve Cost Estimation


![Valve Picture]([https://example.com/profile.jpg](https://imgur.com/a/YyehJGn))


## Project Overview
- This project leverages machine learning to address missing cost data for industrial valves, improving cost prediction accuracy. By applying advanced data imputation techniques and predictive models, we enhanced cost estimation reliability for engineering and procurement teams.

## Problem Statement
- Missing cost data in valve procurement can lead to inaccurate estimates, affecting budgeting and decision-making. This project develops a machine learning solution to fill data gaps and provide more precise cost predictions.

### Data Sources
- Historical Cost Data: Centralized records from multiple engineering projects
- Cleopatra Costing Database: Additional valve specifications and pricing information

##### Methodology & Tools
- Data Processing & Preparation
- Data Cleaning & Manipulation: Python, Pandas, NumPy
- Feature Engineering: Column Transformer, Ordinal Encoding, One-Hot Encoding, MinMax Scaling, SelectPercentile

Exploratory Data Analysis (EDA)
- Visualization Tools: Matplotlib, Seaborn
- Key Insights: Identified weight, size, and pressure rating as primary cost drivers

Machine Learning Models & Techniques
- Model Development: Scikit-Learn (Linear Regression, K-Nearest Neighbors, Deep Learning)
- Imputation Techniques: Iterative Imputer, KNN Imputer for handling missing data
- Neural Network Implementation: TensorFlow, Keras for deep learning-based cost prediction

##### Results & Impact
- Correlation Analysis: Discovered key factors influencing cost (weight, size, pressure rating)
- Model Accuracy: Achieved an 80% improvement in cost estimation accuracy
- Data Visualization: Created scatter plots and heatmaps to illustrate trends
- Neural Network Performance: Developed a predictive model with a low RMSLE (Root Mean Squared Logarithmic Error)
- Practical Application: Successfully generated cost predictions for new data, with results exported to Excel for use by the Estimation team

##### Conclusion
- This project highlights the power of machine learning in improving cost estimation for industrial components. By effectively handling missing data and leveraging predictive models, we significantly enhanced estimation accuracy. The results demonstrate how data-driven approaches can optimize cost analysis, reduce uncertainty, and support better decision-making in engineering and procurement. Future improvements could include integrating real-time cost updates and refining deep learning models for even higher precision.
