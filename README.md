🛢️ Oil Price Prediction of India

📌 Project Overview

This project aims to predict oil prices in India using Machine Learning techniques. Multiple regression models were implemented and compared to evaluate their performance and reliability.

📊 Dataset Features

- Year
- Brent Oil Price (USD/barrel)
- USD to INR Exchange Rate
- Global Oil Demand (mb/d)
- Global Conflict (0/1)

Target Variable:

- Oil Price in India (INR/barrel)

⚙️ Models Used

- Linear Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)

📈 Model Performance

Model            | R² Score| RMSE| MAE| Stability
Linear Regression| 0.9780  | 238 | 190| Best
Ridge Regression | 0.9769  | 244 | 190| Good
KNN Regressor    | 0.9470  | 370 | 237| Unstable

🔍 Key Observations

- Linear and Ridge models produced very similar results, indicating a strong linear relationship in the data.
- Ridge Regression improved model stability through regularization.
- KNN performance improved after feature scaling but remained less stable with higher error values.
- Residual analysis showed that Linear and Ridge models have more consistent error distribution compared to KNN.

🔮 Future Prediction

All models were tested on the same future input data:

- Linear & Ridge → consistent predictions (~8200 range)
- KNN → varied prediction (~7600 range)

This indicates that KNN is less reliable for future forecasting due to its dependence on local data points.

✅ Conclusion

Linear Regression achieved the best performance with the highest accuracy and lowest error. Ridge Regression performed similarly and offers better stability due to regularization. KNN showed lower performance and less consistent predictions, making it less suitable for this dataset.

🚀 Future Improvements

- Apply Time Series models (LSTM)
- Perform hyperparameter tuning
- Include more real-world influencing factors

🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

📂 Project Structure

- "oil_price_prediction.ipynb"
- Dataset (CSV file)
- README.md

👨‍💻 Author

Sisir Pradhan
