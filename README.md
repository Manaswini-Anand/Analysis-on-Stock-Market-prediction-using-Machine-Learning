# Analysis-on-Stock-Market-prediction-using-Machine-Learning

Stock Market Prediction:

This project applies Machine Learning regression models on historical financial data to predict Portfolio Opening Values.
After evaluating multiple models (Linear Regression, Decision Trees, Random Forest, KNN, AdaBoost, Gradient Boosting, XGBoost, ANN, Bagging), the Bagging Regressor achieved the highest R² score and lowest error, making it the best-performing model for this dataset.

Dataset:

Instances: 516

Features: 18

Target Variable: PortfolioOpen

Features included:

Stock indices: NIFTY 50, FTSE 100, S&P 500, Hang Seng

Commodities: Gold, Brent Crude

Cryptocurrencies: Bitcoin (BTCINR)

Bond yields: US 5-Year Bond Yield

Currency exchange rates

Preprocessing:

Removed missing and redundant date fields.

Handled missing values in numerical features.

Checked for multicollinearity using VIF and dropped high-VIF features.

Normalized and validated dataset for training.

Best Model: Bagging Regressor

Train-Test Split: 70–30

R² Score: 0.9622

MAPE: 0.0108

The Bagging model consistently outperformed other models across different splits, showing strong generalization and robustness.
