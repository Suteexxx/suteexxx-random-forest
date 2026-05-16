# Random Forest Classifier - From Scratch to Production

A complete implementation of **Random Forest** using scikit-learn on a synthetic dataset generated with `make_classification`.

---

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [What You'll Learn](#what-youll-learn)
- [Results](#results)
- [Overfitting & Underfitting Analysis](#overfitting--underfitting-analysis)
- [Hyperparameter Tuning](#hyperparameter-tuning)

---

## 📊 Overview

This project demonstrates a full **Machine Learning pipeline** using Random Forest Classifier:
- Synthetic data generation
- Exploratory Data Analysis (EDA)
- Model training & evaluation
- Hyperparameter tuning
- Overfitting/Underfitting detection

---

## 🗃️ Dataset

- **Dataset Used**: `make_classification` (scikit-learn)
- **Samples**: 1000
- **Features**: 20 (15 informative + 5 redundant)
- **Task**: Binary Classification
- **Purpose**: Controlled environment to study model behavior

---

## ✨ Features

- Full EDA (Statistical summary, correlation heatmap, boxplots)
- Train-Test split with stratification
- Feature scaling
- Default Random Forest model
- Hyperparameter tuning using GridSearchCV
- Detailed evaluation metrics
- Learning curves for bias-variance analysis
- Feature importance visualization

---

## 🛠️ Installation

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
