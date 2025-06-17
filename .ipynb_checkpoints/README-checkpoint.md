
# RUL Prediction with Random Forest

This project predicts Remaining Useful Life (RUL) using NASA’s CMAPS dataset and a Random Forest Regressor.

## Overview

- Dataset: NASA CMAPS (train_FD001.txt)
- Model: Random Forest Regressor
- Metrics: MAE = 29.69, RMSE = 41.52
- Visuals: Actual vs Predicted RUL, Feature Importance, Error Distribution

## Highlights

- Data preprocessed by computing max cycle per unit
- Trained on 21 sensor signals and operational settings
- Visualizations provided to explain model behavior

## Structure

icr_ai_project/
├── rul_prediction.ipynb
├── requirements.txt
├── output_plots/
│   ├── actual_vs_predicted.png
│   ├── error_distribution.png
│   └── feature_importance.png
└── README.md

## How to Run

git clone https://github.com/Himansh97/rul-prediction.git  
cd rul-prediction  
pip install -r requirements.txt  
jupyter notebook rul_prediction.ipynb
