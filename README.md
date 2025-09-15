🏦 Bank Customer Churn Prediction using Machine Learning

This project predicts whether a bank customer will churn (leave) or stay using multiple classification models in Python.
It helps banks identify customers at risk of leaving, so they can take action to improve customer retention.
The project covers the full pipeline: data preprocessing, exploratory analysis, model training, evaluation, and comparison.

📊 Features
Data Preprocessing

Dropped irrelevant column (customer_id).

Converted categorical features (gender, country) using one-hot encoding.

Scaled numerical features with StandardScaler.

Split data into training and testing sets.

Exploratory Data Analysis (EDA)

Correlation heatmaps to check feature relationships.

Visualizations of churn distribution and feature importance.

Model Training & Evaluation

Trained and compared:

Logistic Regression

Random Forest

KNN

Decision Tree

Naive Bayes

Support Vector Machine (SVM)

Evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC-AUC score

Bonus: Used LazyClassifier for instant model benchmarking.

Model Comparison

Visualized results with bar charts (Accuracy, Precision, Recall, F1, AUC).

Plotted ROC curves to compare classifier performance.

🧰 Tech Stack

Python 3.x

Libraries:

NumPy, Pandas

Matplotlib, Seaborn, Plotly

scikit-learn

Lazypredict
