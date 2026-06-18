# Spatiotemporal Demand Forecasting System

## Overview

Developed a machine learning pipeline to forecast demand across geospatial regions using spatial, temporal, and road-network characteristics. The project focuses on identifying high-impact demand drivers and optimizing predictive performance through feature engineering and gradient-boosting models.

## Dataset

- 77,000+ observations
- 1,249 geospatial regions
- Spatial, temporal, and traffic-related features

## Features Used

- Geohash Location Encoding
- Road Type
- Number of Lanes
- Large Vehicle Access
- Cyclical Time Features
- Road Type × Vehicle Access Interaction

## Methodology

- Data Cleaning and Preprocessing
- Geospatial Feature Engineering
- Temporal Feature Engineering
- Feature Selection and Pruning
- Hyperparameter Optimization
- Model Benchmarking

## Models Evaluated

- CatBoost Regressor
- XGBoost Regressor
- LightGBM Regressor

## Results

- Improved validation R² from **0.80** to **0.86+**
- Evaluated 20+ feature engineering and optimization iterations
- Identified key spatial and road-network demand drivers
- Achieved robust generalization on unseen spatial and temporal data

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Matplotlib
- Seaborn

## Project Structure

```text
├── spatiotemporal_demand_forecasting.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Ensemble Modeling
- Advanced Spatial Feature Extraction
- Graph-Based Road Network Features
- Real-Time Demand Forecasting
