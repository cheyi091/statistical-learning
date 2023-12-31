# Statistical Learning

## HW1: Analyzing Sales Data using Linear Regression
* Data Exploration: Dimensions of the dataset are determined, and data distribution is examined.
* Linear Regression Models: Three models are fitted, predicting sales based on different independent variables.
* Model Evaluation: Metrics such as MSE, RMSE, RSS, RSE, and TSS are calculated for model assessment.

## HW2: Credit Default Prediction using Logistic Regression and Probit Models
* Logistic Regression: A logistic regression model is fitted on the "default" dataset, exploring default status and variables such as student status, balance, and income.
* Probit Models: Probit models are fitted on the "HMDA" dataset, comparing different specifications and conducting likelihood-ratio tests.
* Train-Test Split: The "HMDA" dataset is split into training and testing sets for model training and prediction.

## HW3: Comparing Regression and SVM Models for Predictive Analysis
* Model Fit Comparison: Compare linear regression, SVM, and LASSO regression models. Evaluate their performance using metrics such as RMSE, R^2, accuracy, and effects of variables.
* Linear Regression: Fit models on "Rating" using "Income" and "log of Income" as predictors. Visualize results with ggplot.
* SVM: Implement SVM on "Purchased" using "Age" and "EstimatedSalary" as predictors. Evaluate accuracy with a confusion matrix and plot the results.
* LASSO Regression: Fit a LASSO model on "Hitters" dataset, analyzing the effects of top variables at optimized and log(lambda) = 0.

## HW4: Predicting Legendary Pokemon using Machine Learning Algorithms
* Predict Legendary Pokemon: Compare SVM with One-Hot-Encoding and KNN for predicting legendary Pokemon.
* Compare prediction accuracy using ROC and AUC metrics: Evaluate logit, probit, SVM, and GBM models using ROC and AUC metrics.
* Resampling methods: K-fold vs. Bootstrapping: Estimate logistic regression models using K-fold cross-validation and bootstrapping, and analyze the impact of polynomial degrees and bias.

## Term Project: Sentiment Analysis of News for Stock Price Movement Prediction
* Led a research project on predicting stock prices using sentiment analysis on news articles, employing Hugging Face's pretrained models and diverse machine learning algorithms.
* Achieved a prediction accuracy of 63.22% using an ensemble method, demonstrating a proficient application of ML models in finance.
* Proposed enhancements to the predictive model by incorporating additional financial indicators.

