# Stock_Price_Prediction_Assignment_Using_RNNs
This repo has the details about an assignment on Stock Price Predictions using RNNs

# 📈 Stock Price Prediction using RNN and LSTM

This project compares the performance of a **Simple RNN** and an **Advanced RNN (LSTM)** for stock price prediction using time series data. The goal is to evaluate the models' accuracy and robustness in predicting stock prices for both single and multiple target stocks (e.g., MSFT, IBM, GOOGL, AMZN).

---

## 🧠 Models Used

### 1. Simple RNN
- Captures basic sequential patterns.
- Less capable of handling long-term dependencies.
- Tends to generalize and smooth out fluctuations.

### 2. LSTM (Long Short-Term Memory)
- Advanced RNN with memory cells.
- Better suited for capturing long-term dependencies and non-linear trends.
- More accurate during volatile market periods.

---

## 🖼️ Visualizations

### Simple RNN Prediction

![Simple RNN](./images/simple_rnn_prediction.png)

- The actual (blue) and predicted (red) stock prices show similar trends.
- Deviations occur during rapid changes or high volatility.
- Struggles in multi-target predictions.

---

### LSTM Prediction

![LSTM](./images/lstm_prediction.png)

- The actual (blue) and predicted (orange dashed) lines align closely.
- Handles fluctuations more effectively.
- Performs exceptionally well in multi-target prediction for MSFT, IBM, GOOGL, and AMZN.

---

## 🔍 Analysis

### Simple RNN:
- ✅ Captures overall trend.
- ❌ Poor performance during sharp fluctuations.
- ❌ Underperforms in multi-stock (multi-target) scenarios.

### LSTM:
- ✅ Accurately tracks both trend and local variations.
- ✅ Superior performance across all tested stocks.
- ✅ Handles volatility and long-term dependencies better.

---

## ✅ Conclusion

- **Performance**:
  - LSTM outperforms Simple RNN in tracking actual stock price movements.
- **Robustness**:
  - LSTM generalizes better to unseen sequences and volatile data.
- **Use Case Fit**:
  - LSTM is the preferred model for financial time series forecasting.

---

## 🚀 Future Improvements

- Explore **GRU** or **Transformer-based** models for even better performance.
- Try **ensemble models** combining RNN, LSTM, and traditional models.
- Incorporate **external factors** like news sentiment, macroeconomic indicators.

---

## 📂 Project Structure
- ReadMe.md
- RNN_Stock_Price_Prediction_Shashidhar_Pattar.zip

## **Author**
  - [Shashidhar Pattar](https://github.com/shashidharpattar007)


