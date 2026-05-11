# Part 1: Customer Churn Prediction using Neural Network

## Project Overview
This project builds a **Feed-Forward Neural Network** to predict customer churn using the `customer_churn_nn.csv` dataset. The project demonstrates data preprocessing, neural network architecture, training process, evaluation, and hyperparameter tuning.

## Dataset
- **File**: `customer_churn_nn.csv`
- **Rows**: 2000
- **Target Variable**: `churn` (Binary: 1 = Churned, 0 = Retained)
- **Imbalance**: Highly imbalanced (~1.55% churn rate)

## Features
- **Categorical**: `region`, `plan_type`, `contract_type`, `payment_method`
- **Numerical**: `tenure_months`, `monthly_charges_inr`, `avg_login_days_per_month`, etc.
- **Identifier**: `customer_id` (dropped)


## Repository Structure
part_1_neural_network_analysis/
├── notebook.ipynb
├── README.md
├── requirements.txt
├── customer_churn_nn.csv
├── data_dictionary.md
└── results/
├── model_comparison.csv
└── confusion_matrix.png


## Technologies Used
- Python 3
- PyTorch (Deep Learning)
- scikit-learn (Preprocessing & Splitting)
- Pandas, NumPy, Matplotlib, Seaborn


## Dataset Source Link

https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs




