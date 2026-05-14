# Machine Learning Practice Project

This project was developed as part of the Machine Learning Practice (MLP) Project in the BS in Data Science and Applications program at IIT Madras.

The project focuses on building a multiclass machine learning classification system to predict comment categories from large-scale real-world internet comment data.

---

# Problem Statement

Developed a multiclass classification model to classify online comments into categories (0,1,2,3) while handling severe class imbalance using Macro F1 Score as the evaluation metric.

---

# Exploratory Data Analysis

Performed detailed exploratory data analysis on approximately 198,000 comments and 15 features.

## Key Insights
- Severe class imbalance:
  - Label 0 → 57%
  - Label 3 → 2.7%
- High missing values in identity-related columns
- Analyzed:
  - comment lengths
  - word counts
  - voting patterns
  - feature distributions

## Visualization Techniques
- Correlation heatmaps
- Boxplots
- Distribution plots
- Feature analysis charts

---

# Data Preprocessing

Implemented preprocessing techniques including:

- Text cleaning
- URL removal
- Missing value handling
- Datetime feature extraction
- Feature engineering:
  - capital letter count
  - exclamation marks
  - question marks

- One-hot encoding for categorical features

---

# Feature Engineering

## TF-IDF Features
- Word-level TF-IDF
- Character-level TF-IDF
- Unigrams, bigrams, and trigrams

## Additional Features
- Numerical metadata features
- Sparse matrix feature combination

## Total Features
- 120,000+ engineered features

---

# Machine Learning Models Used

Implemented and compared multiple machine learning models:

1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear SVM
4. SGD Classifier
5. LightGBM

---

# Results

## Best Performing Model
LightGBM

## Performance
- Validation Macro F1 Score: 0.80
- Kaggle Leaderboard Score: 0.835+

## Optimization
Performed hyperparameter tuning for:
- learning rate
- tree depth
- number of leaves

---

# Viva Experience

## Level 1 Viva
- Notebook walkthrough
- EDA explanation
- Feature engineering discussion
- Model comparison

## Level 2 Viva
Discussed:
- Gradient Boosting
- Loss functions
- Bias-Variance Tradeoff
- Sparse matrices
- Regularization
- Data leakage prevention

---

# Final Results

- Notebook Score: 10/10
- Viva Score: 46/50
- Kaggle Score: 0.835+
- Successfully passed both Level 1 & Level 2 Vivas

---

# Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- SciPy
- Matplotlib
- Seaborn
- Kaggle

---
