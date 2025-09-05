# 🌑 ShadowPM  

ShadowPM is an AI/ML-based financial product that leverages **LSTM networks** to predict the **top 30 stocks from the S&P 500**, achieving **70% accuracy (RMSE)** and a **25% CAGR on backtesting**. The system was trained on **30+ million financial data points**, integrating fundamentals, temporal patterns, and macroeconomic indicators.  

---

## ✨ Key Features  
- 📊 **Stock Prediction**: Ranks the top 30 stocks from the S&P 500.  
- 🧠 **Deep Learning Model**: Built with **LSTM networks** for time-series forecasting.  
- 🔎 **Feature Engineering**:  
  - Temporal patterns  
  - Macroeconomic indicators  
  - Custom financial signals  
- 🛠 **Robust Training Pipeline**:  
  - Data cleaning (handling missing values, standardization)  
  - K-Fold cross-validation  
  - Grid & random search hyperparameter tuning  
- 📈 **Performance**:  
  - 70% accuracy (RMSE)  
  - 25% CAGR on backtests (outperforming S&P 500 benchmark)  
  - Custom evaluation metrics (NAV progression, common top accuracy)  

---

## 🛠 Tech Stack  
- **Python 3.x**  
- **TensorFlow / Keras** (LSTM model)  
- **pandas / NumPy** (data processing)  
- **scikit-learn** (feature engineering, cross-validation)  
- **Matplotlib / Seaborn** (visualizations)  
- **Excel Integration** (for reporting and manual validation)  

---

## 🚀 Installation  

Clone the repo:  
```bash
git clone https://github.com/your-username/shadowPM.git
cd shadowPM
