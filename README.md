# 🏠 House Price Prediction - California Housing Dataset

This project uses the California Housing dataset to predict house prices based on features like income, house age, location, and more. The model is trained using **Linear Regression**.

---

## 📁 Dataset

- Source: Scikit-learn's built-in California housing dataset
- Total features: 8
- Target: Median house value (in 100,000s)

---

## 🔧 Technologies Used

- Python 🐍
- Pandas
- Numpy
- Scikit-learn
- Matplotlib

---

## 📊 Features Used

| Feature         | Description                            |
|-----------------|----------------------------------------|
| MedInc          | Median income in the block             |
| HouseAge        | Median house age                       |
| AveRooms        | Average number of rooms per household  |
| AveBedrms       | Average number of bedrooms             |
| Population      | Block population                       |
| AveOccup        | Average household occupancy            |
| Latitude        | Geographical coordinate                |
| Longitude       | Geographical coordinate                |

---

## 🔍 Model Used

- **Linear Regression**
- Trained on 80% of the data and tested on 20%

---

## 📈 Model Evaluation

| Metric         | Score     |
|----------------|-----------|
| MAE (Mean Absolute Error) | ~0.53 |
| MSE (Mean Squared Error)  | ~0.51 |
| RMSE                      | ~0.71 |
| R² Score                  | ~0.62 |

---

## 🧪 Custom Input Test

Predicted house price for the input:
```python
[8.3014, 21.0, 6.23, 0.97, 2401.0, 2.109, 37.86, -122.22]
