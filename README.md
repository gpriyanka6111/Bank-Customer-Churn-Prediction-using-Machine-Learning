# 🏦 Bank Customer Churn Prediction using Machine Learning

Predict whether a bank customer will churn (leave) or stay using multiple classification models in Python.
Includes data preprocessing, EDA, model training, evaluation, and comparison.

## 📝 Description
Builds a churn prediction pipeline to help identify at-risk customers and improve retention.
Covers cleaning, encoding, scaling, training several classifiers, and visualizing results with clear metrics.

## 📊 Features
### Data Preprocessing
- Dropped irrelevant column (`customer_id`)
- One-hot encoded categorical features (`gender`, `country`)
- Scaled numerical features with `StandardScaler`
- Train/test split with `stratify=y`

### Exploratory Data Analysis (EDA)
- Correlation heatmap (numeric-only)
- Churn distribution plots (optional)

### Model Training & Evaluation
- Models compared:
  - Logistic Regression
  - Random Forest
  - KNN
  - Decision Tree
  - Naive Bayes (GaussianNB)
  - Support Vector Machine (SVM)
- Metrics used:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
- Visuals:
  - Confusion Matrix
  - ROC Curve
  - Bar charts for model comparison
- Bonus:
  - `LazyClassifier` for quick leaderboard

## 🧰 Tech Stack
- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Plotly, scikit-learn, Lazypredict
