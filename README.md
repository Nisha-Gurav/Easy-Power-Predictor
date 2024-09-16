# Easy Power Predictor

**A Machine Learning Model for Predicting Electricity Consumption**

## Project Overview

"Easy Power Predictor" is a machine learning-based project designed to forecast electricity consumption by integrating various weather conditions and holiday data. The model aims to enhance electricity distribution efficiency, reduce energy wastage and optimize power distribution strategies. This project was developed using a combination of machine learning algorithms, including Linear Regression, Random Forest and XGBoost with Random Forest identified as the most effective model for accurate predictions.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Technology Stack](#technology-stack)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributors](#contributors)
- [References](#references)

## Introduction

In today's energy landscape, the dynamics of electricity production and consumption are increasingly complex, particularly with the rising integration of renewable energy sources. The "Easy Power Predictor" project addresses these challenges by leveraging machine learning techniques to accurately forecast energy demand. By considering factors like weather conditions, time of day, and holidays, the model helps bridge the gap between electricity supply and demand, ensuring reliable and cost-effective energy management.

## Methodology

### 1. Data Collection and Integration
- **Data Sources:** Power consumption data from smart meters, historical records, weather data, and holiday schedules.
- **Data Aggregation:** Combined data from multiple sources to create a comprehensive dataset for analysis.

### 2. Data Preprocessing
- **Data Cleaning:** Removed noise, handled missing values, and corrected errors to ensure data quality.
- **Normalization:** Scaled data for consistency across different ranges and units.
- **Feature Engineering:** Extracted relevant features such as time of day, weather conditions, and device types.

### 3. Exploratory Data Analysis (EDA)
- **Visualization:** Used histograms, scatter plots, and correlation heatmaps to analyze relationships between variables.
- **Correlation Analysis:** Identified significant predictors influencing electricity consumption.

### 4. Model Building
- **Algorithm Selection:** Experimented with Linear Regression, Random Forest, and XGBoost.
- **Training and Testing:** Split the dataset into training, testing, and validation sets.

### 5. Model Evaluation
- **Performance Metrics:** Assessed models using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) values.

### 6. Model Selection
- **Comparison:** Random Forest emerged as the best-performing model based on evaluation metrics, demonstrating strong generalization and accuracy.

## Technology Stack

- **Python:** Primary programming language used for data preprocessing, modeling, and implementation.
- **Pandas:** Utilized for data manipulation and preprocessing tasks.
- **Scikit-Learn:** Used for building and training machine learning models.
- **Matplotlib & Seaborn:** Libraries for data visualization.
- **Jupyter Notebook:** Interactive environment for code development and model prototyping.

## Results

- **Best Fit Model:** Random Forest was identified as the best-performing model.
- **Performance:** The model maintained low error metrics and high R-squared values across all data splits, demonstrating strong generalization and accuracy.

## Conclusion

The "Easy Power Predictor" project highlights the potential of machine learning techniques in optimizing electricity distribution, reducing energy wastage, and achieving cost savings for utility providers. By accurately forecasting electricity consumption, the model provides valuable insights for informed decision-making in energy management.

## Contributors

- **Kanchan A. Khedikar** - Assistant Professor, Walchand Institute of Technology, Solapur
- **Shreyansh Kahate** - UG Scholar, Walchand Institute of Technology, Solapur
- **Vipul Ghodke** - UG Scholar, Walchand Institute of Technology, Solapur
- **Shreya Gandhi** - UG Scholar, Walchand Institute of Technology, Solapur
- **Nisha Gurav** - UG Scholar, Walchand Institute of Technology, Solapur

## References

- Jatin Bedi and Durga Toshniwal. *Empirical Mode Decomposition Based Deep Learning for Electricity Demand Forecasting*, IEEE, 2018.
- M Vetri Selvi et al. *Investigation of Performance of Electric Load Power Forecasting in Multiple Time Horizons with New Architecture*, IEEE, 2020.
- D. Hadjout et al. *Electricity consumption forecasting based on ensemble deep learning with application to the Algerian market*, ScienceDirect, 2021.
- Shilong Fan. *Research on Deep Learning Energy Consumption Prediction Based on Generating Confrontation Network*, IEEE, 2019.
- Susanna Berkouwer. *Electric Heating and the Effects of Temperature on Household Electricity Consumption in South Africa*, Energy Institute at Haas, 2019.
 

