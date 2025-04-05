# 💧 Water Quality Classification - Machine Learning Project

This project aims to classify the **potability of water** using supervised machine learning algorithms such as **XGBoost** and **SVM (Support Vector Machine)**. It involves data preprocessing, handling class imbalance using SMOTE, training classification models, evaluating their performance, and visualizing results using confusion matrices and heatmaps.

---

## 📌 Project Highlights

- ✅ Preprocessing missing values
- ✅ Feature scaling using MinMaxScaler
- ✅ Balancing dataset using SMOTE (Synthetic Minority Over-sampling Technique)
- ✅ Feature importance analysis using ExtraTreesClassifier
- ✅ Correlation heatmap using seaborn
- ✅ Classification using:
  - XGBoost
  - SVM (Linear Kernel)
- ✅ Performance Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## 📁 Files Included

| File                        | Description                                  |
|----------------------------|----------------------------------------------|
| `Water_Quality_Classification.ipynb` | Colab notebook with all code and explanations |
| `water_quality.csv`        | Dataset used for training and testing        |
| `output_graphs/`           | Output visualizations (confusion matrix, etc.) |

---

## 📊 Dataset Info

- **Source**: Water Quality Dataset (binary classification)
- **Target column**: `Potability` (0 = Not potable, 1 = Potable)
- **Attributes**: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity

---

## 🧠 Algorithms Used

1. **XGBoost Classifier**  
   - Handles imbalance well  
   - Achieved higher performance scores

2. **SVM (Support Vector Machine)**  
   - Linear kernel  
   - Baseline comparison model

---

## 📈 Performance Metrics

| Model  | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| XGBoost | ✅ High (e.g., ~78%) | ✅ High | ✅ High | ✅ High |
| SVM     | Moderate (~51%)     | Moderate | Moderate | Moderate |

*Detailed outputs and charts are inside the notebook.*

---

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Run `Water_Quality_Classification.ipynb` in [Google Colab](https://colab.research.google.com/).
3. Install required packages like `xgboost`, `imbalanced-learn`, etc.
4. Upload the `water_quality.csv` dataset if needed.
5. Run all cells and check the outputs.

---

## 📣 Connect With Me

I'm actively learning and building ML projects. Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/prasannavenkatesh23/).

---

## 📌 Tags

#machinelearning #xgboost #svm #datascience #python #classification #mlprojects #studentproject #fresher #colab #github #kaggle #imbalanceddata #mlmodel #linkedinproject #featureengineering #waterquality
