# Gold-Price-Prediction-using-Machine-Learning
This project uses Python and machine learning to predict gold prices based on historical data. The goal is to build a predictive model that can help investors and analysts understand the factors influencing gold prices and forecast future trends.

Designed and implemented a predictive model for gold prices using historical financial indicators (SPX, Oil, Silver, EUR/USD).

Conducted EDA, feature engineering, and preprocessing to uncover market patterns and correlations.

Evaluated multiple ML algorithms; Random Forest Regressor delivered the best performance (R² ≈ 0.97).

Visualized feature importance and trends with Matplotlib & Seaborn, providing insights into key market drivers.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost.


📊 Features

✅ Predict gold prices using historical data

✅ Exploratory Data Analysis (EDA) to understand key trends and correlations

✅ Feature engineering & data preprocessing

✅ Model training & evaluation


📁 Dataset

Dataset: gold_data.csv

Contains historical gold price data and related features.

🧰 Tools & Libraries
Python

Libraries Used:

numpy — numerical computations

pandas — data manipulation

seaborn & matplotlib — data visualization

scikit-learn — machine learning algorithms & tools

random forest — prediction model

🤖 Why Random Forest?

The Random Forest algorithm was chosen because:

It is robust to overfitting and performs well on tabular data.

It can handle non-linear relationships between features and the target.

It provides feature importance scores, helping to understand which factors most influence gold prices.

It works well with both small and large datasets, and can capture complex interactions in the data.

⚖️ Algorithm Comparison

Different algorithms were tested to evaluate performance:


| Algorithm             | Strengths                                               | Weaknesses                          | Expected Performance on Dataset     |
| --------------------- | ------------------------------------------------------- | ----------------------------------- | ----------------------------------- |
| **Linear Regression** | Simple, interpretable                                   | Cannot model non-linear trends      | Moderate (R² \~ 0.85)               |
| **Ridge / Lasso**     | Handles multicollinearity, Lasso does feature selection | Still linear, may underfit          | Similar to Linear (R² \~ 0.85–0.88) |
| **Decision Tree**     | Captures non-linear patterns, interpretable rules       | Prone to overfitting                | Better (\~0.90 R²), but unstable    |
| **Random Forest**     | Robust, reduces overfitting, high accuracy              | Slower training, less interpretable | Best (\~0.95–0.97 R²)               |


👉 Final choice: Random Forest since it balances accuracy, stability, and interpretability better than other models.

🚀 How to Run

1️⃣ Clone this repository or download the code.

2️⃣ Install the dependencies:pip install numpy pandas matplotlib seaborn scikit-learn

3️⃣ Place the gold_data.csv file in the project directory.

4️⃣ Run the Python script or notebook: Code to run this project is in another uploaded file


📌 Insights

Analyzed trends and patterns in gold price data.

Identified key features influencing the gold price.

Built a Random Forest model that predicts gold price with good accuracy.

👤 Author

Avadhoot Wamane
📧 avadhootwamane461@gmail.com 
🌐 LinkedIn- https://www.linkedin.com/in/avadhoot-wamane/

