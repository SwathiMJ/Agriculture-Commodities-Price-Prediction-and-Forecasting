
# Agriculture Commodities Price Prediction and Forecasting

## Aim
The aim of this project is to enhance agricultural decision-making in India by developing a comprehensive system for crop recommendation and price forecasting. This system addresses the critical need for regional language support and evidence-based recommendations to assist farmers in making informed decisions regarding storage and sales options.

## Objective
The primary objective of this study is to review existing research on price forecasting in agriculture, identify the pros and cons of different models, and propose enhancements for more effective crop recommendations and price forecasting. This includes developing models using advanced machine learning techniques and ensuring the system can handle regional language requirements.

## Documentation

### Data Preprocessing
Data preprocessing involves several steps to prepare the data for modeling:

1. Feature Engineering for Numerical Columns:

* Standardization and normalization techniques to handle numerical data.
2. Feature Engineering for Categorical Columns:

* Encoding categorical variables using techniques like one-hot encoding.
3. Concatenating Numerical and Categorical Columns:

* Combining preprocessed numerical and categorical features into a single dataset.
4. Train-Test Split:

* Splitting the dataset into training and testing sets to evaluate model performance.

## Modeling Approach
### Ordinary Least Squares (OLS) Regression
* OLS is used to estimate the relationship between a dependent variable and one or more independent variables, aiming to minimize the sum of squared differences between observed and predicted values.

### Random Forest Regression
* An ensemble learning technique that constructs multiple decision trees and averages their predictions to improve accuracy and robustness, especially for non-linear relationships.

## Evaluation Metrics
1. Accuracy: 
Ratio of correctly predicted instances to the total number of instances.

2. Precision: 
Ratio of correctly predicted positive observations to the total predicted positives.

3. Recall (Sensitivity): 
Ratio of correctly predicted positive observations to all actual positives.

4. F1 Score:
 Harmonic mean of precision and recall.

5. Confusion Matrix: 
A summary of prediction results, showing true positives, true negatives, false positives, and false negatives.

## Conclusion
### Key Findings
* Dataset Overview: 
The rich dataset provided insights into market transactions, crop details, and pricing information.

* Challenges:
 Identified the need for regional language support and better decision-making tools for farmers.

* Modeling Approach: 
Implemented OLS and Random Forest Regression models to predict crop prices and provide recommendations.

### Benefits
1. Improved Decision-Making:

* Provides farmers with actionable insights into crop prices, helping them make informed decisions regarding crop selection, storage, and sales strategies.
2. Regional Language Support:

* Recognizes the importance of regional languages, paving the way for future developments that include local language interfaces and recommendations.
3. Economic Growth:

* Supports sustainable agricultural practices and economic growth by offering evidence-based decision support tools for farmers and policymakers.
