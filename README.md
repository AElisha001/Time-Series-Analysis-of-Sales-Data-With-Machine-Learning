# Time-Series-Analysis-of-Sales-Data-With-Machine-Learning

---

# 🧠 Time-Series Analysis of Sales Data With Machine Learning

A practical and research-driven implementation of **multi-step sales forecasting** using **XGBoost** and comparative benchmarking with **ARIMA**. This project demonstrates the application of machine learning for time-series analysis, with a focus on model interpretability, accuracy, and scalability.

---

## 📌 Project Overview

This project includes:


- Multi-step forecasting using **XGBRegressor** with a **direct-recursive strategy**
- Benchmarking with **ARIMA**
- Evaluation using **MAE** and **RMSE**
- Visual comparison of model performance
- A reproducible Jupyter notebook and Python scripts

---

## 🗃️ Dataset

We use the publicly available **Rossmann Sales Dataset**:
- 📥 [Download it from Kaggle](https://www.kaggle.com/c/rossmann-store-sales)

---

## 🚀 Quick Start

### 🔧 Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install numpy pandas matplotlib scikit-learn xgboost statsmodels jupyter
```

---

### 🧪 Run the Notebook

To run the full workflow and compare XGBoost vs ARIMA:

```bash
jupyter notebook sales_forecasting_example.ipynb
```

---

## 📂 Project Structure

```plaintext
Time-Series-Analysis-of-Sales-Data-With-Machine-Learning/
│
├── data/                           # Data directory (add your CSV here)
│   └── rossmann_sales.csv
│
├── notebooks/
│   └── sales_forecasting_example.ipynb     # Main notebook with experiments
│
├── scripts/
│   ├── preprocess.py              # Data cleaning and feature engineering
│   ├── train_xgboost.py           # Model training and evaluation
│   └── utils.py                   # Helper functions
│
├── figures/
│   └── sales_forecast_comparison.png       # Forecast visualization
│
├── requirements.txt
└── README.md
```

---

## 📈 Results Summary

| Model    | MAE     | RMSE    |
|----------|---------|---------|
| ARIMA    | 1584.4  | 2123.7  |
| XGBoost  | **1120.3**  | **1535.6**  |

> 🔍 *XGBoost significantly outperformed ARIMA in modeling non-linear sales trends.*

---

## 🧠 Key Concepts

- **XGBoost**: A tree-based ensemble learning model that handles complex, nonlinear data well.
- **Direct-Recursive Strategy**: A hybrid forecasting strategy that balances prediction accuracy and computational efficiency.
- **Explainability**: Discussed as part of ongoing research directions (e.g., SHAP, feature importance).

---

## 📚 Related Paper

📝 [Time-Series Analysis of Sales Data Using XGBoost – Research Paper](https://github.com/AElisha001/Time-Series-Analysis-of-Sales-Data-With-Machine-Learning/blob/main/time_series_analysis_with_xgboost.docx)

---

## 🧪 Reproducibility

This project was built using:
- Python 3.10
- XGBoost 1.7.4
- scikit-learn 1.2.1
- pandas 1.5.3
- statsmodels 0.13.x
- matplotlib 3.6.2

---

## 📬 Contact

Feel free to connect or collaborate:

**Author:** Elisha Archibong  
📧 [Email](mailto:elishaarchibong@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/elisha-archibong)
