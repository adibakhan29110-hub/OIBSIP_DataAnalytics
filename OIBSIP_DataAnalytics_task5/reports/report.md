# Wine Quality Prediction Report

## 1. Project Overview

This project focuses on predicting the quality of wine using machine learning classification
techniques. The goal is to analyze the chemical characteristics of wine and build predictive
models that can classify wine quality effectively. This project demonstrates a real-world
application of machine learning in the field of viticulture and quality assessment.

Two datasets were used:
- Red Wine Quality Dataset
- White Wine Quality Dataset

Both datasets contain physicochemical properties of wine samples and a quality score assigned
by experts.

---

## 2. Dataset Description

Each dataset includes the following chemical attributes:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

**Target Variable:**
- `quality` (integer score ranging from 0 to 10)

To simplify classification, wine quality was converted into a binary label:
- **Good Quality (1):** Quality ≥ 7
- **Low Quality (0):** Quality < 7

---

## 3. Data Preprocessing

The following preprocessing steps were performed:

- Loaded red and white wine datasets using Pandas.
- Added a `type` column to distinguish between red and white wine.
- Merged both datasets into a single dataframe.
- Checked for missing values and data consistency.
- Converted the quality score into a binary classification label.
- Scaled numerical features using `StandardScaler` to ensure uniformity across features.

---

## 4. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand feature distributions and relationships:

- Statistical summaries were generated using descriptive statistics.
- Class distribution of wine quality was analyzed.
- A correlation heatmap was created to identify relationships between chemical features.

### Key Observations:
- Alcohol content shows a strong positive correlation with wine quality.
- Density and acidity features show moderate correlations.
- The dataset is moderately imbalanced, with more low-quality samples.

---

## 5. Model Development

Three classification models were implemented and compared:

1. **Random Forest Classifier**
2. **Stochastic Gradient Descent (SGD) Classifier**
3. **Support Vector Classifier (SVC)**

The dataset was split into training and testing sets (80/20 split) to evaluate model performance
fairly.

---

## 6. Model Evaluation

Models were evaluated using:
- Accuracy Score
- Precision, Recall, and F1-Score

### Performance Summary:
- **Random Forest** achieved the highest accuracy and overall balanced performance.
- **SVC** performed well but required more computational resources.
- **SGD Classifier** was fast but less accurate compared to the other models.

A bar chart comparing model accuracies was generated to visually compare performance.

---

## 7. Results and Insights

- Chemical properties such as alcohol, sulphates, and density significantly influence wine
  quality.
- Ensemble methods like Random Forest outperform linear models for this dataset.
- Feature scaling plays a crucial role in improving model performance.

---

## 8. Conclusion

This project successfully demonstrates the application of machine learning classifiers to
predict wine quality based on chemical attributes. The Random Forest model proved to be the most
effective among the tested algorithms. This project highlights the importance of data
preprocessing, feature analysis, and model comparison in building reliable predictive systems.

---

## 9. Future Improvements

- Perform hyperparameter tuning to further improve model performance.
- Use multi-class classification instead of binary labels.
- Explore advanced models such as XGBoost or LightGBM.
- Address class imbalance using resampling techniques.

---

## 10. Tools and Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Jupyter Notebook

