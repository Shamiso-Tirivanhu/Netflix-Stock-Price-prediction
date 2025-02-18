# Netflix-Stock-Price-prediction Analysis

## Description

This project analyzes Netflix stock price trends using machine learning techniques. The dataset includes historical stock prices, and the analysis involves data visualization and predictive modeling using Decision Trees and Lin

## Table of Contents

1. [Dataset](#datset)
2. [Usage](#useage)
3. [Features](#features)
4. [Technologies Used](#technological-used)
5. [Results](#results)
6. [Contributing](#contribution)

## 1. Dataset

The dataset used for this analysis is a CSV file containing historical Netflix stock prices. Ensure that NFLX_Stock_Price.csv is available in the project directory.

## 2. Usage

Run the Google colab Notebook to:

- Load and visualize Netflix stock price data

- Train and evaluate machine learning models

- Make stock price predictions

## 3. Features

- Data Preprocessing: Cleans and prepares stock price data

- Visualization: Uses Matplotlib for stock trends visualization

   - Machine Learning Models:

  - Decision Tree Classifier

  - Decision Tree Regressor

- Linear Regression

- Stock Price Prediction

## 4. Technologies Used

- Python

- Pandas

- NumPy

- Scikit-learn

- Matplotlib

- Google colab Notebook

## 5. Results

The project explores historical stock trends and builds predictive models to forecast future prices. Key insights include:

- Model Performance: The Decision Tree Regressor and Linear Regression models were evaluated for accuracy, with performance metrics including Mean Squared Error (MSE) and R-squared scores. Among the two, the Linear Regression model performed better, providing more reliable and stable long-term predictions, while the Decision Tree Regressor captured short-term fluctuations but tended to overfit the data as shown below.



![Image_Alt](https://github.com/Shamiso-Tirivanhu/Netflix-Stock-Price-prediction/blob/cc4509be4fa2d67abdfb3bb6a459b77e51535466/Netflix%20Stock%20Price.png)






- Historical Trends: The analysis identified patterns in Netflix's stock prices, including seasonal fluctuations and significant market events that influenced stock movement.

- Feature Importance: The Decision Tree model helped determine which stock indicators had the most impact on price predictions.

- Prediction Insights: The models demonstrated varying degrees of accuracy, with linear regression providing more stable long-term trends and decision trees capturing short-term fluctuations.

- Limitations & Future Work: The project highlights challenges such as market volatility and external factors (e.g., earnings reports, macroeconomic trends) that were not accounted for. Future improvements could incorporate sentiment analysis and additional financial indicators.

## 6. Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
