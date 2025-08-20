# PRODIGY_DS_03
"Built and evaluated a Decision Tree Classifier on Bank Marketing dataset achieving X% accuracy, with visualized decision paths."


# Task 03: Decision Tree Classifier (Bank Marketing Dataset)
# 📌 Project Overview

This project builds a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and marketing campaign data.

# 🛠️ Workflow

Dataset Setup

Loaded Bank Marketing dataset (UCI Repository).

Checked structure, types, and missing values.

Preprocessing

Encoded categorical variables using Label Encoding.

Split dataset into features (X) and target (y).

# Train-Test Split

Divided dataset into 80% training and 20% testing sets.

# Model Training

Trained a DecisionTreeClassifier with controlled depth to avoid overfitting.

Model Evaluation

Accuracy Score

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

# Visualization

Visualized the decision tree using plot_tree.

Insights

Decision Tree identified key features (e.g., age, balance, duration) influencing customer subscription.

Achieved reasonable accuracy on test data.

# 🛠️ Tools & Libraries

Python (Google Colab / Jupyter Notebook)

pandas, numpy

scikit-learn (DecisionTreeClassifier, train_test_split, metrics)

matplotlib, seaborn

# 📊 Deliverables

Cleaned & preprocessed dataset

Decision Tree Classifier model

Model evaluation metrics

Decision Tree visualization
