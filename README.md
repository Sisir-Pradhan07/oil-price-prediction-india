# 🛢️ Oil Price Prediction of India

## 📌 Project Overview

This project predicts oil prices in India using Machine Learning techniques and global economic indicators. Multiple regression models were implemented and compared to evaluate their prediction accuracy, stability, and reliability.

---

## 📊 Dataset Features

- Year
- Month
- Brent Oil Price (USD/barrel)
- WTI Oil Price (USD/barrel)
- USD to INR Exchange Rate
- OPEC Production (mb/d)
- Global Oil Demand (mb/d)
- Global Conflict (0/1)

### 🎯 Target Variable
- Oil Price in India (INR/barrel)

---

## ⚙️ Models Used

- Linear Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)

---

## 📈 Model Performance

| Model | R² Score | RMSE | MAE | Performance |
|---|---|---|---|---|
| Linear Regression | 0.9780 | 238 | 190 | Best |
| Ridge Regression | 0.9769 | 244 | 190 | Good |
| KNN Regressor | 0.9470 | 370 | 237 | Moderate |

---

## 🔍 Key Observations

- Linear and Ridge Regression models achieved very high accuracy, indicating a strong linear relationship between the selected features and oil prices.
- Ridge Regression improved model stability using regularization.
- KNN performance improved after applying feature scaling using StandardScaler.
- Correlation analysis showed strong relationships between global oil indicators and Indian oil prices.
- Residual analysis indicated that Linear and Ridge models produced more consistent prediction errors compared to KNN.

---

## 🔮 Future Prediction

The trained models were tested using future economic input values for oil price forecasting.

- Linear & Ridge models produced stable predictions in the ₹8200 range.
- KNN produced comparatively varied predictions around the ₹7600 range.

This indicates that KNN is less reliable for long-term forecasting because it depends heavily on nearby data points.

---

## ✅ Conclusion

Linear Regression achieved the best performance with the highest R² score and lowest prediction error. Ridge Regression produced similar results while improving model stability through regularization. KNN showed lower performance and less consistent predictions, making it less suitable for this dataset.

---

## 🚀 Future Improvements

- Apply Time Series forecasting models (LSTM)
- Perform hyperparameter tuning
- Add more macroeconomic indicators
- Deploy model using Flask or Streamlit

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

- `oil_price_prediction.ipynb`
- `oil_price_dataset.csv`
- `README.md`
- `requirements.txt`

---

## 👨‍💻 Author

**Sisir Pradhan**