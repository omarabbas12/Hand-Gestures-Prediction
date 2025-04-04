This repository contains a comprehensive implementation of hand gesture recognition using the HaGRID dataset – a large-scale dataset featuring 18 different hand gestures, each labeled and extracted using MediaPipe with 21 hand landmarks per hand in (x, y, z) format.

🔍 Project Overview
Utilized the HaGRID dataset for training and evaluation.

Preprocessed landmark data from CSV format.

Implemented multiple machine learning models for classification.

Achieved 98.4% accuracy using LightGBM (LGBM), outperforming traditional models.

✅ Features
Data loading and preprocessing pipeline.

Support for multiple models including Random Forest, SVM, XGBoost, and LightGBM.

Detailed evaluation metrics (accuracy, confusion matrix, classification report).

Visualization of model performance.

Hyperparameter tuning for optimal results.

📊 Dataset
HaGRID (Hand Gesture Recognition Image Dataset)

18 hand gesture classes.

Extracted using MediaPipe.

Input: 21 hand landmarks per hand (x, y, z).

📈 Best Model
LightGBM (LGBMClassifier)

Achieved 98.4% test accuracy

Fast training time and excellent generalization
