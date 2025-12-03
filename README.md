# ML Prediction Pipeline — Customer Intent Modeling

This repository implements a reproducible machine learning pipeline for customer intent modeling, including robust data preprocessing, feature engineering, model training, evaluation and serialization for deployment.

The focus areas:
- Data ingestion and validation
- Feature engineering and transformation
- Model training, hyperparameter baseline, and evaluation
- Model persistence for downstream inference and deployment
- Lightweight experiment logging and reproducibility

## Tech Stack
- Python 3.10+
- pandas, numpy
- scikit-learn
- joblib

## Repository Contents
- `dataset.csv` — representative tabular dataset for binary classification (age, income, target)
- `train.py` — orchestrates preprocessing, model training, evaluation and model export
- `inference.py` — minimal inference example to load exported model and predict
- `requirements.txt` — runtime dependencies
- `notebooks/` — optional exploratory notebooks and model analysis

## How to run (local)
1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
