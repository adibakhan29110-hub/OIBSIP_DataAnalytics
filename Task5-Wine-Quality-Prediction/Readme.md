# Wine Quality Prediction 🍷

## Overview

This project focuses on predicting wine quality using machine learning classification
techniques. By analyzing the chemical properties of wine samples, the project aims to
classify wine quality and demonstrate the practical application of machine learning in
the field of viticulture.

Both **red** and **white** wine datasets are used to build and compare multiple
classification models.

---

## Dataset

The datasets used in this project are:
- `winequality-red.csv`
- `winequality-white.csv`

Each dataset contains physicochemical attributes such as acidity, density, sulphates,
and alcohol content.

**Target Variable:**
- `quality` (converted into a binary class: good or low quality)

---

## Project Structure

Task5-Wine-Quality-Prediction/
│
├── data/
│ └── raw/
│ ├── winequality-red.csv
│ └── winequality-white.csv
│
├── notebooks/
│ └── wine_quality_prediction.ipynb
│
├── reports/
│ └── figures/
│ ├── correlation_heatmap.png
│ └── model_comparison.png
│
├── report.md
└── README.md


---

## Machine Learning Models Used

The following classification models were implemented and evaluated:

- Random Forest Classifier
- Stochastic Gradient Descent (SGD) Classifier
- Support Vector Classifier (SVC)

---

## Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling and selection
4. Model training
5. Model evaluation and comparison
6. Visualization of results

---

## Key Insights

- Alcohol content shows a strong positive correlation with wine quality.
- Random Forest performed best among the tested models.
- Feature scaling significantly improved model performance.
- Combining red and white wine datasets enhances model generalization.

---

## Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Results

The Random Forest Classifier achieved the highest accuracy and demonstrated robust
performance across evaluation metrics such as precision, recall, and F1-score.

---

## Conclusion

This project demonstrates an end-to-end machine learning workflow, from data analysis
to model evaluation, applied to a real-world dataset. It highlights the importance of
feature engineering, model selection, and performance evaluation in predictive modeling.

---

## Author

**Adiba Khan**

