This project implements a machine learning model to predict the daily movement of the Nifty 50 Index (^NSEI). Rather than predicting the exact price, the model focuses on a binary classification task: predicting whether the index will close higher or lower on the following day.

The program fetches historical data, performs feature engineering through rolling averages and trend analysis, and utilizes a Random Forest Classifier to make predictions. To ensure reliability, the project includes a backtesting framework.


To run this notebook, you need the following Python libraries installed:

yfinance: For fetching real-time and historical stock market data.

pandas: For data manipulation and analysis.

scikit-learn: For the Random Forest machine learning model and evaluation metrics.

matplotlib: For visualising historical price trends.