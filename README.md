# S&P 500 Stock Performance Prediction

This project focuses on predicting the performance of S&P 500 stocks using a combination of value and momentum indicators. Value indicators include well-known financial ratios like P/E ratio and Dividend yield, while momentum is measured using trailing 3, 6, and 12-month returns.

## Key Features
- Utilized a diverse set of machine learning models including Support Vector Machines, Random Forests, AdaBoost, K-Nearest Neighbors, Naive Bayes, XGBoost, Logistic Regression, and Perceptron.
- Engineered meaningful features by calculating momentum periods for each stock based on historical closing prices.
- Set a target of predicting stocks with returns greater than 2% in the next month, equivalent to 25%+ annualized return, to ensure a margin of safety.
- Employed cross-validation to assess model performance, comparing accuracy scores across different algorithms.

## Project Structure
- Data preprocessing steps included handling missing values and feature engineering.
- Combined financial data and momentum indicators into a single dataset.
- Employed a variety of machine learning algorithms to train and evaluate predictive models.
- Conducted cross-validation to estimate model accuracy and compare their performance.

Feel free to explore the code and methodology to understand how we approached the challenge of predicting S&P 500 stock performance.

## Libraries Used
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- XGBoost
  
![acc](https://github.com/Ronit11246/S-P500_Prediction/assets/108767208/9b767859-eafc-4472-8542-049d1adabe5b)
