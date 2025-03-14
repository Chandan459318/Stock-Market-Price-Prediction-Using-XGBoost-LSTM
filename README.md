📈 Stock Market Price Prediction Using XGBoost & LSTM
🚀 Overview
This project predicts Apple (AAPL) stock prices using XGBoost and LSTM (Long Short-Term Memory) deep learning models. The goal is to leverage machine learning and deep learning to forecast stock price trends and compare the accuracy of both models.

📊 Features & Capabilities
✅ Data Preprocessing & Feature Engineering

Cleaned and transformed 10 years of Apple stock data.
Engineered key features like Daily Returns, RSI, Volatility, and EWMA for better predictions.
✅ XGBoost Model

Trained an XGBoost Regressor for short-term stock price prediction.
Achieved high R² and low RMSE, making it an effective predictive model.
✅ LSTM Deep Learning Model

Built a Sequential LSTM model for capturing long-term trends.
Utilized time-series data to improve learning and minimize loss over training epochs.
✅ Next 30-Day Prediction

Forecasted next 30 days of stock prices using both XGBoost & LSTM.
Compared and visualized the predictions using matplotlib.
📂 Project Workflow
1️⃣ Data Collection & Cleaning → Load historical stock data and clean missing values.
2️⃣ Feature Engineering → Add technical indicators (RSI, EWMA, Volatility).
3️⃣ Model Training → Train XGBoost and LSTM models on processed data.
4️⃣ Evaluation → Compare models using MAE, RMSE, and R² scores.
5️⃣ Next 30-Day Prediction → Predict future prices and visualize trends.

🔧 Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)
Machine Learning: XGBoost
Deep Learning: TensorFlow (LSTM)
Data Preprocessing: MinMaxScaler (Normalization)
📈 Results & Insights
✔ XGBoost performed well in short-term prediction with low RMSE.
✔ LSTM captured long-term trends but had higher loss initially.
✔ Next 30-day forecast provides insights into future stock price trends.
