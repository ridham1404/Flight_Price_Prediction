# ✈️ Flight Price Prediction

A machine learning project that predicts airline ticket prices based on multiple factors such as airline, departure time, stops, and journey duration.

## 📂 Dataset
- Source: `flight_price.xlsx`
- Features:
  - Airline
  - Date of Journey
  - Source & Destination
  - Total Stops
  - Duration
  - Additional Info
  - Price (target variable)

## ⚙️ Methodology
1. **Data Cleaning**: Removed missing values, converted date/time columns, handled categorical data.
2. **Feature Engineering**: Extracted day, month, and time-based features.
3. **Exploratory Data Analysis (EDA)**: Visualized price trends, correlations, and distributions.
4. **Model Training**:
   - Tried Linear Regression, Decision Tree, Gradient Boosting, and Random Forest
   - Selected **Random Forest** as the best model
5. **Evaluation**: Measured performance using R² score and Mean Absolute Error.

## 📊 Results
- **Best Model**: Random Forest Regressor
- **R² Score**: 0.910
- **Mean Absolute Error**: 1383.88 INR

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Joblib

## 🚀 How to Run
```bash
git clone <repo_link>
cd flight-price-prediction
pip install -r requirements.txt
jupyter notebook 18.2_flight_price_prediction.ipynb
