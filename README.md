# 📈 Stock Price Prediction with RNN

This project predicts future stock prices for Amazon (AMZN), Google (GOOGL), IBM, and Microsoft (MSFT) using sequential models like Simple RNN, LSTM, and GRU.

---

## 📂 Files

- **RNN_Stock_Price_Prediction.ipynb** — Jupyter Notebook with full data prep, modeling, and evaluation.
- **Data** — Not included here. Use the given CSV files for AMZN, GOOGL, IBM, MSFT.

---

## ✅ Models Used

- **Simple RNN**: Baseline model.
- **Advanced RNNs**: LSTM and GRU with hyperparameter tuning.

---

## 📊 Results

- **Best configuration**: LSTM, 100 units, 0.3 dropout.
- **Test RMSE**: ~113.13  
- **Validation Loss**: ~18,097

---

## 📌 How to Run

1. Clone the repo or download the notebook.
2. Install dependencies:  
   ```bash
   pip install tensorflow numpy pandas matplotlib scikit-learn
