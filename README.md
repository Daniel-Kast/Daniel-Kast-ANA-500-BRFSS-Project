# Daniel-Kast-ANA-500-BRFSS-Project
Using BRFSS to examine the risk factors in Diabetes

# 🩺 Diabetes Prediction Benchmarking

This project explores multiple machine learning models to predict diabetes using tabular health data. It compares traditional classifiers, deep learning architectures, and reconstruction-based anomaly detection to evaluate performance across key metrics.

## 📌 Project Goals

- Build and evaluate interpretable models for binary classification
- Compare performance across recall, precision, F1, ROC AUC, and average precision
- Explore threshold tuning and reconstruction error strategies
- Document reproducible workflows for educational and stakeholder use

## 🧠 Models Evaluated

- Logistic Regression (baseline, balanced, tuned)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest (default and tuned)
- Gradient Boosting
- Naive Bayes
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)
- TabTransformer
- Autoencoder (reconstruction-based)

## 📊 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision, Recall, F1 Score (for minority class)
- ROC AUC
- Average Precision (AP)
- Confusion Matrix
- Classification Report

## 🧪 Notebooks & Workflow

- `data_preprocessing.ipynb`: Scaling, encoding, and train-test split
- `model_training.ipynb`: Pipelines for each classifier
- `evaluation_summary.ipynb`: Metric comparison and visualizations
- `autoencoder.ipynb`: Reconstruction error and thresholding
- `tabtransformer.ipynb`: Deep learning with categorical embeddings

## 📚 Learning Journey

This repository is maintained by a student of machine learning and a retired U.S. Navy veteran currently leading facilities operations at Navy Federal. It reflects a hands-on approach to learning, benchmarking, and sharing reproducible ML workflows.

## ✅ Next Steps

- Add ensemble strategies and threshold tuning
- Explore SHAP or LIME for model interpretability
- Deploy best-performing model with a simple UI

---
