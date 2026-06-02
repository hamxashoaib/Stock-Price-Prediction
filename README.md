# 📈 Stock Price Prediction Using Machine Learning

## 🚀 Project Overview
This project predicts the next day's stock closing price using historical market data from Yahoo Finance. Machine learning regression models are trained on stock features such as Open, High, Low, and Volume to forecast future closing prices.

The project demonstrates the complete machine learning workflow, including data collection, preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 🎯 Objective
To predict the next day's closing stock price using historical stock market data and machine learning techniques.

---

## 📊 Dataset
The dataset is fetched directly from Yahoo Finance using the yfinance Python library.

### Features Used
- Open Price
- High Price
- Low Price
- Volume

### Target Variable
- Next Day Closing Price

---

## 🧠 Machine Learning Models
### 1. Linear Regression
A simple baseline regression model used to establish initial prediction performance.

### 2. Random Forest Regressor
An ensemble learning model that improves prediction accuracy by combining multiple decision trees.

---

## ⚙️ Project Workflow

1. Download historical stock data from Yahoo Finance.
2. Select relevant features.
3. Create the target variable by shifting the closing price by one day.
4. Split data into training and testing sets while preserving time order.
5. Train Linear Regression and Random Forest models.
6. Evaluate models using Mean Squared Error (MSE).
7. Visualize actual and predicted stock prices.
8. Predict the next day's closing price.

---

## 📈 Results
The models successfully learn patterns from historical stock data and generate next-day closing price predictions.

Random Forest generally provides better performance compared to Linear Regression due to its ability to capture non-linear relationships in stock market data.

---

## 📊 Visualization
The project includes a comparison graph showing:
- Actual Stock Prices
- Linear Regression Predictions
- Random Forest Predictions

This helps evaluate model performance visually.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Stock-Price-Prediction.git
cd Stock-Price-Prediction
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open Jupyter Notebook and run all cells:

```bash
jupyter notebook stock_prediction.ipynb
```

---

## 📚 Skills Demonstrated

- Data Collection using APIs
- Financial Data Analysis
- Data Preprocessing
- Feature Engineering
- Regression Modeling
- Model Evaluation
- Data Visualization
- Time Series Data Handling

---

## 🔮 Future Improvements

- LSTM Deep Learning Models
- Real-Time Stock Prediction Dashboard
- Multiple Stock Analysis
- Technical Indicators (RSI, MACD, Bollinger Bands)
- Hyperparameter Tuning
- Model Deployment using Streamlit

---

## 👨‍💻 Author

Hamza Shoaib

BS Artificial Intelligence  

The Islamia University of Bahawalpur

---

## 📄 License

This project is developed for educational and portfolio purposes.
