# ☀️ Solar Power Estimation using Hybrid ML Models

## 🎯 Project Goal
To accurately predict solar power output (in kW) using time-series data, improving the efficiency and reliability of energy management systems.

## 🧠 Model Architecture & Methodology
This project uses a comparative approach, evaluating the performance of three key models:

1.  **XGBoost (Extreme Gradient Boosting):** For robust performance and handling non-linear relationships.
2.  **Random Forest:** As a baseline ensemble method.
3.  **LSTM (Long Short-Term Memory):** Specifically used for its strength in sequence prediction and time-series forecasting.

## 📊 Key Results & Evaluation
* **Evaluation Metric:** Root Mean Squared Error (RMSE) was chosen for regression task evaluation.
* **Best Performance:** The **Hybrid LSTM-XGBoost** model achieved the lowest RMSE of **[Insert Your Actual RMSE Value Here]**.
* **Key Finding:** [Briefly state the main insight, e.g., "Feature engineering with time-of-day variables significantly improved model performance."]

## 🛠️ Technology Stack
* **Language:** Python 3
* **Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `XGBoost`, `Keras/TensorFlow` (for LSTM implementation), `Matplotlib/Seaborn` (for visualization).

## 💡 Running the Code
1.  **Clone the repository:** `git clone https://github.com/priya220405/Solar-Power-Estimation-ML.git`
2.  **Install dependencies:** `pip install -r requirements.txt` (If you create a `requirements.txt` file listing all libraries).
3.  Open and run the main notebook/script.
