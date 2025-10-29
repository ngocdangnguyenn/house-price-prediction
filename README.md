# House Price Prediction
Practical machine learning project implementing a reproducible pipeline for residential property price prediction. Focused on comprehensive data analysis, robust feature engineering, and systematic model evaluation.
Achieves **99.96% R² Score** with **RMSE of 1,445.92** and **MAE of 920.44** on the held-out test set (RandomForest with optimized hyperparameters).

## Overview
This project uses a housing price dataset and employs RandomForest regression with optimized hyperparameters to predict house prices. The pipeline processes various housing features (e.g., square footage, bedrooms, engineered features), handles feature scaling, and produces a production-ready model for highly accurate price estimation.
Key features include robust data preprocessing, engineered features for better predictability (log transforms, price per sqft, room ratios), and careful model validation to ensure reliable performance. The final model demonstrates exceptional predictive capability with near-perfect R² score on the test set.

## Quick Start
```bash
git clone https://github.com/ngocdangnguyenn/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
jupyter notebook notebooks/
```

## Project Structure
```
house-price-prediction/
├── data/
│   ├── raw/                    # Original dataset
│   └── processed/              # Engineered features & scaler
├── models/                     # Trained model
├── notebooks/                  # Analysis & modeling notebooks
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_training.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Contact
- Email: nndnguyen2016@gmail.com
- LinkedIn: https://www.linkedin.com/in/ngocdangnguyenn
- Portfolio: https://ngocdangnguyenn.github.io/portfolio/ 
