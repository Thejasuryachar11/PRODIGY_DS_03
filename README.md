# PRODIGY_DS_03
"Built and evaluated a Decision Tree Classifier on Bank Marketing dataset achieving X% accuracy, with visualized decision paths."


# PRODIGY_DS_03 - Decision Tree Classifier (Bank Marketing Dataset)

## 🎯 Objective
The goal of this task is to **build a Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their **demographic and behavioral data** using the **Bank Marketing dataset** from the UCI Machine Learning Repository.

---

## 🛠 Workflow

### 1. Load Dataset
- Used the **Bank Marketing dataset**.
- Inspected shape, columns, and data types.

### 2. Data Preprocessing
- Encoded categorical variables (`job`, `marital`, `education`, `contact`, `month`, etc.) using Label Encoding.
- Converted target column `y` → **(Yes = 1, No = 0)**.
- Split data into **training (80%)** and **testing (20%)**.

### 3. Model Building
- Used **DecisionTreeClassifier** from `scikit-learn`.
- Limited `max_depth` to prevent overfitting.
- Trained the model on training data.

### 4. Model Evaluation
- Calculated **Accuracy, Precision, Recall, F1-score**.
- Generated a **Confusion Matrix** to evaluate classification performance.
- Analyzed **Feature Importances** to understand key predictors.

### 5. Visualization
- Exported the tree using `export_graphviz`.
- Visualized the decision tree with **Graphviz** and `plot_tree`.

---

## 📊 Key Insights
- **Duration** of the call and **previous campaign outcome** were highly predictive.
- Customer **age** and **job type** also influenced subscription probability.
- Decision Tree provided interpretable rules for customer targeting.

---

## 💻 Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn)
- **Matplotlib / Seaborn**
- **Graphviz** (for decision tree visualization)
- **Jupyter Notebook**

---

## 📂 Repository Structure
'''bash
PRODIGY_DS_03/
│── bank.ipynb # Notebook with code and analysis
│── decision_tree.pdf # Visualization of trained tree
│── README.md # Documentation

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/thejasuryachar11/PRODIGY_DS_03.git
   cd PRODIGY_DS_03
   jupyter notebook bank.ipynb


