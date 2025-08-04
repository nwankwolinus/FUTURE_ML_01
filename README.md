# 📊 Customer Churn Prediction System

This project is a Machine Learning-based Churn Prediction System developed as part of the Future Interns ML Internship. It uses real customer data to predict which users are likely to stop using a service, helping businesses improve retention strategies.

## 🚀 Features

- Predicts customer churn with high accuracy
- Trained with `scikit-learn`, `XGBoost`, and other ML models
- Visualizations for insights on model performance (RMSE, MAPE)
- Identifies best- and worst-performing stores
- Final results are aggregated and exported for reporting

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

## 📁 Structure

- `data/`: Preprocessed datasets
- `notebooks/`: Main training, forecasting, and evaluation notebooks
- `results/`: RMSE and MAPE evaluations per store
- `.gitignore`: Ignores datasets and environment files

## 📈 Results Snapshot

Best Performing Stores:
| Store | RMSE  | MAPE  |
|-------|-------|--------|
| 733   | 1494.89 | 7.86% |
| 1097  | 1162.64 | 8.29% |

Worst Performing Stores (High MAPE):
| Store | RMSE  | MAPE       |
|-------|--------|------------|
| 644   | 3112.95 | 2957562000000000000% |
| 817   | 4374.79 | 3237368000000000000% |

## 📌 How to Run

```bash
git clone https://github.com/yourusername/churn-prediction
cd churn-prediction
jupyter notebook
