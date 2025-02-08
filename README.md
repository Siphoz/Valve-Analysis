# Machine Learning-Based Valve Cost Estimation

<img src="https://i.imgur.com/i8YjCkq.jpg" alt="Valve Picture" width="550"/>

## Project Overview
This project leverages machine learning to predict the costs of industrial valves made from rare materials such as Titanium, Hastelloy, and Alloy 20—materials that are not readily available and often lack complete cost data. By analyzing key factors such as valve type, connection type, size, pressure rating, material composition, and market material costs, the model fills in missing data and enhances cost estimations. The goal is to develop accurate cost models that empower engineering and procurement teams to make more informed decisions and improve budgeting accuracy.

## Data Sources
- **Historical Cost Data**: Centralized records from multiple engineering projects
- **Cleopatra Costing Database**: Additional valve specifications and pricing information

## Methodology & Tools
**1. Data Processing & Preparation**
- Data Cleaning & Manipulation: Python, Pandas, NumPy

![Preprocessing](Pics/Preprocess.jpg)

- Feature Engineering: Column Transformer, Ordinal Encoding, One-Hot Encoding, MinMax Scaling, SelectPercentile

**2. Exploratory Data Analysis (EDA)**
- Visualization Tools: Matplotlib, Seaborn
- Key Insights: Identified weight, size, and pressure rating as primary cost drivers

**3. Machine Learning Models & Techniques**
- Model Development: Scikit-Learn (Linear Regression, K-Nearest Neighbors, Deep Learning)
- Imputation Techniques: Iterative Imputer, KNN Imputer for handling missing data
- Neural Network Implementation: TensorFlow, Keras for deep learning-based cost prediction

## Results & Impact
- **Correlation Analysis**: Discovered key factors influencing cost (weight, size, pressure rating)
- **Model Accuracy**: Achieved an 80% improvement in cost estimation accuracy
- **Data Visualization**: Created scatter plots and heatmaps to illustrate trends
- **Neural Network Performance**: Developed a predictive model with a low RMSLE (Root Mean Squared Logarithmic Error)
- **Practical Application**: Successfully generated cost predictions for new data, with results exported to Excel for use by the Estimation team

## Conclusion
This project highlights the power of machine learning in improving cost estimation for industrial components. By effectively handling missing data and leveraging predictive models, we significantly enhanced estimation accuracy. The results demonstrate how data-driven approaches can optimize cost analysis, reduce uncertainty, and support better decision-making in engineering and procurement. Future improvements could include integrating real-time cost updates and refining deep learning models for even higher precision.
