# AI-Based DDoS Attack Detection System

## Overview

This project presents an AI-based system for detecting Distributed Denial-of-Service (DDoS) attacks using machine learning and deep learning techniques.

The system performs data preprocessing, feature engineering, dimensionality reduction, class balancing, and model training to classify different attack categories.

## Dataset

The project uses the CICIoT2023 dataset from Kaggle.

The original dataset was distributed across multiple files. These files were consolidated into a single dataset to simplify preprocessing and model training.

## Data Preprocessing

- Missing value removal
- Label encoding
- Feature standardization using StandardScaler
- Dimensionality reduction using PCA
- Class balancing using SMOTE

## Models Used

- CatBoost Classifier
- Random Forest Classifier
- LSTM Neural Network
- LightGBM Stacking Ensemble

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

## Technologies

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- CatBoost
- LightGBM
- Matplotlib
- Seaborn

## Project Structure

```
DDoS-Attack-Detection-System.ipynb
requirements.txt
README.md
```

## Author

Gomana Anasiry

## Future Improvements

- Real-time traffic analysis
- Model deployment
- Integration with network monitoring systems
