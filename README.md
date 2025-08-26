🌞 Solar Energy Prediction using Stacked Ensemble Models
📌 Project Overview

This project was developed for the Solar Energy Prediction Challenge.
The goal is to forecast solar energy generation (generation_W) and load (load_W) using historical data and system metadata.

A stacked ensemble learning approach was implemented, combining LightGBM, XGBoost, CatBoost (GPU), and ElasticNet (CPU) with Ridge Regression as the meta learner.

⚙️ Features

Data Preprocessing:

Merge metadata with training/testing datasets.

Feature engineering: time-based, lag, and rolling window features.

Encoding categorical variables.

Model Training:

GroupKFold cross-validation.

GPU-accelerated LightGBM, XGBoost, CatBoost.

ElasticNet for linear learning.

Ridge Regression for stacking.

Evaluation:

Out-of-Fold (OOF) validation using Mean Absolute Error (MAE).

Submission:

Generates a submission.csv file with predictions for evaluation.
