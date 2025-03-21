# Growthlink_assignment

## Sales Prediction for GrowthLink

## 📌 Task Objective

Predict car purchase amounts based on customer data using machine learning models. This helps businesses optimize marketing strategies by identifying high-value customers and forecasting potential spending.

---

## 🧾 Dataset

- **Source**: https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction?resource=download
- **Features**:
  - Demographics: Country, Gender, Age
  - Financial: Annual Salary, Credit Card Debt, Net Worth
  - Target: Car Purchase Amount

---

## 🧪 Steps Performed

1. **Exploratory Data Analysis**
2. **Data Cleaning**:
   - Removed name and email
   - Encoded gender
3. **Outlier Detection**
4. **Feature Scaling**
5. **Model Training**:
   - Linear Regression
   - Random Forest
   - XGBoost Regressor ✅
6. **Model Evaluation**:
   - MAE, RMSE, R²
   - Feature Importance
   - Residual Analysis ✅

---

## 🔧 Enhancements

- 🔥 **XGBoost Regressor**: Improved performance using gradient boosting.
- 📊 **Residual Analysis**: Checked prediction error distribution to confirm normality and unbiased model behavior.

---

## 🚀 Results

- **XGBoost** gave the best performance with the highest R² and lowest RMSE.
- Most influential features: Net Worth, Credit Card Debt, and Salary.

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AADHITHYAN07/sales-prediction.git
   cd sales-prediction

