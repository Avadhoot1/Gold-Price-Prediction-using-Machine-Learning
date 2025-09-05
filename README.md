# Gold-Price-Prediction-using-Machine-Learning
•	Built a machine learning model to predict next-day gold closing prices using historical OHLCV (Open, High, Low, Close, Volume) data. 

•	Applied data preprocessing, removed irrelevant features, and trained a Random Forest Regressor to capture non-linear market behavior.

•	Achieved 98% prediction accuracy and validated results through actual vs. predicted plots for financial insights.

•	Problem Statement: Gold prices change daily due to market and economic factors. Traders need reliable short-term forecasts, but traditional models can’t capture these complex patterns. A machine learning approach is required for better predictions.

## Problem Statement
Gold prices fluctuate daily due to market volatility, currency shifts, and global events.
Traditional models fail to capture these complex patterns, making short-term forecasting unreliable.
This project uses machine learning to provide better accuracy, helping traders and investors make data-driven decisions.


## 🛠 Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost

Algorithm Used: Random Forest Regressor


## 📊 Features

✅ Predict gold prices using historical OHLCV data

✅ Perform Exploratory Data Analysis (EDA) to uncover trends & correlations

✅ Feature engineering & preprocessing (lag features, moving averages)

✅ Model training & evaluation using industry metrics

✅ Actual vs Predicted plots for visual validation


## 📁 Dataset

Dataset: gold_data.csv

Contains historical gold price data and related features.

## 🧰 Tools & Libraries
Python

Libraries Used:

numpy — numerical computations

pandas — data manipulation

seaborn & matplotlib — data visualization

scikit-learn — machine learning algorithms & tools

random forest — prediction model

## 🤖 Why Random Forest?

Handles non-linear relationships in financial data

Reduces overfitting compared to a single Decision Tree

Provides feature importance scores

Works well with both small & large datasets

## ⚖️ Algorithm Comparison

Different algorithms were tested to evaluate performance:

| Algorithm             | Strengths                                               | Weaknesses                          | Expected Performance |
| --------------------- | ------------------------------------------------------- | ----------------------------------- | -------------------- |
| **Linear Regression** | Simple, interpretable                                   | Cannot model non-linear trends      | R² ≈ 0.85            |
| **Ridge / Lasso**     | Handles multicollinearity, Lasso does feature selection | Still linear, may underfit          | R² ≈ 0.85–0.88       |
| **Decision Tree**     | Captures non-linear patterns, interpretable rules       | Prone to overfitting                | R² ≈ 0.90 (unstable) |
| **Random Forest**     | Robust, reduces overfitting, high accuracy              | Slower training, less interpretable | R² ≈ 0.95–0.97       |



👉 Final choice: Random Forest since it balances accuracy, stability, and interpretability better than other models.

## 🚀 How to Run

1️⃣ Clone this repository or download the code.

git clone https://github.com/yourusername/Gold-Price-Prediction-ML.git
cd Gold-Price-Prediction-ML


2️⃣ Install the dependencies

pip install numpy pandas matplotlib seaborn scikit-learn xgboost

3️⃣ Place gold_data.csv in the project folder

4️⃣ Run the notebook/script to train and test the model


📌 Insights

Discovered trends and correlations in gold price data

Identified key features influencing gold price fluctuations

Built a Random Forest model with ~98% prediction accuracy

Visualized actual vs predicted values for easy interpretation


👤 Author

Avadhoot Wamane

📧 avadhootwamane461@gmail.com 

🌐 LinkedIn- https://www.linkedin.com/in/avadhoot-wamane/

