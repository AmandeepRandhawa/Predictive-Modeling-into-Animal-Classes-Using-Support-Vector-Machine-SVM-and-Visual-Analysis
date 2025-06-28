# Predictive-Modeling-into-Animal-Classes-Using-Support-Vector-Machine-SVM-and-Visual-Analysis


# Predictive Modeling and Visual Insights into Animal Classes Using Support Vector Machine (SVM) and Advanced R Visualizations

**Author:** Amandeep Randhawa  
**Date:** June 28, 2025  

## 📌 Overview

This project explores animal classification using the **Zoo dataset**, applying machine learning techniques and advanced visualizations in **R**. The main objective is to predict the class of animals based on their physical and biological characteristics using **Support Vector Machine (SVM)**, followed by insightful visual analysis.

## 🧠 Key Concepts

- **Supervised Machine Learning (SVM Classification)**
- **Model Evaluation** (Accuracy, Confusion Matrix, Sensitivity, Specificity)
- **Data Preprocessing & Feature Engineering**
- **Dimensionality Reduction** (PCA & t-SNE)
- **Data Visualization** using `ggplot2`, `Rtsne`, `caret`, `randomForest`, and more

## 📂 Dataset

Two CSV files were used:
- `zoo.csv`: Contains 18 features for 101 animals and their class label.
- `class.csv`: Provides mappings between numeric class labels and class names.

## 🛠️ Tools & Packages Used

- `e1071` (SVM)
- `caret` (Model evaluation)
- `ggplot2` (Visualizations)
- `randomForest` (Feature importance)
- `Rtsne` (t-SNE visualization)
- `dplyr`, `reshape2`, `scales`, `vcd`, and others

## 📊 Visualizations Included

- 📌 **Class Distribution**: Bar chart, pie chart, and lollipop chart of animal class counts
- 🔍 **Feature Exploration**: Histograms, boxplots, pair plots
- 🧠 **Model Diagnostics**:
  - Confusion matrix heatmap
  - Accuracy bar chart
  - Actual vs Predicted comparison
- 🌐 **Dimensionality Reduction**:
  - PCA 2D projection
  - t-SNE visualization
- 🌲 **Random Forest Feature Importance**
- 📦 **Mosaic plot** (e.g., Hair vs Class Type)

## ✅ Results

- Achieved **high accuracy** using tuned SVM
- Excellent **class separation** shown in PCA and t-SNE
- Identified important predictors (e.g., legs, milk, feathers)
- Balanced accuracy for each class analyzed to assess model fairness

## 📄 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/animal-classification-svm.git
   cd animal-classification-svm
