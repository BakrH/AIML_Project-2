# AIML_Project-2
# Project-2: Used Cars Price Prediction

## Overview
This project aims to explore and analyze a dataset of used cars to identify key factors that influence their prices. By leveraging various regression models, we aim to provide actionable insights to a used car dealership, helping them make data-driven decisions regarding inventory acquisition and pricing strategies.

## Dataset
The dataset used in this project is sourced from Kaggle and contains information on 426,000 used cars. It includes various features such as:
- `price`: The selling price of the car
- `year`: The year the car was manufactured
- `manufacturer`: The brand of the car
- `model`: The model of the car
- `odometer`: The mileage of the car
- `fuel`: The type of fuel used
- `transmission`: The type of transmission (automatic/manual)
- `region`: The region where the car is sold
- Additional features related to the car's condition, size, and more.

## Objectives
- Understand the distribution of car prices and identify any quality issues within the dataset.
- Perform feature engineering to create new variables that may impact car prices.
- Apply various regression models (e.g., Linear Regression, Ridge Regression, Gradient Boosting) to predict car prices.
- Evaluate model performance using metrics such as Mean Squared Error (MSE).
- Provide insights into the key drivers of used car prices.

## Methodology
1. **Data Understanding**: Load the dataset and perform exploratory data analysis (EDA) to understand the data structure and identify any quality issues.
2. **Data Preprocessing**: Clean the data, handle missing values, and perform feature engineering (e.g., creating a `car_age` feature).
3. **Modeling**: Build and evaluate multiple regression models to predict the log-transformed price of the cars.
4. **Evaluation**: Compare model performance and interpret the results to identify key factors influencing car prices.
5. **Reporting**: Summarize findings and provide recommendations for the used car dealership.

## Requirements
To run this project, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
Usage
Clone the repository:
git clone https://github.com/BakrH/AIML_Project-2
cd project-2-cars
Run the Jupyter Notebook:
jupyter notebook
Open the notebook file and execute the cells to perform the analysis.
Conclusion
The findings from this project will help the used car dealership understand the factors that drive car prices, enabling them to optimize their inventory and pricing strategies for better sales performance.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Dataset sourced from Kaggle.
Special thanks to the contributors of the libraries used in this project.
