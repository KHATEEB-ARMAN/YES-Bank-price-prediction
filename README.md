# 📊 YES Bank Stock Price Prediction

A machine learning project that predicts the closing price of YES Bank stock based on input features such as Open, High, and Low prices. It includes model training, evaluation, and a Flask web interface for real-time predictions.

---

## 🔧 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn (Linear, Ridge, Random Forest, etc.)
- GridSearchCV for tuning
- Flask (for web UI)
- Pickle (for model persistence)

---

## 💡 Features
- Preprocesses historical stock data
- Trains & evaluates 6 regression models
- Saves best model & scaler
- Interactive web app (input Open, High, Low → predict Close)
- Clean HTML interface in Chrome

---

## 📁 Key Files
├── new_df.csv # Cleaned stock dataset
├── app.py # Flask web app
├── best_ridge_model.pkl # Best saved ML model
├── scaler.pkl # Scaler for feature normalization
├── templates/
│ └── index.html # Input form