# 🚗 Car Price Prediction using Machine Learning

A machine learning project that predicts the selling price of a used car based on its characteristics such as manufacturing year, fuel type, kilometers driven, transmission type, and more.

---

## 📌 Overview

The objective of this project is to build a regression model capable of estimating the selling price of used cars using historical data.

The project includes:

- Data loading and exploration
- Data preprocessing
- Handling categorical features
- Feature engineering
- Model training using Linear Regression
- Model evaluation
- Visualization of predictions

---

## 📂 Dataset

The dataset contains information about used cars with the following features:

| Feature | Description |
|---------|-------------|
| Car_Name | Name of the car |
| Year | Manufacturing year |
| Present_Price | Current showroom price |
| Kms_Driven | Total kilometers driven |
| Fuel_Type | Petrol / Diesel / CNG |
| Seller_Type | Dealer or Individual |
| Transmission | Manual or Automatic |
| Owner | Number of previous owners |
| Selling_Price | Target variable |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Checking missing values
- One-Hot Encoding for `Fuel_Type`
- Label Encoding for:
  - Seller_Type
  - Transmission
- Splitting data into:
  - 80% Training set
  - 20% Testing set

---

## 🤖 Machine Learning Model

The project uses:

### Linear Regression

The model is trained to predict:

```python
Selling_Price
```

from the input features:

```python
Year
Present_Price
Kms_Driven
Fuel_Type
Seller_Type
Transmission
Owner
```

---

## 📈 Visualization

The project visualizes:

- Actual car prices vs Predicted car prices
- Scatter plot colored according to predicted values

---

## 📁 Project Structure

```text
├── car.ipynb          # Main notebook
├── car_data.csv       # Dataset
└── README.md          # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/0xmhss/Car-Price-Prediction-using-Machine-Learning.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Run the notebook:

```bash
jupyter notebook car.ipynb
```

---

## 📊 Future Improvements

- Try advanced regression algorithms:
  - Random Forest Regressor
  - XGBoost Regressor
  - Gradient Boosting
- Hyperparameter tuning
- Feature selection
- Cross-validation
- Deploy the model as a web application using Flask or FastAPI

---

## 👨‍💻 Author

**Mohamad Soussi**


---

⭐ If you found this project useful, consider giving it a star.
